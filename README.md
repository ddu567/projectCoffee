# ☕ Coffee Cong
📌[이동하기](http://13.209.201.181:8080/)


### 🖥 프로젝트
- 소개: 커피 원두와 관련 도구를 구매할 수 있는 커피 관련 쇼핑몰입니다.
- 개발 기간: 2023년 12월 11일 ~ 12월 26일
- 개발 인원: 4명 (백엔드 3명, 프론트엔드 1명)
- 담당 역할: 로그인, 회원가입, 회원 정보 수정 및 탈퇴 (프론트엔드 포함)


### ⚙ 개발 환경
- 언어: Java(JDK 11.0.19), HTML/CSS, JavaScript
- 서버: AWS EC2
- 프레임워크: Spring boot(2.7.17), JPA
- 빌드 도구: Maven(1.1.3)
- DB: MySQL(8.0)
- IDE: IntelliJ
- API: Google/Naver/Kakao Login API, Daum 주소 검색
- 라이브러리: lombok, thymeleaf(3.1.0), Spring Security, OAuth2


### 📝 코드 보기
<details>
  <summary>회원 관련</summary>
  <a href="https://github.com/ddu567/projectCoffee/blob/main/projectCoffee/src/main/java/projectCoffee/entity/Member.java">member</a> <br>
  <a href="https://github.com/ddu567/projectCoffee/blob/main/projectCoffee/src/main/java/projectCoffee/dto/MemberFormDto.java">MemberFormDto</a> <br>
  <a href="https://github.com/ddu567/projectCoffee/blob/main/projectCoffee/src/main/java/projectCoffee/dto/MemberUpdateDto.java">MemberUpdateDto</a> <br>
  <a href="https://github.com/ddu567/projectCoffee/blob/main/projectCoffee/src/main/java/projectCoffee/dto/SessionMember.java">SessionMember</a> <br>
  <a href="https://github.com/ddu567/projectCoffee/blob/main/projectCoffee/src/main/java/projectCoffee/repository/MemberRepository.java">MemberRepository</a> <br>
  <a href="https://github.com/ddu567/projectCoffee/blob/main/projectCoffee/src/main/java/projectCoffee/service/MemberService.java">MemberService</a> <br>
  <a href="https://github.com/ddu567/projectCoffee/blob/main/projectCoffee/src/main/java/projectCoffee/controller/MemberController.java">MemberController</a>
</details>
<details>
  <summary>로그인 관련</summary>
  <a href="https://github.com/ddu567/projectCoffee/blob/main/projectCoffee/src/main/java/projectCoffee/config/SecurityConfig.java">SecurityConfig</a> <br>
  <a href="https://github.com/ddu567/projectCoffee/blob/main/projectCoffee/src/main/java/projectCoffee/dto/OAuthAttributes.java">OAuthAttributes</a><br>
  <a href="https://github.com/ddu567/projectCoffee/blob/main/projectCoffee/src/main/java/projectCoffee/service/OAuth2MemberService.java">OAuth2MemberService</a><br>
  <a href="https://github.com/ddu567/projectCoffee/blob/main/projectCoffee/src/main/java/projectCoffee/service/CustomOAuthService.java">CustomOAuthService</a><br>
  <a href="https://github.com/ddu567/projectCoffee/blob/main/projectCoffee/src/main/java/projectCoffee/service/OAuth2MemberService.java">OAuth2MemberService</a><br>
</details>
