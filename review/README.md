# 패스트캠퍼스 자바지기님의 강의 수강을 마치며

2016.06.27 ~ 2016.08.25 총 8.5주라는 시간동안 [자바지기님의 강의](http://www.fastcampus.co.kr/dev_camp_jwp/)를 수강하였다. <br/>
* 강의는 얼마나 좋았는가?
  - 얼리버드라서 할인을 받았지만 120만원(기본은 145만원)이란 금액을 지불하였다. (내돈으로.. 회사돈 아님)
  - 근데 이번 강의의 다음 스탭에 해당하는 강의가 개설되면 또 들을 생각이다. 내돈으로
  - 8주에 120~150만원 이란 금액이 작은 금액은 아니다. 근데 **또 들어야겠다고 생각이 들정도로 좋은 강의**였다.

강의 내용에 대해선 [Github](https://github.com/jojoldu/fastcampus-java)에 정리 하였으니 참고하면 좋을것 같다. <br/>
(아직도 작성중이다. 수업내용을 복기하는 마음으로 다시 보면서 내용을 추가/수정중이다.)
* 다른 회사의 개발방식을 알수 있었다.
  - 우리회사도 SpringBoot와 ORM을 사용중이다 (SpringDataJpa가 아닌 네이티브 하이버네이트이지만...)
  - 하지만 TDD를 진행하지 않고 있으며,
  - 개인적으로 **가장 좋았던 부분**이다.

* 맞춤형 강의였다.
  - 2주정도 지난 시점에서 수강생들의 실력이 비슷하지 않다는것을 인지하시고, 강의 내용을 2가지 타입으로 나누셨다.
  - A : SpringMVC 이미 사용해본 수강생들에겐 직접 MVC/DI 프레임워크를 구축하는 과정을 진행
  - B : SpringMVC 혹은 웹개발을 처음 접한 수강생들에겐 SpringMVC를 사용한 웹개발 과정을 진행
  - 각자 실력에 맞게 A/B를 나눠서 동시 진행하다보니 너무 어려워하거나 쉬워하는 수강생들이 줄어 끝까지 텐션을 유지할 수 있었다.

* 우리가 사용중인 프레임워크를 직접 구현해보았다. 
  - 톰캣도 없고, Spring도 없는 상황에서 순수 Servlet 만으로 게시판을 구현해보는 경험은 절대 이 시간외에는 경험해보지 못했을 것이다.
  - HttpRequest가 쓰레드를 상속 받는것을 이제야 알았다.
  - JDBC Template를 직접 구현해보았다. (난 시간이 되서 ORM도 도전해보았다.)
  - 

* TDD를 시작할수 있게 되었다.
  - 사내 우리팀에서 TDD가 활성화 되어 있지 않아(타팀은 하는지 잘모르겠어서..), 온라인상에서 아무리 TDD의 중요성을 외쳐도 실감하지 못하고 있었다.
  - 책이나 동영상 강의로 혼자 공부하기는 어려웠다. 뜬구름잡는 이야기도 많았고, 웹 프로젝트보다는 Java 어플리케이션을 예제코드로 보여줘서 Bean Injection, DB연동, HttpRequest 등에 대한 테스트를 알수없었다.
  - 강의에서 Junit & Mockito같은 테스트 프레임워크 없이 테스트 코드 
  - 블로그에 기술관련 포스팅을 할 경우 항상 테스트 코드를 통해 코드를 공개하게 되었다.
  - 회사에서 웬만큼 일정이 급하지 않은 경우에 테스트 코드를 작성하면서 개발을 진행하게 되었다.

* 객체지향적 코딩에 대해 
  - 