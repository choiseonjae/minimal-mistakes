---
title: Maven 저장소 이용하기
categories:  
- java 
- maven

tags:
   - maven
   - pom.xml
   - repository

author_profile: true #작성자 프로필 출력여부
read_time: true # read_time을 출력할지 여부 1min read 같은것!

toc: true #Table Of Contents 목차 보여줌2
toc_label: "My Table of Contents" # toc 이름 정의
toc_icon: "cog" # font Awesome아이콘으로 toc 아이콘 설정 
toc_sticky: true # 스크롤 내릴때 같이 내려가는 목차

last_modified_at: 2020-03-24T08:33:00 # 마지막 변경일

---
기존에는 필요한 **라이브러리를 다운**받아 넣어줘야 사용할 수 있던 것을 **pom.xml에 태그만 기술**함으로서 쉽게 라이브러리를 사용할 수 있게 되었다.  
그렇게 할 수 있는데에는 **메이븐 중앙 저장소** 덕분이다.  

중앙 저장소는 일종의 라이브러리 보관 장소이고, 메이븐을 개발한 아파치 소프트웨어 재단이 운영하는 [사이트](https://repo1.maven.org/maven2/)이다.

주소를 지정해 원하는 저장소로 지정 가능하지만 아무것도 지정하지 않으면 **기본값으로 [메이븐 중앙 저장소](https://repo1.maven.org/maven2/)**이 지정된다.  

실제 사이트로 들어가보면 단순히 **프로그램 이름**(그룹ID, 아티팩트ID)로 디렉토리를 나누어 공개하고 있을 뿐 원하는 라이브러리를 찾기는 쉽지 않다.  
즉, 메이븐이 찾기에는 좋은 곳이지만 사용자가 원하는 라이브러리를 조사하기 위해 접속해봐도 별 도움은 되지 않는다.  

그래서 중앙 저장소에 등록된 라이브러리를 쉽게 검색해볼수 있는 [사이트](https://search.maven.org/)가 있다.  
검색 창에 원하는 소프트웨어 이름을 입력하면 결과가 나온다.

메이븐 중앙 저장소를 이용하는 방법은 [해당 포스팅](https://choiseonjae.github.io/java/maven/repository/central/)을 참고하면 된다.  

# 원격 저장소









# Reference
*  [자바 프로젝트 필수 유틸리티](https://books.google.co.kr/books/about/%EC%9E%90%EB%B0%94_%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8_%ED%95%84%EC%88%98_%EC%9C%A0%ED%8B%B8%EB%A6%AC%ED%8B%B0.html?id=jZdaDwAAQBAJ&printsec=frontcover&source=kp_read_button&redir_esc=y#v=onepage&q&f=false)

* [메이븐 검색 사이트](https://search.maven.org/)

* [메이븐 중앙 저장소](https://repo1.maven.org/maven2/)

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTgzMjIzMDQzMiw3MzM0ODYzMzUsMTYyMj
c3MDAxMl19
-->