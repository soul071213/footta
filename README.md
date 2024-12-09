# foo타

## 개발 동기
평소 축구 경기를 시청하는 것도 즐기고 축구를 분석하는 것도 좋아하지만 축구 분석을 하는데 좋은 사이트가 없고 대부분 외국 사이트이기 때문에 자료를 잘 찾을 수 없기 때문에 이 사이트를 만들게 되었습니다.

## 프로젝트 목적
축구 데이터를 보기 쉽게 습득하는 사이트를 제작할 것 입니다.

### 사용 기술
react, pandas

### 데이터 분석
출처 : https://footystats.org/download-stats-csv

#### 데이터 유형 및 특징
csv로 되어 있으며 리그 팀별 데이터와, 선수 별 데이터, Match별 데이터,리그 데이터 이렇게 4개가 있다.

#### 데이터 처리 계획
팀별 데이터에서는 팀별 순위를 가져와야 하기 때문에 팀의 승리와 무승부를 가져와 승점을 계산할 것이고 승점을 기준으로 정렬할 것이다. 또한 선수별 데이터에서 선수 득점 순위와 도움을 기준으로 랭킹을 측정하고 match는 라운드 당 있었던 Match 데이터를 가져올 것이다.

### 유사 사례
#### SoccerWay
#### 시사점 또는 차이점
해외 사이트이기 때문에 한국인에게는 접근하기 어렵고 UI/UX가 오로지 데이터에만 치중되어 있어 사용자 친화적이지 않다.

## 서비스 개요 및 기능 설명
시즌에 해당하는 경기 정보와 선수 매치 정보를 랭킹 형식으로 볼 수 있게 할 것이다 또한 매치를 클릭하면 자세한 매치 정보를 볼 수 있다.

### 데이터 활용 방식
pandas에서 필요한 데이터를 filter하여 가져올것 이다.

### 기대효과
축구 정보를 손쉽게 확인 할 수 있어 많은 사람들이 축구에 쉽게 접근할 수 있을것이다.


