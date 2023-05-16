<!-- # Springboot-MyBatis-Recruitment-Project -->

# HIGHRE - 개발자를 위한 구인구직 웹사이트 - V2
![image](https://user-images.githubusercontent.com/122351733/223630188-a70350c4-3496-4705-bfe3-c031f68d27f3.png)

<br> 

# 소개
>'고용하다'라는 의미의 Hire와 '더 높은'이라는 의미의 Higher를
><br>합쳐 고객들에게 더 좋은 일자리를 제공한다는 의미를 담았습니다

<br> 

# ⏰ 개발 기간
- 2023.03.20~2023.03.27(1주)

<br>

# ⚙️ 기술스택
- 언어: JDK 11
- 백엔드: Springboot 2.7.8
- 프론트엔드: HTML5, CSS3, Javascript, JSP, Bootstrap
- 데이터베이스: 테스트 H2, 프로덕션 MySQL, MyBatis, Redis 세션
- 테스트: Junit
- IDE: Visual Studio Code
- VCS: Github

<br>

# 🖥 아키텍쳐(MVC)

![image](https://user-images.githubusercontent.com/122351733/223648466-ee6ce325-64b3-4f82-888b-5d627e5e55fe.png)

<br>

> ## 내가 한 기능

### Rest API 
1차 프로젝트에서 구현 했었던 MVC 패턴을 Rest API 형식으로 변환 하는 작업을 함. <br>
- Bookmark 
- Resume
- UserPage

### JWT 
- JWT 토큰을 사용하여 로그인시 Jwt토큰 받아 Header에 넣기
- Filter를 통해서 로그인 인증이 필요한 경로 토큰을 비교 

### swagger 
- 문서화 시키기 위해 Spring에 swagger 적용
- 각각의 Controller에 Target 과 Operation 지정하여 명칭 지정
- 컴포넌트 사용하여 Header에 Athorization 설정 후 토큰 넣을 수 있게 설정
- 번호를 매겨서 시나리오 순서대로 정렬


# 📝 기능정리

## V2 업데이트
<details>
  <summary>REST API</summary>
  <ul>
  <br>
    <li>MyBatis ORM 구현</li>
    <li>RESTful URI 설계</li>
    <li>JSON 데이터 요청, 응답 구현</li>
  <br>
  </ul>
</details>
<details>
  <summary>Junit TEST</summary>
  <ul>
  <br>
    <li>전체 Controller 테스트 완료</li>
    <li>JWT 테스트 완료</li>
    <li>SALT 암호화 테스트 완료</li>
  <br>
  </ul>
</details>
<details>
  <summary>JWT</summary>
  <ul>
  <br>
    <li>JWT 기반 Stateless 서버 구축</li>
    <li>WhiteURLList 구현</li>
  <br>
  </ul>
</details>
<details>
  <summary>OAuth</summary>
  <ul>
  <br>
    <li>OAuth 카카오 로그인 구현</li>
  <br>
  </ul>
</details>
<details>
  <summary>AOP</summary>
  <ul>
  <br>
    <li>AOP 인증 처리 구현</li>
    <li>AOP 인가 처리 구현</li>
    <li>HandlerMethodArgumentResolver 사용하여 매개변수 값 주입 구현</li>
  <br>
  </ul>
</details>
<details>
  <summary>Interceptor</summary>
  <ul>
  <br>
    <li>요청 응답 후 세션 만료화 구현</li>
  <br>
  </ul>
</details>
<details>
  <summary>Filter</summary>
  <ul>
  <br>
    <li>Filter단에서 JWT 검증 처리</li>
  <br>
  </ul>
</details>

<br>

# 📺 Swagger API
### Swagger API 문서 자동화
<img src="https://user-images.githubusercontent.com/93416157/230993358-a673d786-c447-4789-bad7-22a6ecd9e805.gif" width="850" height="450" />
<br>

### Swagger API Repository 링크
https://github.com/Khohyeon/swagger-job

<br>


