
# EnjoyTrip

본 프로젝트는 삼성 청년 SW 아카데미 1학기 최종 프로젝트 결과물 입니다.

## 참여 인원 (2명)

| 이름 | 역할 | 구현기능 |
| --- | --- | --- |
| 김보경 | 팀장 (BackEnd) | RESTful API<br> 카카오 소셜로그인<br> 카카오맵 API 활용<br> 네이버 검색 API<br> 실시간 알림|
| 김범수 | 팀원 (FrontEnd) | 화면 설계 및 구성<br> 비동기 통신 처리<br> 현위치 기반 실시간 정보 제공 기능<br>실시간 알림 |

## 성과

삼성 청년 SW 아카데미 1학기 프로젝트 우수상 - 삼성전자

## 핵심 기능

```
- 여행 계획 플랫폼에 SNS를 더하여 사용자간 여행 기록을 공유 할 수 있는 기능 제공
- 소셜로그인 (카카오)
- 계획 생성
- 수정의 실시간 알림
- 날짜별 세부 장소 일정 조정
- GPS기반 테마별 장소 검색

- 타겟 대상층
- 다른 사람과 함께 일정을 계획하고 싶은 사용자
- 본인의 추천 코스를 공유하고 싶은 사용자
- 나의 위치 주변에 있는 장소를 조회하고 싶은 사용자
```

## 기획배경 / 기획의도

```
사람들은 여행계획을 짜기 위해 함께 가는 사람과 공유하고 싶어 한다. 
enjoytrip에서는 국내의 모든 여행지를 검색할 수 있으며 쉽게 일정에 대한 계획을 짤 수 있도록 도와준다. 
그리고 여행을 다녀와서 여행지에 대한 후기를 사진과 함께 세세한 장소를 태깅해서 게시물을 작성하고 공유할 수 있도록 하였다. 
따라서 여행을 가려는 사람들의 모든 니즈를 최대한 담는 서비스를 만들었다.
```

## 프로젝트 기간

- 2023년 11월 16일  ~ 2023년 11월 24일 (약 2주)
- BackEnd 개발 일정

![Untitled](profile/Untitled.png)

- FrontEnd 개발 일정

![Untitled](profile/Untitled%201.png)


<div align=center><h1>📚 기술 스택</h1></div>

<div align=center> 
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> 
  <img src="https://img.shields.io/badge/spring%20boot-6DB33F?style=for-the-badge&logo=spring%20boot&logoColor=white"> 
  <img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">
  <img src="https://img.shields.io/badge/apache%20tomcat-F8DC75?style=for-the-badge&logo=apache%20tomcat&logoColor=white">
  <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> 
  
  <br>
  <img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white">
  <img src="https://img.shields.io/badge/vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white"> 
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
  <img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white"> 
  
  <br>
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
  <img src="https://img.shields.io/badge/tailwindcss-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">
  
  <br>
  <img src="https://img.shields.io/badge/intellij%20idea-000000?style=for-the-badge&logo=intellij%20idea&logoColor=white">
  <img src="https://img.shields.io/badge/visual%20studio%20code-007ACC?style=for-the-badge&logo=visual%20studio%20code&logoColor=white">
  <img src="https://img.shields.io/badge/postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white">
  <img src="https://img.shields.io/badge/swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=white">
  
  <br>
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <br>
</div>

### code convention

```
4 space(1 tab) 들여쓰기를 사용한다.
함수명 위에 한줄 주석으로 기능을 정의한다.
postman 이용해 parameter 및 return 값을 명시한다.

Naming Conventions
클래스 명은 카멜케이스(CamelCase)로 작성한다.
DB의 테이블, 컬럼명은 대문자로 정의한다.
```

## DB설계

![Untitled](profile/Untitled%202.png)

## 기능 구현 설명

### BackEnd

```jsx
RESTful API
카카오 소셜로그인
카카오맵 API 활용
네이버 검색 API
실시간 알림 (Socket.io)
```

### FrontEnd

```jsx
화면 설계 및 구성
- Vue3와 Javascript(ES6)를 활용하여 컴포넌트 단위로 분리되어있는 화면을 구성
비동기 통신 처리
- Axios, async를 활용하여 비동기 통신 구현
현위치 기반 실시간 정보 제공 기능
- 카카오맵 API, 네이버 검색 API, Geolocation API 3가지의 API를 활용하여 현위치 기반 주변 장소를 검색 후 지도를 통해 정보전달
실시간 알림
- 사용자에게 댓글, 좋아요에 대한 알림을 위해 Socket.io를 이용한 실시간 알림 기능 구

```

## 실행 화면, 기능 설명

1. 시작 페이지
- 서비스의 사용할 수 있는 방법을 시작페이지에 넣어 누구나 사용할 수 있도록 하였다.

![Untitled](profile/Untitled.gif)

1. 메인페이지 
- 첫 페이지에 사용자의 사용을 돕기 위해 모든 기능을 함축해서 볼 수 있도록 간단한 카드를 통해 보여준다.

![Untitled](profile/Untitled%201.gif)

1. 장소에 대한 게시글 작성
- 장소를 검색하여 태그하고 사진과 함께 정보를 입력하여 게시물을 작성할 수 있다.

![Untitled](profile/Untitled%202.gif)

1. 게시물 검색 / 조회 / 댓글 작성

![Untitled](profile/Untitled%203.gif)

1. 계획 작성
- 여행에 대한 계획을 날짜를 선택하여 해당하는 날짜의 장소를 drag & drop으로 일정을 만들 수 있다.

![Untitled](profile/Untitled%204.gif)

1. 내위치 주변 장소 검색
- 주변에 있는 맛집/카페/관광지/숙박 카테고리 별로 장소를 조회할 수 있다.
- 좌측의 장소 위에 마우스가 올라가면 지도에 있는 마커가 포커싱이 되어 가시성을 높혔다.

![Untitled](profile/Untitled%205.gif)

1. 실시간 알림
- **Web Socket**을 통해 사용자와 관련된 정보에 대한 알림을 실시간으로 준다.

![Untitled](profile/Untitled%206.gif)
