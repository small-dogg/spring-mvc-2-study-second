# spring-mvc-2-study-second
[inflearn] 스프링 MVC 2편 - 백엔드 웹 개발 활용 기술(스프링 통합과 폼)


## 참고 문헌

### 참고자료
- 기본 메뉴얼: https://www.thymeleaf.org/doc/tutorials/3.0/usingthymeleaf.html
- 스프링 통합 메뉴얼: https://www.thymeleaf.org/doc/tutorials/3.0/thymeleafspring.html

### 설정 방법
타임리프 템플릿 엔진을 스프링 빈에 등록하고, 타임리프용 뷰 리졸버를 스프링 빈으로 등록하는 방법
- https://www.thymeleaf.org/doc/tutorials/3.0/thymeleafspring.html#the-springstandarddialect
- https://www.thymeleaf.org/doc/tutorials/3.0/thymeleafspring.html#views-and-viewresolvers

### 스프링 부트가 제공하는 타임리프 설정, thymeleaf 검색 필요
https://docs.spring.io/spring-boot/docs/current/reference/html/appendix-applicationproperties.html#common-application-properties-templating

## 학습 내용
본 학습에서는 각각의 form(items.html 제외)에 여러 input 타입을 적용 해보았다.
- 입력 폼 처리
- 체크 박스 - 단일
- 체크 박스 - 멀티
- 라디오 버튼
- 셀렉트 박스
- 정리