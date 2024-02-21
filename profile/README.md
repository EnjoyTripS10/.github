
# EnjoyTrip

본 프로젝트는 삼성 청년 SW 아카데미 1학기 최종 프로젝트 결과물 입니다.

## 참여 인원 (2명)

| 이름 | 역할 | 구현기능 |  |
| --- | --- | --- | --- |
| 김보경 | 팀장 (BackEnd) | 카카오맵 api활용,,,,,주저리 주저리 등 |  |
| 김범수 | 팀원 (FrontEnd) |  |  |

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

## 성과

삼성 청년 SW 아카데미 1학기 프로젝트 우수상 - 삼성전자

## 기술 스택

mysql 8.0

spring boot 2.7.2 / java 11

gradle

node.js + vue3

javascript

Tailwind CSS

## Tool

intellij

visual studio

postman

swagger

github

## API

HTML - Geolocation API

Drag and Drop API

KAKAO Map API

NAVER API

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

```

### FrontEnd

```jsx

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
