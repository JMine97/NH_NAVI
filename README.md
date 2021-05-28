## 나비날다 (기부 독려 서비스)
2020 NH디지털혁신캠퍼스 챌린지 온라인 해커톤 장려상 작품입니다!<br><br>

나비날다는 '언제, 어디서나 내가 원하는 기부를 쉽게 찾아 할 수 있게 하자!' 는 취지에서 출발했습니다.<br><br>

나비날다의 핵심 서비스는 크게 ’결제‘, ’기부 추천‘, ’커뮤니티‘입니다.<br>

첫째, 결제는 이용자 결제 금액의 특정 %를 기부하는 것으로 이용자가 설정한 퍼센트(%)가 기부로 이어지는 기능입니다. <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;간편결제를 이용하면 계좌번호, 금액 입력 후 기부 기관만 선택하면 기부할 수 있습니다.<br><br>
 둘째, 기부 추천은 이용자가 기부단체를 추천받는 기능입니다. <br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;크게 아동, 어르신, 장애인, 한 부모, 유기견, 자연재해로 구성되어 있으며, <br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;이용자는 관심 있는 분야, 봉사 방법(기부/자원봉사/펀딩 중 선택 가능), 희망 금액 카테고리 안에서 <br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;원하는 항목을 선택하여 기부할 수 있습니다. <br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;기부 전 이용자는 기부 기관 리스트를 클릭하여 기관 상세정보를 알 수 있습니다.<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;펀딩 기능은 현재 진행 중인 기부, 마감 임박 기부, 펀딩 오픈하기로 구성되며, 이용자가 원하는 펀딩을 할 수 있습니다.<br><br>
 셋째, 커뮤니티는 이용자가 최신 기부 소식(기부 관련 뉴스), 기부 이야기(서비스 이용자 간 의견 교류 기능)를 사용할 수 있습니다. <br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;자유롭게 자신의 기부 소식을 올릴 수 있으며 이를 통해 유대감을 형성할 수 있습니다.<br><br>
 마지막으로, 마이페이지에서는 현재 보유 기부금액, 나의 기부레벨, 나의 관심 기부 기관, 나의 관심 펀딩 기관을 확인할 수 있습니다.<br><br>



## 목차
* [사용 기술](#1-사용-기술)
* [주요 기능](#2-주요-기능)
* [역할 분배](#3-역할-분배)
* [발표 파일](#4-발표-파일)<br><br>



## 1. 사용 기술
안드로이드 스튜디오, 농협 API, 네이버 지식백과 API 이용합니다.

농협 계좌와 연결해 서비스 결제 및 잔액을 관리합니다.
네이버 지식백과 API를 이용해 기부 단체 및 기관의 정보를 확인할 수 있도록 했습니다. <br><br>


## 2. 주요 기능
### 대기화면
![image](https://user-images.githubusercontent.com/52027965/119978059-21819d00-bff4-11eb-9876-56d1c0f7b19a.png)<br><br><br>

### 홈화면
![image](https://user-images.githubusercontent.com/52027965/119977710-bb951580-bff3-11eb-85c9-5632f6478dad.png)<br><br>
현재 이용자의 금융계좌, 기부 카테고리, 진행중인 펀딩 등 핵심 서비스 확인 가능<br>
시각화를 통해 한 눈에 보유 기부금액, 나의 기부 레벨, 카드 사용내역을 볼 수 있음 <br><br><br>

### 기부하기
![image](https://user-images.githubusercontent.com/52027965/119978143-3eb66b80-bff4-11eb-9d14-2a2efda74ff6.png)<br><br>
* 기부 : 카테고리(추천기부 구성과 동일), 기관, 펀딩 기능으로 구성
* 추천기부 설정 : 이용자가 기부단체를 추천 받는 기능,
	              아동/어르신/장애인/한부모/유기견/자연재해로 구성
* 이용자는 관심 있는 분야, 봉사 방법(기관/자원봉사/펀딩), 희망 금액 안에서 기부 가능<br><br><br>

### 기부하기2
![image](https://user-images.githubusercontent.com/52027965/119978278-67d6fc00-bff4-11eb-9ea9-f02618fcff42.png)<br><br>
* 기부 : 기관 상세정보 확인 기능, 기관에 대한 접근성+신뢰도 확보 역할 수행
* 어플에 제시된 기부 단체 및 기관 : 내부적인 선정 절차를 통해 선정<br><br><br>

### 기부하기(펀딩)
![image](https://user-images.githubusercontent.com/52027965/119978364-84733400-bff4-11eb-8ff5-f71e9907e6ae.png)<br><br>
* 펀딩 : 진행중인 펀딩, 마감임박 펀딩, 펀딩 오픈하기 으로 구성
* 펀딩 상세정보를 통해 이용자가 원하는 펀딩 직접 참여 가능<br><br><br>

### 간편결제
![image](https://user-images.githubusercontent.com/52027965/119978468-a5d42000-bff4-11eb-93c7-55d17ce34618.png)<br><br>
* 간편결제 : QR결제, 송금하기 기능으로 구성
* QR결제 :  QR코드를 이용하여 누구나 쉽게 기부금액 결제 가능
* 결제내역 : 사용자가 앱으로 결제한 내역과 기부한 금액에 대한 확인 가능<br><br><br>


### 간편결제(송금하기)
![image](https://user-images.githubusercontent.com/52027965/119978565-c13f2b00-bff4-11eb-912f-1d18cfb6f51f.png)<br><br>
* 송금하기 : 진행중인 펀딩, 마감임박 펀딩, 펀딩 오픈하기 으로 구성 
* 이용자가 원하는 펀딩 참여 가능 <br><br><br>


### 커뮤니티
![image](https://user-images.githubusercontent.com/52027965/119978669-e469da80-bff4-11eb-9411-b493125d9314.png)<br><br>
* 커뮤니티 : 최신 기부 소식(기부 관련 뉴스), 기부 이야기(서비스 이용자 간 의견 교류) 
                        서비스 사용 가능
* 자유롭게 자신의 기부 소식을 올릴 수 있으며, 유대감 형성 역할 <br><br><br>

### 마이페이지
![image](https://user-images.githubusercontent.com/52027965/119978755-f9466e00-bff4-11eb-856d-84becf7d695e.png)<br><br>
* 마이페이지 : 현재 보유 기부금액, 나의 기부 레벨 확인 가능
* 이용자가 선호하는 기관, 펀딩 기록 확인 가능
* 설정 : 결제 금액 범위, 기부 퍼센트(%) 설정 가능<br><br>


## 3. 역할 분배
* 최정민(본인) : Android Studio 백엔드
* 이해서 : Android Studio 프론트엔드
* 이지나 & 신수영 & 이인경 : 기획, UI/UX <br><br>


## 4. 발표 파일
[일반부문_나비날다.pptx](https://github.com/JMine97/NH_NAVI/files/6560541/_.pptx)
