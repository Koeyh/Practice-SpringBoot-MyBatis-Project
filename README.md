# Practice-SpringBoot-MyBatis-Project
_기본 CRUD에 기능을 추가한 게시판 웹 어플리케이션 제작_

### 개요
- 현재까지의 학습 내용 복기
- 팀 프로젝트 진행 시 주도적을 구현 해 보지 못한 기능 사용 목적

### 환경 설정
- Build Tool : Gradle
- View : JSP
- Database : Oracle
    - koeyh / p@ss_word
- Sql Mapper : MyBatis

### _📌 구현 목표_
1. 게시판 기본 CRUD 기능 (게시물 생성, 조회, 수정, 삭제)
2. 다중 파일(image) 첨부 기능 구현
3. 로그인 세션 적용 / Spring Security 적용으로 대체도 생각 해 볼것
4. 로그인 계정에 따라 데이터 수정, 삭제 기능 제한
5. 여유가 된다면 관리자 화면 설정

### Day1 ('24. 6. 18)
- controller에서 view(JSP) 로드 안됨
    - build.gradle 의존성 확인
    - application.properties 설정 확인
    - 파일 경로 확인
    - 모두 마쳤는데도 증상 지속
    - Visual Studio Code에서 폴더를 열 때 한층 더 상위 계층의 폴더를 연 것을 확인
    - 프로젝트 폴더 수정 후 해결
