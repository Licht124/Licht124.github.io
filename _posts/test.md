---
title: "[포스팅 예시] Test"
excerpt: "Test 작성"

categories:
  - Categories4
tags:
  - [tag1, tag2]

permalink: /categories4/post-name-here-4/

toc: true
toc_sticky: true

date: 2022-07-24
last_modified_at: 2022-07-24
---

## 🦥 본문

본문은 여기에 ...

#### 📙 #JSP_1101_과제

1. 폼 페이지에서 입력된 데이터를 전달하는 요청 파라미터 값을 JSP 페이지로 가져오는 내장객체는?
	- request
	- 자주 사용되는 메소드 : getParameter()

2. 서버에서 웹 브라우저에 다른 페이지로 강제 이동하도록 명령하는 내장 객체와 관련된 메소드는 무엇인가?
	- response
	- 메소드 : sendRedirect()

3. 스크립트 태그의 표현문과 같이 데이터를 출력하는 내장 객체는 무엇인가?
	- out 내장 객체


---

#### 📙 #JSP_getQueryString

1. 리턴 형태
	- id=admin&pw=1234

---


#### 📙 #JSP_Calender


<% out.println("오늘의 날짜 및 시각 : " + Calendar.getInstance().getTime()); %>

<%=java.util.Calendar.getInstance().getTime()%>

---
#### 📙 #JSP_페이지_갱신_5초

response.setIntHeader("Refresh",5);

--- 
