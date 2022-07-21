# [TOY] 리액트 다루는 기술의 블로그 만들기

배울점 : 회원 가입, 로그인, 인증 구현, 서버(BackEnd)와 클라이언트(FrontEnd)간 CRUD패턴

서버는 DB의 데이터를 가져와서 Rest Api형태로 클라이언트에게 전달

## Dir Structure

### backend

- src
  - api : rest API 설정하기
    - auth : 로그인
    - posts: 포스팅
  - lib : library
  - models : DB 모델 설정

### frontend

- src
  - components
    - auth : 로그인 페이지
    - common : Reuse Components
  - lib
    - styles : CSS Color palette
  - pages : react router page
  - modules : redux
