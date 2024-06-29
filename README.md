# 🏨 sybnb (3rd Team Project)

국비지원 훈련과정 마지막 팀프로젝트입니다.

- 3개 이상의 역할이 명확하게 구분되어지는 사이트
- 사용자 간의 상호작용이 이루어지는 사이트
- 결제, 공유하기, 달력, 주소 검색 등 다양한  API를 활용할 수 있는 사이트

위 3가지 조건에 부합하는 호텔 예약 사이트로 주제로 선정하였습니다.
<br>
<img src="https://img.shields.io/badge/Airbnb-FF5A5F?style=for-the-badge&logo=Airbnb&logoColor=white"> 사이트를 참고하였습니다.
  
<br>

## 🔖 목차
[1. 프로젝트 개요](#--1.-프로젝트-개요)
   - [개발 기간](#-개발-기간)
   - [사용 기술 및 개발 환경](#-사용-기술-및-개발-환경)
   - [팀원 소개](#-팀원-소개)   

[2. 프로그램 구조](#-2.-프로그램-구조)
   - [ER Diagram](#-ER-Diagram)
   - [주요 기능](#-주요-기능)
   - [주요 기능 - Flow Chart](#-주요-기능---Flow-Chart)

[3. 페이지 기능 안내](#-3.-페이지-기능-안내)
   - [주요 기능](#-주요-기능)
   - [세부 기능](#-세부-기능)

[4. 개선사항 및 후기](#-4.-후기-및-개선점)
   - [후기](#-후기)
   - [개선점](#-개선점)

<br><br>

## 1. 프로젝트 개요
### 🗓 개발 기간
* 2024.04.24 ~ 2024.06.05
* 1주차 : 주제선정 및 프로젝트 기획 회의, DB설계, 개발환경 세팅
* 2~3주차 : 개인별 집중 개발 진행 후, 1차 통합 테스트
* 4주차 : 세부기능/추가기능 등 피드백 후 수정 작업 진행
* 5주차 : 2차 통합테스트 및 오류 수정
* 6주차 : 발표 자료, 프레젠테이션  준비 및 최종 시연(6/11)

<br>

### 🖥 사용 기술 및 개발 환경
* OS : <img src="https://img.shields.io/badge/windows 11-0078D4?style=for-the-badge&logo=windows11&logoColor=white">
* Tools : <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white">
* Front-end : <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white"> <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black">
* Back-end : <img src="https://img.shields.io/badge/Java-34567C?style=for-the-badge&logo=Java&logoColor=white"> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=SpringBoot&logoColor=white"> <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=MariaDB&logoColor=white">
* Library : <img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=Chart.js&logoColor=white"> <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=Bootstrap&logoColor=white">

<br>

### 👩‍💻 팀원 소개
* [도경민](https://github.com/mindyhere)
* 박미현🙋‍♀️
* [양미영](https://github.com/didaldud)
* [조연우](https://github.com/yunuyununu)
* [홍재희](https://github.com/jh91019)

![member_final](https://github.com/Miihyunee/sybnb/assets/151993240/dc845325-2485-4777-b7bd-e2aa6b91296f)

<br><br>

## 2. 프로그램 구조
### 🔹 ER Diagram
![erDiagram](https://github.com/Miihyunee/sybnb/assets/151993240/2644f8e8-ccfa-4dab-a204-614edc2108b1)

<br>

### 🔹 주요 기능
![main](https://github.com/Miihyunee/sybnb/assets/151993240/8d57937e-95b8-4e18-83f5-ea1b3d44a594)

<br>

### 🔹 주요 기능 - Flow Chart
 - 회원등록 및 가입승인
![회원등록](https://github.com/Miihyunee/sybnb/assets/151993240/8259152c-b607-42cc-99c3-bcf2b7dc8421)

<br>

 - 호텔등록 및 영업관리
![호텔등록](https://github.com/Miihyunee/sybnb/assets/151993240/5ad47e31-1b52-4cfd-9bde-d23c3d87664a)

<br>

 - 숙박 예약(예약 · 취소 · 변경) 및 예약관리
![숙박](https://github.com/Miihyunee/sybnb/assets/151993240/21308727-2104-4067-ba2b-88bc409e9ee8)

<br>

 - 후기˙평점 관리
![후기](https://github.com/Miihyunee/sybnb/assets/151993240/faada4b5-a3e3-4edd-8f8c-71fba154185b)

<br><br>

## 3. 페이지 기능 안내
#### ☝ 주요 기능
 - 호스트 회원가입
<br>
 : 최초 가입 시 “가입 완료” 상태 
 <br>
 : 호스트 승인요청 시, 첨부파일 등록 필수(프로필/사업자 등록증/ 통장사본) → 승인요청 버튼 활성화
<br>

![호스트회원가입](https://github.com/Miihyunee/sybnb/assets/151993240/d7d6003b-87bf-4e59-940f-e408bdb97ac0)

<br>

 - 호스트 가입 승인
<br>
 : 신규 회원 승인 대기 상태일 때 [가입승인] 버튼 클릭
 <br>
 : 사업자등록증, 통장사본 일치 확인 → 승인 완료
<br>

![호스트 가입승인불가+승인완료 영상](https://github.com/Miihyunee/sybnb/assets/151993240/68951802-ae44-43dd-8c71-ec103e5bf1d2)

<br>

 - 호텔등록 및 영업관리
<br>
 : 기본정보 입력 후 ‘다음’ 클릭 시 편의시설, 객실정보 입력하는 페이지로 이동
<br>
  ※ 객실 정보 등록 시, 싱글룸은 필수 입력
<br>
  ※ 객실 사진은 최대 3장까지 첨부 가능
<br>
 : 작성 중인 내용이 있을 경우 이어서 작성할 것인지 묻는 Alert
<br>
  1) “네” 선택 시, 입력했던 데이터 불러온 후 이어서 작성 가능
<br>
  2) “아니오” 선택 시, 저장되었던 데이터 삭제되고 새로 입력하는 페이지로 이동
<br>

![호텔 등록 승인](https://github.com/Miihyunee/sybnb/assets/151993240/bf6bb725-8e20-4ed5-b025-bbf2d30b05e3)

<br>

 - 예약 확정
![예약확정](https://github.com/Miihyunee/sybnb/assets/151993240/033d05ea-954e-4f3b-ba0b-61aa04c9dad0)

<br>

- 예약변경 승인
![예약변경승인](https://github.com/Miihyunee/sybnb/assets/151993240/c5663561-b0a8-488f-bdaa-d68d39a45fd3)

<br>

- 예약변경 거부
![예약변경거부](https://github.com/Miihyunee/sybnb/assets/151993240/c928e70b-f664-4719-b45a-9451837df57e)

<br>

 - 후기˙평점 관리
<br>
 : 리뷰가 등록되어 있지 않은 지난 여행만 작성 가능
<br>

![후기작성](https://github.com/Miihyunee/sybnb/assets/151993240/f11ed852-881f-403f-aa2b-bf123b91ec85)

<br>

#### ✌ 세부 기능
 - 게스트 회원가입
![게스트회원가입](https://github.com/Miihyunee/sybnb/assets/151993240/76529c35-6dfd-423c-aa7a-e581e0985b82)

<br>

- 게스트 위시 리스트
<br>
: 상세 페이지에 들어갈 때마다 local storage에 호텔 고유번호를 배열로 저장 → 배열을 재생성(Set: 중복 제거)하여 항목을 추가하여 반복문을 사용해 최근 본 순서로 정렬
<br>

![위시리스트](https://github.com/Miihyunee/sybnb/assets/151993240/7f45d40b-b56b-4289-b21e-2afb7e1dccee)

<br>

- 호스트 상세 페이지
![호스트상세페이지](https://github.com/Miihyunee/sybnb/assets/151993240/6e2ae0c5-6f30-4e7b-ac00-a35859e08f9d)

<br>

- 채팅
<br>
: react-simple-chatbot 활용
<br>

![채팅](https://github.com/Miihyunee/sybnb/assets/151993240/11b2e4e4-dac0-4735-bcff-9100070dfa58)

<br>

- 호텔 신규 등록
![호텔신규등록](https://github.com/Miihyunee/sybnb/assets/151993240/1bb335ab-354f-460f-be8e-7d0c085d7857)

<br>

- 호텔 신규 등록(이어서)
![이어서 등록](https://github.com/Miihyunee/sybnb/assets/151993240/824f4ba3-9e15-4a84-ba15-8a8cb40c7df1)

<br>

- 호텔 정보 수정
![호텔정보수정](https://github.com/Miihyunee/sybnb/assets/151993240/045c3acb-fbb5-4f1e-a7e2-a63d7f2c4b09)

<br>

- 호스트 계정
![호스트계정정보](https://github.com/Miihyunee/sybnb/assets/151993240/828619b2-e757-4cd6-bf37-54150f9c1720)

<br><br>

## 4. 후기 및 개선점
### 📝 후기
- 깜박임 현상이 잦아 아쉬움. 후 axios(비동기처리)로 개선 필요
- 관리자 자동로그인 기능 추가
- 후기 작성 후 일정기간이 지나면 수정/삭제가 불가능하도록 개선 필요
- 호스트 가입승인 시 가입정보가 일치하지 않으면 ‘승인요청거부’ 메시지가 전달되도록 개선 필요


<br>

### 🛠 개선점
- Github를 활용하여 원활한 팀 프로젝트를 진행할 수 있었다.
- 안드로이드를 활용한 숙박예약어플, 관리자-호스트 매출/정산 기능 등 기획단계에서 더 많은 아이디어가 나왔었는데 여건 상 시도하거나 최종 구현하지 못한 부분들이 아쉬움으로 남는다.
- 프로젝트 기획과정에서 다양한 테이블 관계형성과 프로시저, 새로운 프론트엔드(React)를 활용할 수 있도록 노력했고 그 결과 많은 공부가 되었다. 
- 팀 프로젝트를 통해 많이 배우고 부족한 부분을 채워 성장할 수 있는 계기가 되었다. 
