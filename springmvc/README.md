# spring-mvc-1
[인프런] 스프링 MVC 1편 - 백엔드 웹 개발 핵심 기술  
> servlet 폴더에서   
> [섹션2] basic  
> [섹션3] web.servlet  
> [섹션3] web.servletmvc  
> [섹션4] web.frontcontroller   
> [섹션5] web.springmvc 패키지 순으로 볼 것

## 2. 서블릿
### 2.1 Hello 서블릿
- basic/HelloServlet.java
### 2.4 HttpServletRequest - 기본 사용법
- basic/request/RequestHeaderServlet.java
### 2.6 HTTP 요청 데이터 - GET 쿼리 파라미터
- basic/request/RequestParamServlet.java
### 2.7 HTTP 요청 데이터 - POST HTML Form
- webapp/basic/hello-form.html
- (또는) Postman 요청
### 2.8 HTTP 요청 데이터 - API 메시지 바디 - 단순 텍스트
- basic/request/RequestBodyStringServlet.java
### 2.8 HTTP 요청 데이터 - API 메시지 바디 - JSON
- basic/request/RequestBodyJsonServlet.java
- basic/HelloData.java
### 2.9 HttpServletResponse - 기본 사용법
- basic/response/ResponseHeaderServlet.java
### 2.10 HTTP 응답 데이터 - 단순 텍스트, HTML
- basic/response/ResponseHtmlServlet.java
### 2.11 HTTP 응답 데이터 - API JSON
- basic/response/ResponseJsonServlet.java

---
## 4. MVC 프레임워크 만들기
- web/frontcontroller 패키지

---
## 5. 스프링 MVC - 구조 이해
### 5.2 핸들러 매핑과 핸들러 어댑터
- web/springmvc/old/OldController.java
- web/springmvc/old/MyHttpRequestHandler.java
### 5.4 스프링 MVC - 시작하기
- web/springmvc/v1 패키지
### 5.5 스프링 MVC - 컨트롤러 통합
- web/springmvc/v2 패키지
### 5.6 스프링 MVC - 실용적인 방식
- web/springmvc/v3 패키지

---
## 6. 스프링 MVC - 기본 기능
> springmvc 폴더 볼 것  
> 목차 : src/main/resources/static/index.html
### 6.1 로깅 간단히 알아보기
- basic/LogTestController.java
### 6.3 요청 매핑
- basic/requestmapping/MappingController.java
### 6.4 요청 매핑 - API 예시
- basic/requestmapping/MappingClassController.java
### 6.5 HTTP 요청 - 기본, 헤더 조회
- basic/request/RequestHeaderController.java
### 6.6 HTTP 요청 파라미터 - 쿼리 파라미터, HTML Form
### 6.7 HTTP 요청 파라미터 - @RequestParam
- basic/request/RequestParamController.java
- static/basic/hello-basic.html
### 6.8 HTTP 요청 파라미터 - @ModelAttribute
- basic/HelloData.java
- basic/request/RequestParamController.java
### 6.9 HTTP 요청 메시지 - 단순 텍스트
- basic/request/RequestBodyStringController.java
### 6.10 HTTP 요청 메시지 - JSON
- basic/request/RequestsBodyJsonController.java
### 6.11 응답 - 정적 리소스, 뷰 템플릿
- basic/response/ResponseViewController.java
### 6.12 HTTP 응답 - HTTP API, 메시지 바디에 직접 입력


