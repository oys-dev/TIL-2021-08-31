# TIL-2021-08-31
## 3rd 프론트엔드 class 
### 메타데이터 요소
메타데이터: 데이터를 위한 데이터

### - title
문서 제목 요소
<title>제목</title>

### - meta
빈 요소임
< meta > 요소는 < base >, < link >, < script >, < style >, < title >과 같은 다른 메타관련 요소로 나타낼 수 없는 메타데이터를 나타냄
name: 이름, content: 값

#### 표준 메타데이터 이름 정의

application-name: 웹 페이지에서 구동 중인 애플리케이션의 이름

author: 문서 저작자

description: 페이지에 대한 짧고 정확한 요약. Firefox, Opera 등 여러 브라우저는 즐겨찾기 페이지의 기본 설명 값으로 사용

generator: 페이지를 생성한 소프트웨어의 식별자

keywords: 페이지의 콘텐츠와 관련된, 쉼표로 구분한 키워드 목록

referrer

viewport: 전체 브라우저에서 웹 페이지를 볼 수있는 영역

뷰포트 content는 일단 알아만두자

*< meta charset="UTF-8" > 한글 사용 가능*

### < link >: 현재 문서와 외부 리소스의 관계를 명시
ex) < link href="style/main.css" rel="stylesheet" >
< link rel="icon" href="favicon.ico" >

### MIME type: 
파일 경로를 해석하지 못 할 경우 타입을 명시

### < style >: 스타일 정보 요소
외부파일로 가져오는것을 권장하긴 함

### < script >: 스크립트 요소
데이터와 실행 가능한 코드를 문서에 포함할 때 사용하며 보통 JavaScript 코드와 함께 씀
