# 레벨3 - 팀 프로젝트

## [GPU 내껀데](https://github.com/woowacourse-teams/2021-gpu-is-mine)
- 딥러닝 학습 자동화 서비스
- [Team TechLogs](https://github.com/woowacourse-teams/2021-gpu-is-mine#techlogs)
- [레벨3 개인 블로그 정리](https://nauni.tistory.com/category/%EC%9A%B0%EC%95%84%ED%95%9C%ED%85%8C%ED%81%AC%EC%BD%94%EC%8A%A4/%EB%A0%88%EB%B2%A83)
- [레벨4 개인 블로그 정리](https://nauni.tistory.com/category/%EC%9A%B0%EC%95%84%ED%95%9C%ED%85%8C%ED%81%AC%EC%BD%94%EC%8A%A4/%EB%A0%88%EB%B2%A84)

## 백엔드 사용기술
- Java, SpringBoot, JPA
- AWS EC2, Jenkins, nginx, Docker
- MariaDB, H2, Flyway(DB migration)
- ElasticStack
- Submodule

---
# 서비스근로

## [우아한테크코스 지원서비스](https://github.com/woowacourse/service-apply)
- 우아한테크코스 지원부터 최종 합격까지 관리 서비스
- 작년에 배포되어 사용된 서비스를 유지 및 보수
- 2021.10.22~ 우아한테크코스 4기 지원 시작
- [코드리뷰 문화](https://github.com/woowacourse/service-apply/pulls?q=is%3Aopen+is%3Apr)

## 백엔드 사용기술
- Kotlin, SpringBoot, JPA
- MySQL, H2, Flyway(DB migration)
- Vaadin

## 백엔드 추가 및 개선기능
- Mockito 테스트코드 MockK로 전환
- 유효한 이메일 인증
- 회원과 지원자 분리
- 모집삭제 정책 구현
- 이메일 발송 기능
- 과제 관리 기능
- csv 파일로 평가 관리 기능
- 부정행위자 관리 기능
- 추후 관리자페이지 react 전환을 위한 API 작업

---
# 레벨4
Http 서버 구현, MVC 프레임워크 구현, JDBC Template 구현

# 미션 목록
- 코드로 구현하며 추상화 된 동작방식을 이해

## [http 서버](https://github.com/knae11/woowalevel4/tree/http)
- http 요청을 읽고 해석하여 적절한 응답을 반환하는 기능 구현
- [reflection을 사용하여 GetMapping annotation 만들기](https://nauni.tistory.com/293)
- [File, inputStream, outputStream](https://nauni.tistory.com/294)
- [http/1.1 프로토콜](https://nauni.tistory.com/295) 
- [1단계 PR](https://github.com/woowacourse/jwp-dashboard-http/pull/37)
- [2,3단계 PR](https://github.com/woowacourse/jwp-dashboard-http/pull/84)

## [mvc 프레임워크](https://github.com/knae11/woowalevel4/tree/mvc)
-  기존 ManualController로 되어있는 내용을 AnnotationController로 변환하는 작업 
-  Java Reflection
-  [Spring Web MVC DispatcherServlet](https://nauni.tistory.com/300)
-  [1단계 PR](https://github.com/woowacourse/jwp-dashboard-mvc/pull/23)
-  [2,3단계 PR](https://github.com/woowacourse/jwp-dashboard-mvc/pull/75)

## [jdcb](https://github.com/knae11/woowalevel4/tree/jdbc)
- 기본 DAO에서 find, insert 구현이 된 코드를 리팩토링하며 추가 기능 구현
- 익명 클래스, 함수형 인터페이스, 람다
- 제네릭
- 가변 인자
- 템플릿 콜백 패턴
- try-with-resources
- checked vs unchecked exception
- [PR](https://github.com/woowacourse/jwp-dashboard-jdbc/pull/5)

# 학습내용 정리
- [레벨4 블로그](https://nauni.tistory.com/category/%EC%9A%B0%EC%95%84%ED%95%9C%ED%85%8C%ED%81%AC%EC%BD%94%EC%8A%A4/%EB%A0%88%EB%B2%A84)
- [레벨4 모음 repo](https://github.com/knae11/woowalevel4)
---

# 레벨2
Spring 입문, Mock 테스트, 통합테스트, Acceptance 테스트, 배포인프라

# 미션 목록
- Java 8, Spring 기반의 미션을 진행 

## [체스 jwp](https://github.com/knae11/woowalevel2/tree/jwp-chess)
- [스프링입문, MVC](https://nauni.tistory.com/226?category=927888)
- [JDBC, CORE](https://nauni.tistory.com/229?category=927888)
- AWS EC2 배포
- MockTest, SliceTest
- 웹 프론트엔드
- 페어의 코드 리팩토링
- [체스 jwp 학습로그](https://nauni.tistory.com/223?category=927888)
- [1&2단계 PR](https://github.com/woowacourse/jwp-chess/pull/245)
- [3단계 PR](https://github.com/woowacourse/jwp-chess/pull/321)

## [지하철 map](https://github.com/knae11/woowalevel2/tree/subway-map)
- AcceptanceTest
- 각 레이어의 역할
- [REST API](https://nauni.tistory.com/230?category=927888)
- [지하철 map 학습로그](https://nauni.tistory.com/247?category=927888)
- [1&2단계 PR](https://github.com/woowacourse/atdd-subway-map/pull/65)
- [3단계 PR](https://github.com/woowacourse/atdd-subway-map/pull/121)

## [지하철 path](https://github.com/knae11/woowalevel2/tree/subway-path)
- Spring Config(Auth)
- [E2E테스트, 인증과 인가](https://nauni.tistory.com/246?category=927888)
- [지하철 path 학습로그](https://nauni.tistory.com/248?category=927888)
- [1,2단계 PR](https://github.com/woowacourse/atdd-subway-path/pull/77)
- [3단계 PR](https://github.com/woowacourse/atdd-subway-path/pull/121)

## [지하철 fare](https://github.com/knae11/woowalevel2/tree/subway-fare)
- 프론트엔드(1팀:2명), 백엔드(2팀:4명) 사이의 간단한 협업 경험
- Spring Configuration
- [지하철 fare 학습로그](https://nauni.tistory.com/256?category=927888)
- [협업미션 PR](https://github.com/woowacourse/atdd-subway-fare/pull/16)

# 학습내용 정리
- [레벨2 블로그](https://nauni.tistory.com/category/%EC%9A%B0%EC%95%84%ED%95%9C%ED%85%8C%ED%81%AC%EC%BD%94%EC%8A%A4/%EB%A0%88%EB%B2%A82)
- [레벨2 모음 repo](https://github.com/knae11/woowalevel2)
---

# 레벨1
java 8, 객체지향, 테스트, TDD, 코드리뷰, 페어프로그래밍

# 미션 목록
- Java 8 기반의 콘솔출력 기반의 미션을 진행 

## [자동차경주게임](https://github.com/knae11/woowalevel1/tree/racing-car)
- 페어프로그래밍
- 객체지향
- [TDD](https://nauni.tistory.com/141?category=913481)
- MVC 패턴
- [정적팩토리메소드](https://nauni.tistory.com/128?category=913481)
- [생성자체이닝, 일급컬렉션, 원시값포장](https://nauni.tistory.com/135?category=913481)
- [불변객체, 방어적복사](https://nauni.tistory.com/136?category=913481)
- [1단계 미션 PR](https://github.com/woowacourse/java-racingcar/pull/190)   
- [2단계 미션 PR](https://github.com/woowacourse/java-racingcar/pull/252)     

## [로또](https://github.com/knae11/woowalevel1/tree/lotto)
- OOP
- [로또 미션 학습로그](https://nauni.tistory.com/151)
- [제네릭과 와일드카드](https://nauni.tistory.com/143?category=913481)
- [레거시코드 TDD, cache](https://nauni.tistory.com/155?category=913481)
- [1단계 미션 PR](https://github.com/woowacourse/java-lotto/pull/255)    
- [2단계 미션 PR](https://github.com/woowacourse/java-lotto/pull/288)

## [블랙잭](https://github.com/knae11/woowalevel1/tree/blackjack)
- 상속, 인터페이스
- [블랙잭 학습로그](https://nauni.tistory.com/164?category=913481)
- [상속과 조합, 좋은 객체의 7가지 덕목](https://nauni.tistory.com/165?category=913481)
- [상속, 조합, 인터페이스](https://nauni.tistory.com/167?category=913481)
- [객체지향 SOLID](https://nauni.tistory.com/172?category=913481)
- [상태패턴](https://nauni.tistory.com/187?category=913481)
- [1단계 미션 PR](https://github.com/woowacourse/java-blackjack/pull/127)   
- [2단계 미션 PR](https://github.com/woowacourse/java-blackjack/pull/209)     

## [체스](https://github.com/knae11/woowalevel1/tree/chess)
- FB, 웹, DB
- [체스 학습로그](https://nauni.tistory.com/209?category=913481)
- [람다와 스트림](https://nauni.tistory.com/193?category=913481)
- [OOP](https://nauni.tistory.com/192?category=913481)
- [js todo 리스트 미션 PR](https://github.com/woowacourse/js-todo-list-step1/pull/29)
- [DB 생활코딩 강의 정리](https://nauni.tistory.com/category/Computer%20Science/DB)
- [1,2,3단계 미션 PR](https://github.com/woowacourse/java-chess/pull/201)   
- [4,5단계 미션 PR](https://github.com/woowacourse/java-chess/pull/230)   


# 학습내용 정리
- [레벨1 블로그](https://nauni.tistory.com/category/%EC%9A%B0%EC%95%84%ED%95%9C%ED%85%8C%ED%81%AC%EC%BD%94%EC%8A%A4/%EB%A0%88%EB%B2%A81)
- [레벨1 모음 repo](https://github.com/knae11/woowalevel1)
