# README #

### 개발 개요 ###

사내 프로젝트 (ASKHUB - 온디맨드 서비스) MVP 기간 동안 수집된 데이터를 시각화하기 위해 만든 웹 페이지입니다.
Referer 쿠폰 내역을 Network Graph로 시각화하여 친구 초대가 어떤 경로로 이루어졌는지 볼 수 있습니다.
딜리버리 서비스 이용 데이터를 지도 기반 Mark Cluster 로 시각화하여, 가게에서 주문한 이용자의 위치 / 이용자의 주문 건수 / 주문 최다 가게 등을 확인할 수 있습니다.

* 개발 기간 : 2019.8 ~ 2019.9
* 개발 인원 : 단독 개발
* 사용 스택 : Vue.js, node.js, Mysql

### Dataset ###
MVP 기간 동안 수집한 사용자 추천 정보 및 주문 정보를 사용하였으며, 개인정보는 csv 파일로 마스킹처리 는하였습니다.
실제 데이터는 Mysql에서 불러오며 연결 정보를 제외하였기에 csv 파일을 사용하였습니다.

### 데모 영상 ###
![Demo1](https://user-images.githubusercontent.com/8486747/128510853-45cffa38-b247-4351-9adf-5e4755e98ac5.gif)
![Demo2](https://user-images.githubusercontent.com/8486747/128508711-05aa8462-56b1-4e48-854e-2dc8941f2436.gif)
![Demo3-1(4)](https://user-images.githubusercontent.com/8486747/128510324-eb1ec38e-d64d-491d-a497-2a6524d64509.gif)
![Demo3-2(3)](https://user-images.githubusercontent.com/8486747/128510112-f0a54bbe-a358-490f-ad86-46492663d011.gif)

### 실행 방법 ###
<pre><code>
* frontend *
cd frontend
npm install
npm start

* backend *
cd backend
npm install
npm start
</pre></code>

