# ⭐️GodLife
Team.I/O - GodLife 프로젝트


# 🔖프로젝트 소개 및 선정 이유
* 저희 GodLife 목표달성 플랫폼 프로젝트는 자아실현과 성취감을 중요시하고, 자기 관리 욕구가 높은 MZ세대의 라이프스타일인 ‘갓생살기’를 타겟으로
일상을 공유하고 SNS를 통해 무엇인가를 인증하려는 욕구가 강한 MZ세대에게 더 나은 삶을 위한 건강한 습관과 목표를 만들 수 있도록 해당 서비스를 기획했습니다.

* 저희 서비스는 높은 동기부여를 위하여 챌린지를 생성 및 참가하여 스스로 포인트, 즉 돈을 걸어 미션을 수행하고 인증하며 목표를 달성할 수 있도록 도와주는 서비스 입니다.

* 같은 목표를 가진 이들끼리 커뮤니티에 인증샷을 올려 경쟁심과 성취욕구를 자극하기도 하고 응원과 격려를 주고 받기도 합니다.

* 목표 100프로 달성자 부터 각 달성 퍼센트 에따른 보상을 획득 합니다.


# 개발기간 및 인원
* 개발기간 ⏰ : 2022 / 05 / 02 ~ 2022 / 07 / 01 (총 9주)
* 개발인원    : 풀스택 엔지니어 5명 
    * Project Master👨🏻‍💻 : 유병문
    * Project Member👨‍👨‍👧‍👦 : 김호 황석현 이수아 이해동

# 개발방식
* 애자일 개발 프로세스와 그에 따른 스크럼 방법론에 의거해 일주일 단위의 스프린트를 기준으로 삼았습니다.
* 매 스프린트 시작마다 Planning Meeting을, 매일 아침 11시에는 Daily Meeting을 진행하며 현재 진행상황과 앞으로의 진행 예정 사항을 최신화 하고 일정을 조율했습니다.
* 매일 저녁 8시에는 각 팀원의 이슈를 체크하고, 스케쥴에 따른 프로젝트 방향성을 확립하였습니다.
* 모든 회의는 회의록을 작성하여 소통에 있어 혼선이 생기는 것을 최소화했습니다.


# 데모 영상 🎥
https://drive.google.com/file/d/1ahwCnU_mzMbUzneLaurN7cVvDUnDIXSp/view?usp=sharing


# 적용 기술 및 구현 기능 🛠

## 적용기술

## 공통사항
Git & Github, Slack, Trello, Google SpreadSheet, Google Document

Front-End
HTML, CSS, JavaScript, JSP, JQuery, AJAX, JSON, BootStrap, GSAP, Slick.js, Font AWESOME

Back-End
JAVA, Spring, MyBatis, Maven, Unit, GSON, Oracle, Oracle Developer, XML

API
CoolSMS, Kakao Open API, Import

Tool
Eclipse, StarUML, OvenAPP


## 공통 역할
* 프로젝트 분석(현업 요구사항 정의서, UseCase 유형정의, 요구사항 추적표, UseCase 정의서, UseCase Diagram, Class Diagram, VOPC, 화면정의서)
* 프로젝트 설계(설계 표준, VOPC, 화면정의서)
* Data 제작∙관리 및 최신화


## 개인별 역할 ❤️

### 유병문
* 프로젝트 스케쥴 작성
* ERD 다이어그램 작성
* 포인트 관리( 회원 보유포인트, 포인트 현금 결제, 상품 구매, 챌린지 참가비 결제, 챌린지 포인트 보상 환급, 이벤트 참가비용 결제, 이벤트 보상 환급, 포인트 이용내역) 구현
* 기부하기 구현
* 회원 관리( Top Nav 회원정보, 신고 카운트 증가 및 레드카드 발급, 레드카드 쿠폰 사용, 타회원 상세페이지 배지목록 및 챌린지 목록) 구현
* 통합 관리( 매일 출석하기 이벤트 ) 구현
* 챌린지 관리(메인화면 베스트 인증이미지 목록) 구현
* Import API를 사용하여 카카오 페이 결제, 페이코 카드 결제 구현
* CoolSMS를 사용하여 상품권 구매정보 문자메세지 전송 구현
* GodLife 프로젝트 최종 디버깅 작업

### 김호
* 상품 관리( 포인트/상품권/쿠폰 상품 등록, 포인트/상품권/쿠폰 상품 수정, 포인트/상품권/쿠폰 상품 삭제, 포인트/상품권/쿠폰 상품 상세조회) 구현
* 배지 관리( 배지 등록, 배지 수정, 배지 삭제, 배지 상세조회) 구현
* File upload 를 통한 이미지 등록 구현
* 회원가입, 친구등록, 챌린지 달성률 100프로, 챌린지 종료 후 카테고리에 맞는 배지 활동 횟수량 증가 구현
* 마이배지 목록 조회 구현
* 배지 등급에 따른 디스플레이 변화 구현
* 프로젝트 최종 문서화 작성
* 관리자 UI 구현

### 황석현
* Oracle Developer 구현
* 통합관리(공지사항 등록, 공지사항 삭제, 공지사항 조회,FAQ 등록,FAQ 수정,FAQ 삭제, FAQ 조회, 룰렛 이벤트) 구현
* 메인화면 이벤트 배너 기능 구현

### 이수아
* Maven을 사용한 프로젝트 생성
* 회원관리(일반 회원가입, 소셜 회원가입, 로그인, 소셜로그인, 회원 상세조회, 회원정보수정, 쪽지 보내기, 쪽지읽기, 쪽지 신고, 쪽지 목록, 친구/블랙리스트 목록, 친구/블랙리스트 등록, 친구/블랙리스트 삭제, 관리자용 전체회원목록, 관리자용 신고목록) 구현
* CoolSMS를 통한 회원가입 시 본인인증 구현
* File upload를 통한 이미지 등록 구현
* Kakao Open API를 통한 카카오 소셜로그인 구현
* Top Nav 구현
* 마이페이지 사이드 바 구현

### 이해동
* Oracle Developer 최신화
* 챌린지 관리(챌린지 등록, 챌린지 조회, 챌린지 참여유저 목록, 챌린지 인증이미지 등록, 인증이미지 게시판 좋아요/싫어요, 인증이미지 게시판 댓글) 구현
* File upload를 통한 이미지 등록 구현
* 챌린지 관리(챌린지 찜하기, 챌린지 공유, 참여한 챌린지 목록) 구현
* 블랙리스트 상대가 등록한 챌린지,인증이미지 게시글 은 조회가 되지 않도록 구현
* Kakao Open ApI를 통한 카카오 공유하기 구현
* 인증이미지 게시판 무한 스크롤 구현
* Resources 관리 
* 메인화면 베스트 챌린지 목록, 신규 챌린지 목록, 친구가 등록한 챌린지 목록, 관심사에 따른 추천 챌린지 목록 구현

## 구현기능 📝

### 메인페이지🏠
* 이벤트 배너 스크롤 구현
    * 메인 배너 를 포함한 두개의 이벤트 배너
* 베스트 챌린지 목록 구현
    * 아직 시작 전인 챌린지를 상대로 참여자가 많은 순으로 디스플레이 되도록 구현
* 신규 챌린지 목록 구현
    * 아직 시작 전인 챌린지를 상대로 챌린지 생성날짜가 빠른 순으로 디스플레이 되도록 구현
* 추천 챌린지 목록 구현
    * 아직 시작 전인 챌린지를 상대로 회원이 등록한 관심사를 기준으로 챌린지 목록이 디스플레이 되도록 구현
* 친구 챌린지 목록 구현
    * 아직 시작 전인 챌린지를 상대로 회원의 친구가 등록한 챌린지 목록이 디스플레이 되도록 구현
* 베스트 인증이미지 목록 구현
    * 인증이미지 게시글에 좋아요가 많은 순으로 디스플레이 되도록 구현

### Top NAV바🧩
* 챌린지 관심사, 공지사항, 이벤트, (회원가입, 로그인), (회원간략정보, 마이페이지 이동, 포인트상품 구매 , 상품권상품 구매, 쿠폰상품 구매, 기부하기),관리자 UI로 구성됨
    * 로그인 상태 비회원 / 회원 / 관리자에 따라 UI 변화가 이루어진다.

### 마이페이지😼
* 본인 상세정보
    * 로그인한 회원의 정보를 조회, 수정 할 수 있습니다.
    * 수정 시에는 본인 인증이 필요합니다.
    * 서비스 활동을 하며 타회원으로 부터 받은 신고개수와 레드카드 개수, 레드카드소멸 쿠폰 개수가 보여집니다.
        * 신고개수는 5개가 된다면 자동으로 초기화 되며 레드카드가 증가합니다.
        * 레드카드를 3장 보유했을 시 서비스 활동이 제한됩니다.
        * 레드카드 소멸쿠폰을 통해 레드카드를 소멸할 수 있으며, 쿠폰은 쿠폰구매 화면에서 포인트로 구매가 가능합니다.
* 포인트 이용내역 조회
    * 포인트 전체 이용내역, 포인트 충전내역, 상품권 구매내역, 기부내역 으로 세분화 됩니다.
        * 포인트 전체 이용내역은 회원이 서비스를 이용하며 발생한 포인트 충전/소비, 금액, 이용처, 날짜로 조회됩니다.
        * 포인트 충전내역은 현금으로 포인트 상품을 구매한 내역이며 포인트 이용유형, 금액, 구매한 상품, 날짜로 조회됩니다.
        * 상품권 구매내역은 포인트로 구매한 상품권에 대한 정보 내역으로, 상품명, 상품권 고유번호,구매날짜, SMS문자 전송 기능이 있습니다.
        * 기부내역은 포인트로 기부한 내역으로 기부처, 기부금액, 기부날짜로 조회됩니다.
        * 모든 내역은 검색 조건으로 세분화된 검색을 할 수 있습니다.

* 보유 배지
    * 배지는 활동 배지, 관심사 배지로나뉘어지며 배지 활동량 증가에 따라 등급이 오릅니다.
        * 활동 배지 : 친구배지(친구등록시), 목표100프로 달성, 레벨배지 등 각 배지에 맞는 조건 달성 시 활동량 증가
        * 관심사 배지 : 관심사(운동,취미,예술,식습관,생활)에 맞는 챌린지를 참여하여 보상 받을 시 활동량 증가 
    * 배지 전체 보기 버튼을 통해 모든 배지의 정보 및 배지서비스의 규칙을 확인 할 수 있습니다.
        * 관리자는 배지 전체 보기 내에서 배지 등록, 수정, 삭제 가 가능합니다.

* 친구/블랙리스트 목록
    * 등록한 친구 또는 블랙리스트를 조회 할 수 있으며 쪽지를 보낼수도 있습니다.
    * 체크 박스를 통해 친구/블랙리스트를 삭제할 수 있습니다.
        * 친구가 등록된다면 친구가 등록한 챌린지를 메인페이지에서 확인 할 수 있습니다.
        * 블랙리스트로 등록된다면 해당 회원의 등록된 챌린지,인증이미지는 어디에서도 조회가 불가능 합니다. 

* 참여한/ 찜한 챌린지 목록
    * 본인이 참여한 / 찜한 챌린지 목록을 조회합니다. 
        * 참여한 챌린지 중 시작전 챌린지는 나가기 기능, 공유하기 기능이 있습니다.
        * 진행중인 챌린지는 목표달성을 위한 인증사진 등록 기능이 있습니다.
        * 종료된 챌린지는 목표달성률에 따른 보상포인트 받기 기능이 있습니다.
        * 찜한 챌린지는 시작전에만 보여지며 진행중인 상태가 된다면 사라집니다.

* 쪽지 보내기, 받은 쪽지함
    * 회원,관리자에게 쪽지를 보낼 수 있습니다.
    * 블랙리스트로 등록된 경우, 서로 쪽지를 주고받을 수 없습니다. 
    * 받은 쪽지함에서 해당 회원에게 답장을 보낼 수 있으며 신고또한 가능합니다.

### 상품 구매🎁
* 포인트상품 구매, 상품권상품 구매, 쿠폰상품 구매가있습니다.
    * 포인트상품 구매는 현금결제를 통해 구매가 가능하며 결제 방식으로는 계좌이체, 페이코 카드결제, 카카오페이가 있습니다.
    * 상품권상품 구매는 포인트를 통해 구매가 가능합니다.
        * 상품권 구매 시 영문+숫자로 조합된 랜덤번호가 고유번호로 저장됩니다.
    * 쿠폰상품 구매는 포인트를 통해 구매가 가능합니다.

### 기부하기🍀
* 기부하기 화면에는 지금껏 기부했던 회원들 중 상위 3명의 랭킹이 보여집니다.
* 기부하기는 포인트를 통해 기부가 가능합니다.

### 이벤트🤹🏻‍♂️
* 매일 출석하기 이벤트와 룰렛 이벤트가 있습니다.
* 매일 출석하기 이벤트는 회원만 하루에 한번 참여가 가능하며 월이 바뀐다면 초기화 됩니다.
    * 매월 14,28번째 출석은 보다 좋은 보상을 받을 수 있습니다.
* 룰렛 이벤트는 회원만 하루에 한번 참여가 가능합니다
    * 관리자가 지정한 확률에 따른 보상이 나뉘어져 있습니다.
    * 룰렛이벤트 참여시 일정 포인트를 지불해야 합니다.

### 챌린지 생성🎯
* 회원은 챌린지를 생성할 수 있습니다.
* 챌린지 생성시 타이틀, 입장 포인트, 썸네일, 관심사, 시작날짜, 종료날짜, 인증주기, 챌린지 설명, 챌린지 규칙을 작성합니다.
    * 관심사는 추천 챌린지 목록에 이용됩니다.
    * 지정한 시작날짜, 종료날짜, 인증주기(월화수목금토일 다중 선택가능)에 맞추어 챌린지 인증이미지 등록 개수와 달성률이 조정됩니다.
* 최종 등록시 지정한 정보들을 한번더 확인하여 수정 및 최종등록을 할 수 있습니다.

### 챌린지 상세페이지❤️
* 챌린지 상세페이지는 시작전, 진행중, 종료된 상태로 나뉩니다.
    * 챌린지 시작전 메인화면 또는 챌린지 검색에 조회가 되며, 다른 회원들은 입장포인트를 지불하고 참여가 가능합니다. 또한 친구에게 카카오 공유도 할 수 있습니다.
    * 챌린지 진행중 참여한 회원들은 인증이미지 등록 가능 날짜에 맞춰 조건에 맞는 인증이미지를 등록할 수 있으며 그에따른 달성률이 증가합니다
        * 호스트와 관리자는 타회원이 등록한 인증이미지가 불건전 하거나 챌린지 조건에 맞지않다면 삭제를 할 수있습니다.
        * 인증이미지가 삭제 된다면 달성률에 지장이 있으며 인증이미지 등록 가능날짜가 지난다면 재등록 할 수 없습니다.
    * 챌린지 종료 시 회원인 자신의 목표달성률에 따른 보상을 지급받을 수 있습니다.

### 공지사항 및 FAQ❓
* 관리자가 등록한 공지사항과 FAQ를 비회원을 포함하여 모든 회원이 조회가 가능합니다.


# 분석 단계 DataBase Model
 <img width="1248" alt="스크린샷 2022-07-07 오후 3 33 28" src="https://user-images.githubusercontent.com/98165704/177708017-e6747854-9711-4407-91b0-e951aea0438a.png">


# 설계 단계 DataBase Model
<img width="1285" alt="스크린샷 2022-07-07 오후 3 34 24" src="https://user-images.githubusercontent.com/98165704/177708160-46e71af8-5b14-4b57-bc29-bc3f46916a23.png">

<hr/>

# 본인 구현 파트 - GodLife

## 1. 상품 관리 (관리자 모드)  
(포인트, 상품권, 쿠폰 동일 기능 구현)

### 1) 상품 전체 목록
* 페이지 구성(포인트 상품권)
* 해당 웹싸이트는 포인트를 구매해서 챌린지에 참여 가능
  * [포인트 필요처]
    * 챌린지 참여 (최소 1000 포인트 필요)
    * 상품권과 쿠폰 구입
    * 룰렛 이벤트 참여 (최소 1000 포인트 필요)
  * `포인트 = 해당 웹사이트 재화`
![이미지1](https://postfiles.pstatic.net/MjAyMzAxMTdfNjgg/MDAxNjczOTMxOTgzNjc1.cxM7Dr4qzzAnVYnya0042HsrHStosATP8-eYylifN3sg.XAWe8vD3FShlR7Bn4UgUPCuTpNCVaJtmFaYzwJgrFZ0g.PNG.kimhoyam/image.png?type=w773)

<hr/>

* 해당 내용 간략 상품 정보를 보기 위해서 동그란 버튼 클릭 시, Ajax로 아래의 간략 정보 처리  
(포인트, 상품권, 쿠폰 동일)

![이미지2](https://postfiles.pstatic.net/MjAyMzAxMTdfMTE0/MDAxNjczOTMyOTQwMzA0.ZTvVUSg3EvHSTIiuiapu1-HV_fqyLUTNlOzg28L30y8g.TMYgjEv7CeDvvFtwIBGC_I1-pCJ5E3G56kFhs7jFZtYg.PNG.kimhoyam/image.png?type=w773)

<hr/>

* 페이지 구성 (상품권)
* 해당 웹싸이트에서는 상품권을 포인트로 구매 가능
* 상품권을 해당 웹싸이트 재화인 포인트로 구매하여, 현실에서 사용할 수 있는 상품권으로 구매 후 사용 가능

![이미지3](https://postfiles.pstatic.net/MjAyMzAxMTdfMTMz/MDAxNjczOTMzNDU5MzEy.770UDsEiQZnVg5AziJ1A-s68WWyXwQmUfWH2g5zssHcg.NZohXZi1PPkuOvIXK4ob9g4tUhnXQ9iBCMB9ZO_pFMgg.PNG.kimhoyam/image.png?type=w773)

<hr/>

* 페이지 구성 (쿠폰 상품)
* 해당 웹싸이트의 재화가 되는 포인트로 레드 카드 소멸권 및 인증 사진 대처 쿠폰 구매

![이미지4](https://postfiles.pstatic.net/MjAyMzAxMTdfMTk4/MDAxNjczOTMzNTcyNTUw.SVJj02TQV0ks3CwOEIIySzKaNZ6js0c1GGqmLZ1kwQ8g.dPF6uNNOPoxXsqBjsRngSL4qa1nMRKF0oD1t2o--QJ4g.PNG.kimhoyam/image.png?type=w773)

<hr/>

### 2) 추가 상품 등록 (포인트, 상품권, 쿠폰 동일)

* 상단의 신규 상품 등록 버튼을 클릭

![이미지5](https://postfiles.pstatic.net/MjAyMzAxMTdfMTYg/MDAxNjczOTM0MTIzOTg0.jxXm3XiVc8qKrBpb1VwzE4CIFhXSGjtcCoVhDz0ud3kg.b0cOqYTFcjyvQxgRuQhKnUJSciBri2U4uZJ13ewnMaUg.PNG.kimhoyam/image.png?type=w773)

<hr/>

* 신규 포인트 상품 등록 화면

![이미지6](https://postfiles.pstatic.net/MjAyMzAxMTdfOTgg/MDAxNjczOTMyMTAxNzQ5.Fbr8iIfmT-bc0o75FDkn2litGQVezAH0YWudh4jv8Vsg.kg2LiBwpv2jXxb_vpXCV3Ke9k32XJZDetQuWckniSJIg.PNG.kimhoyam/image.png?type=w773)

<hr/>

* image upload 화면

![이미지7](https://postfiles.pstatic.net/MjAyMzAxMTdfMTQw/MDAxNjczOTMyMTY3OTU3.u_3YKLR2zoRL-Y_eUmnLvYpl3r8-ZiGM6igEwOb3qw0g.3Zn9d3Y-6Zr9MK-8-MuSTjJ9tY4CoJtfL0on_g6y3T4g.PNG.kimhoyam/image.png?type=w773)

<hr/>

* 상품 등록 완료 버튼 클릭

![이미지8](https://postfiles.pstatic.net/MjAyMzAxMTdfMTEz/MDAxNjczOTMyNjE4NDgw.mgbUt9fR8EZe3nur6maLmcjdGIJPP8Zl-A0twHAufOsg.VeeQoxCPZFHaq5OFjP6zZLosdnOnD7dwtsyQQPfeNgsg.PNG.kimhoyam/image.png?type=w773)

<hr/>

* 상품 추가된 화면

![이미지9](https://postfiles.pstatic.net/MjAyMzAxMTdfODIg/MDAxNjczOTMyNjQyOTc0.5J-g5K7hrlsNGpsjDt7vRxviDUVI5axWLLBYsvhJJ3cg.RmoKzHKydeeXnbFdYpyBFCjq9h-8IUl5Ge9Aq5KgVEUg.PNG.kimhoyam/image.png?type=w773)

<hr/>

### 3) 상품 상세 정보 화면 (포인트, 상품권, 쿠폰 동일)

* 관리자 일때는 이미지를 클릭 후, 상세 정보 창으로 넘어온다

* 유저 일때는 이미지 클릭시, 아무 일 없음 (이미지 상단 버튼으로만 상품 상세 정보 볼 수 있음)

![이미지10](https://postfiles.pstatic.net/MjAyMzAxMTdfMjUg/MDAxNjczOTMyNzAzNDQ1.0hTynJ-U7I56hxdBBpMbeJvjVmrlu7xr8Og5efJNVM4g.vKcrmqhto0q-CPgLUwgFcOB-Ut3BZ61sEZVVu5wNqg4g.PNG.kimhoyam/image.png?type=w773)

<hr/>

### 4) 수정 및 삭제 버튼 화면

* 상세 정보 창에서, 수정 버튼을 클릭 시 화면
* 수정 및 삭제 가능

![이미지11](https://postfiles.pstatic.net/MjAyMzAxMTdfMTA2/MDAxNjczOTMyNzUwODcy.KcL1IanGEWOODJ9dRmB8z_Fy1sKS-1Repip-xB17XOcg.TgjTAtTnF0RUjmFReeG40rvqgr-6G5QSVKwzIBu1IFsg.PNG.kimhoyam/image.png?type=w773)

<hr/>

* 삭제 버튼으로 상품 삭제

![이미지12](https://postfiles.pstatic.net/MjAyMzAxMTdfMjk3/MDAxNjczOTMyNzc1ODY2.SDL6zfebgnWilZAxqs3zCHXoSi-uBsh41JO94FInjIwg.FUAcaI-M9m0hy63x-_M8-1rOdGfe-lZsDAXUHQa9b3gg.PNG.kimhoyam/image.png?type=w773)

<hr/>

## 2. 상품 조회 (유저 모드)
### (포인트, 상품권, 쿠폰)    
  
### 1) 포인트 상품 조회 페이지

* ajax 이용, 상품 정보 및 결제 방식 구현
* 결제 방식을 클릭 후, buy 버튼 클릭 시 구매

![이미지13](https://postfiles.pstatic.net/MjAyMzAxMTdfMjgw/MDAxNjczOTM1NDE1NTY0.kkZ9CUOqTWmnr99IquMDgTdkdhARASb3rvNtdPAH5Ckg.U9SAnndyJ22gXrcUHLdC7zw15fNTEoPgagFyzo2ScwEg.PNG.kimhoyam/image.png?type=w773)

<hr/>

### 2) 상품권 조회 페이지  
(동일 내용)

![이미지14](https://postfiles.pstatic.net/MjAyMzAxMTdfNzMg/MDAxNjczOTM1NDkzNjkw.U8kV7qbQYsdn4C0hFy6-pmmHA087881nld0friai_BMg.PqkDkZIJ98TemCcYE7S4Cm_FVGdHPm4k2sXRo4nvlH0g.PNG.kimhoyam/image.png?type=w773)

<hr/>

### 3) 쿠폰 조회 페이지  
(동일 내용)

![이미지15](https://postfiles.pstatic.net/MjAyMzAxMTdfODkg/MDAxNjczOTM1NTU1MTUx.p1sAFyNijGUqBfsjvD7Ukz9UFbLFGMLmA67yK0Oj4TQg.c41lNkbBSqOVwyZLbZdE99t0hgcBjfoavCPTKd3fWuAg.PNG.kimhoyam/image.png?type=w773)

<hr/>

## 2. 전체 배지 목록 (관리자 모드)
### 1) 배지 전체 목록

* 해당 웹싸이트에서 배지의 역할은 수집욕구를 불러 일으켜 유저들이 챌린지 싸이트를 가입, 참여 및 참여율에 따라 뱃지를 얻고 업그레이드를 할 수 있도록 했다

![이미지16](https://postfiles.pstatic.net/MjAyMzAxMTdfMjAx/MDAxNjczOTM1NzIxNTYx.7PR2ZMMv9SzkAUDa8cmtG0JQ14TOzsa_RLaGsY18yswg.ru1GF2qpNNwKiLTr9qYUoGhZwWldsWOEJXLAs1Sd4IMg.PNG.kimhoyam/image.png?type=w773)

<hr/>

### 2) 배지 등급 변화 구현

* 등급에 따른 변화
* 처음 배지를 얻게되면 Bronze레벨의 테두리부터 Gold Badge까지 변활 수 있게 구현

![이미지17](https://postfiles.pstatic.net/MjAyMzAxMTdfMTcz/MDAxNjczOTM1OTg4ODU1.3hMUxZCicCOQodLb55EO7PnDJRcEUWG36GtwqhctmXsg.ZfLv8cLanj0GZfJy8SubB0yCOjiVxch1LVt7vUage2gg.PNG.kimhoyam/image.png?type=w773)

<hr/>

### 3) 추가 배지 기능 구현
* 우측 상단의 버튼 클릭

![이미지18](https://postfiles.pstatic.net/MjAyMzAxMTdfMTY1/MDAxNjczOTM2MTkyNTk5.4jp4wYTfFbOnWWMI-i8E_JMqXiUUrr50cv-zftNz0eEg.leEoNcdTPUg2K4OsKJj-NkScHFTxHdxhtXyBpqPvH6Mg.PNG.kimhoyam/image.png?type=w773)

<hr/>

* 하기와 같이 신규 배지 등록이 가능

![이미지19](https://postfiles.pstatic.net/MjAyMzAxMTdfMTkg/MDAxNjczOTM2MjEyNjAw.ijmvf5_1zlHgz32AMqDN262Y0w3lWBEScblJVJ5rZ8kg.d0T9y6TiTb_Ga2vAzv3rIf6XAzKYChnyEPFry38jONcg.PNG.kimhoyam/image.png?type=w773)

<hr/>

* 첫번째 : 활동 배지인지 관심사 배지인지를 구분 해준다
* 두번째 : 배지명 입력
* 세번째 : 배지 상세 정보 입력
* 네번째 : 배지 이미지 등록
* 다섯번째 : 등록완료 버튼 클릭

![이미지20](https://postfiles.pstatic.net/MjAyMzAxMTdfMTQg/MDAxNjczOTM2Mjg2ODAx.e-uxqrwNjbxqLRUvRhe4ET9bj0BZ1DlLFZltEDht1gYg.bXdccBtYFVJu54n0OIJ5oAR2MvFG-lgTfn1dMA32Coog.PNG.kimhoyam/image.png?type=w773)

<hr/>

* 추가된 배지 화면

![이미지21](https://postfiles.pstatic.net/MjAyMzAxMTdfMjkx/MDAxNjczOTM2NDY4Mzg3.CL1ANEG39MSiPvuZ0zQ1cDwDa4pUd54UwQF-1xx1NLIg.PEpWS2QIZpLfuK1ZiVbls4aFnHX7-JncZCXCwF89ev0g.PNG.kimhoyam/image.png?type=w773)

<hr/>

### 4) 배지 상세 정보
* 관리자 모드에서는 이미지를 클릭 하면 상세 정보를 볼 수 있다

![이미지22](https://postfiles.pstatic.net/MjAyMzAxMTdfMTI5/MDAxNjczOTM2NTMwNDQy.7A7aiirWnmAAVypPINPh3iCeUvtGJ0AE41P7MvsDjXIg.U35vYWNRKrDwJIZamGrYd_zWs0-sjoYhf7Q_fHCuqiUg.PNG.kimhoyam/image.png?type=w773)

<hr/>

### 5) 배지 수정 및 삭제

* 상세 정보에서 수정하기 버튼을 클릭
* 수정 할 내용을 작성 후, 수정완료를 클릭 하거나
* 해당 배지를 삭제 할 수 있다 

![이미지23](https://postfiles.pstatic.net/MjAyMzAxMTdfMjc5/MDAxNjczOTM2NTgzMDAx.DawROZV1LZkaisUUy3C5xBec24trd3Ro7yM2Hw1fZBEg.oOg7uJBvO30bW4zM9YqZOEkcFUicwwY_KCIFxcjyd4Mg.PNG.kimhoyam/image.png?type=w773)

<hr/>

* 수정 완료된 화면

![이미지24](https://postfiles.pstatic.net/MjAyMzAxMTdfMjYg/MDAxNjczOTM2NzI2OTg4.9JquHHGXeZ7CmAq5CcUVbP2YM7fS8oLdtlcJtMKMnqog.1HbJ299IDWNI8g8qHnTE4tFUgoYDHYIThvygtZetoUgg.PNG.kimhoyam/image.png?type=w773)

<hr/>

* 배지 삭제 화면

![이미지25](https://postfiles.pstatic.net/MjAyMzAxMTdfMjc5/MDAxNjczOTM2NzU2NTA5.PG9Heyj97Dik6jV3_P94ZjI0HjZy2PZI-HhGoTBk4N4g.BbK8LAqlnmfzoiJWmR82HWh7TjPMOAXMfiE7bC6lzy8g.PNG.kimhoyam/image.png?type=w773)

<hr/>

### 6) 배지 등급 별 변화
* 브론즈, 실버, 골드

![이미지26](https://postfiles.pstatic.net/MjAyMzAxMTdfMjIy/MDAxNjczOTM3MTcwMzI2.-U5CVPjFwXsqnIZZqc7x8qtp9YE0sBvc2H37-oM8e6Yg.MN7mlVK2qJlGYO_HBFFQHIuWdnG0gYylh7iaIy85idog.PNG.kimhoyam/image.png?type=w773)

<hr/>

## 3. 마이 배지 전체 조회 (유저 모드)

### 1) 마이 페이지 -> 개인정보 조회 -> 보유 배지 클릭

![이미지27](https://postfiles.pstatic.net/MjAyMzAxMTdfOTEg/MDAxNjczOTM3Mzk0MzA5._JJZ_ntKeLYjftA7fPIS4V2Ox0KPQYdMZV4nZJTz9Fsg.po-9SgCNvi8_G1qDNwbwGZRpC_g_OilMbUZ2pMVN3bEg.PNG.kimhoyam/image.png?type=w773)

<hr/>

* 보유 배지 화면
* 활동 배지와 관심사 배지가 구분되어 있음
* 현재 자신이 획득한 배지만 나옴

![이미지28](https://postfiles.pstatic.net/MjAyMzAxMTdfMjcx/MDAxNjczOTM4NDUzMDAx.DGA2s2fK-lL_11ashHcXDM1TFNczDpLcawNZtGnmnzgg.oKlO4JxEmyZfw9hdKw_Ym-JvIDSennc4AjlQi-EWzxcg.PNG.kimhoyam/image.png?type=w773)

<hr/>

* 버튼 클릭 시, 부트스트랩의 collapse 
기능으로 아래와 같이 배지에 대한 설명이 나옴

![이미지29](https://postfiles.pstatic.net/MjAyMzAxMTdfMTAw/MDAxNjczOTM4NTAyOTE5.02QoeIJXR7BVuE81tu9OucozgU4MBTTlE3mG_D5O_DUg.KsRqFbCTa2sAnyFRo0kQCVB9BirWEFxvTbbC2_kJTDEg.PNG.kimhoyam/image.png?type=w773)

<hr/>

* 모든 배지를 조회 하고 싶다면
* 배지 전체 목록 상세 조회 가기 클릭

![이미지30](https://postfiles.pstatic.net/MjAyMzAxMTdfMTk0/MDAxNjczOTM4NjM5ODA2.O_VWftMSWFOTR924_i-R4G_ZOE3zmKBtugaNCuEn55Mg.F6zbH2CQYKaXZfiN-hbdXZayQRYEF_MHl1r4YZgs6ogg.PNG.kimhoyam/image.png?type=w773)

<hr/>

* modal 기능을 이용해서 모든 배지의 내용과 등급별 테두리를 볼 수 있음

![이미지31](https://postfiles.pstatic.net/MjAyMzAxMTdfODgg/MDAxNjczOTM4NjU4MTgz.IINqXD-k1MqUuLxKq-v1L_8drpGEaZQhauwMKpa1BGgg.S0BkgsDnR5ctOdki2mAmPxwUWw7Ud1ZwJW40-0OircMg.PNG.kimhoyam/image.png?type=w773)

<hr/>

* modal창의 배지 클릭 시, 아래에 Ajax로 간단한 설명을 볼 수 있음

* modal창으로 뜨는 화면은 관리자 모드의 창을 재활용해서 유저일때와는 다른 기능들이 작동되게 했음
  * 예>
    * [관리자 모드]
      * 이미지 클릭 시, 상세 정보 창
    * [유저 모드]
      * 이미지 클릭 시, ajax로 아래에 간단한 설명

![이미지32](https://postfiles.pstatic.net/MjAyMzAxMTdfMjkz/MDAxNjczOTM4NzAzNzY3.vq6fp3WLTcMWhPUbDphCMep2biu4k6zNM0KEkGaX-Iwg.G8QX97xt4ev6_i_Mq3F6CSj3sY1GDgCaDGNAfB6TDWIg.PNG.kimhoyam/image.png?type=w773)
