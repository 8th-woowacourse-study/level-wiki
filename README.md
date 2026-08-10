# level-wiki
레벨별 주제 토론

<details>
  <summary><h1>Level 1</h1></summary>

  ## Java
  
  1. [Optional은 언제 사용해야할까? #1](https://github.com/8th-woowacourse-study/level-wiki/discussions/1)
  2. [접근 제어자들의 차이점 #2](https://github.com/8th-woowacourse-study/level-wiki/discussions/2)
  3. [static메서드는 언제사용할까? #12](https://github.com/8th-woowacourse-study/level-wiki/discussions/12)
  4. [DTO는 view 영역인가? controller 영역인가? 아니면 별도의 영역인가? #3](https://github.com/8th-woowacourse-study/level-wiki/discussions/3)
  5. [자바에서 제공하는 함수형 인터페이스 #4](https://github.com/8th-woowacourse-study/level-wiki/discussions/4)
  6. [Enum은 단순한 상수의 집합인가? 언제 어떻게 사용하는게 좋을까? #5](https://github.com/8th-woowacourse-study/level-wiki/discussions/5)
  7. [인터페이스와 추상클래스의 차이 #11](https://github.com/8th-woowacourse-study/level-wiki/discussions/11)
  8. [`SQLException`을 바로 던지지 않고, 다른 예외로 변환해서 던지는 이유 #7](https://github.com/8th-woowacourse-study/level-wiki/discussions/7)
  9. [정적 팩토리 매서드는 언제/어떻게 사용해야할까? #13](https://github.com/8th-woowacourse-study/level-wiki/discussions/13)

  ## Clean Code

  1. [indent depth 2 이내 규칙에 대해서 어떻게 생각하나요? #8](https://github.com/8th-woowacourse-study/level-wiki/discussions/8)
  2. [네이밍은 어떻게 하는게 좋을까요? #20](https://github.com/8th-woowacourse-study/level-wiki/discussions/20)
  3. [객체 생성 전 검증과 생성 후 검증 중 무엇이 자연스러운가 #63](https://github.com/8th-woowacourse-study/level-wiki/discussions/63)

  ## OOP

  1. [메서드 선언 방식에 대하여 언제 어떤 방식으로 사용하는게 좋을까요? #6](https://github.com/8th-woowacourse-study/level-wiki/discussions/6)
  2. [원시값 포장: 우리는 '왜' 그리고 '언제' 해야 할까요? #14](https://github.com/8th-woowacourse-study/level-wiki/discussions/14)
  3. [불변 객체는 언제 만들어야할까요? #15](https://github.com/8th-woowacourse-study/level-wiki/discussions/15)
  4. [상수의 위치와 접근 제어자 #17](https://github.com/8th-woowacourse-study/level-wiki/discussions/17)
  5. [상태를 변경하는 메서드가 결과를 반환해도 될까요? #22](https://github.com/8th-woowacourse-study/level-wiki/discussions/22)

  ## Design & Architecture

  1. [record를 VO로 사용해도 될까? 혹은 완전한 대체제가 될 수 있을까? #9](https://github.com/8th-woowacourse-study/level-wiki/discussions/9)
  2. [Service는 Stateless해야 한다 -- 그 의미는 무엇일까? #19](https://github.com/8th-woowacourse-study/level-wiki/discussions/19)
  3. [상태 패턴: 객체의 자율성과 전이 책임의 소재 #21](https://github.com/8th-woowacourse-study/level-wiki/discussions/21)

  ## Testing

  1. [JDBC의 로직 테스트를 어떻게 하는게 좋을까요? #18](https://github.com/8th-woowacourse-study/level-wiki/discussions/18)
  2. [Mock은 언제, 어떻게 사용해야할까? #10](https://github.com/8th-woowacourse-study/level-wiki/discussions/10)
  3. [테스트 더블에 대하여 #16](https://github.com/8th-woowacourse-study/level-wiki/discussions/16)
  4. [Spring 테스트는 어디까지 띄워야 할까? (@SpringBootTest, Slice Test, MockMvc, RestAssured) #62](https://github.com/8th-woowacourse-study/level-wiki/discussions/62)

  ## JDBC

  1. [Statement와 PreparedStatement의 차이 #23](https://github.com/8th-woowacourse-study/level-wiki/discussions/23)
  
</details>

<details open>
  <summary><h1>Level 2</h1></summary>

  ## Java
  
  1. [DTO는 계층 간 데이터 전달 객체일 뿐인가, 비즈니스 의미를 가져도 되는가? #31](https://github.com/8th-woowacourse-study/level-wiki/discussions/31)
  2. [어노테이션(@)은 무엇인가? #32](https://github.com/8th-woowacourse-study/level-wiki/discussions/32)
  3. [final을 좋아하세요? #42](https://github.com/8th-woowacourse-study/level-wiki/discussions/42)

  ## Design & Architecture

  1. [없는 데이터 삭제 시 204 vs 404 #34](https://github.com/8th-woowacourse-study/level-wiki/discussions/34)
  2. [패키지 분리는 어떻게 할까? #35](https://github.com/8th-woowacourse-study/level-wiki/discussions/35)
  3. [쿼리 한 번은 실제로 얼마나 비쌀까요? #39](https://github.com/8th-woowacourse-study/level-wiki/discussions/39)
  4. [이미 언체크 예외인 Spring 데이터 예외, 어디서 잡아야 할까? #43](https://github.com/8th-woowacourse-study/level-wiki/discussions/43)
  5. [커스텀 예외의 본질은 메시지 관리일까, 실패 타입 표현일까? #47](https://github.com/8th-woowacourse-study/level-wiki/discussions/47)
  6. [입력값 검증은 어디서 해야할까? Controller vs Domain #48](https://github.com/8th-woowacourse-study/level-wiki/discussions/48)
  7. [예약 취소 배치(Scheduler)와 실시간 요청 간의 동시성 이슈 및 해결 방안 #60](https://github.com/8th-woowacourse-study/level-wiki/discussions/60)
  8. [외부 결제 승인은 성공했는데 DB 반영이 실패하면, 우리는 어떤 상태로 수렴시켜야 할까요?](https://github.com/8th-woowacourse-study/level-wiki/discussions/67)
  9. [동기 LLM 호출을 트랜잭션 안에서 처리해도 되는가](https://github.com/8th-woowacourse-study/level-wiki/discussions/68)
  10. [Timeout과 Rate Limit 값은 어떤 관측 지표를 보고 조정해야 할까요?](https://github.com/8th-woowacourse-study/level-wiki/discussions/69)
  11. [필요한 데이터가 여러가지일 때, API를 여러 번 호출할지, 한 번에 호출할지?](https://github.com/8th-woowacourse-study/level-wiki/discussions/70)
  12. [도메인 엔티티와 영속성 엔티티 분리](https://github.com/8th-woowacourse-study/level-wiki/discussions/71)

  ## Testing
  
  1. [Mocking이 나쁜 코드의 신호라는 말은 어떤 의미일까? #33](https://github.com/8th-woowacourse-study/level-wiki/discussions/33)
  2. [@DirtiesContext의 편리함과 느린 테스트 사이의 선택 #37](https://github.com/8th-woowacourse-study/level-wiki/discussions/37)

  ## Jdbc

  1. [SimpleJdbcInsert + ParameterSource가 파라미터 이름을 어떻게 컬럼명으로 매핑할까요? #36](https://github.com/8th-woowacourse-study/level-wiki/discussions/36)
  
  ## Spring
  
  1. [생성된 식별자 조회: KeyHolder vs SimpleJdbcInsert #29](https://github.com/8th-woowacourse-study/level-wiki/discussions/29)
  2. [DAO의 책임 범위: ReservationDao가 JOIN을 해야 할까, Service가 조립해야 할까? #30](https://github.com/8th-woowacourse-study/level-wiki/discussions/30)
  3. [@Transactional, 어디까지 잡아야 할까? #38](https://github.com/8th-woowacourse-study/level-wiki/discussions/38)
  4. [Spring MVC 요청 흐름 #40](https://github.com/8th-woowacourse-study/level-wiki/discussions/40)
  5. [Spring에서 Controller는 실제 Service를 모른다!? #45](https://github.com/8th-woowacourse-study/level-wiki/discussions/45)
  6. [Entity를 불변 객체로 만들어야 할까요? #46](https://github.com/8th-woowacourse-study/level-wiki/discussions/46)
  7. [FeignClient vs RestClient #61](https://github.com/8th-woowacourse-study/level-wiki/discussions/61)
  8. [요청마다 인증/인가 처리 어떻게 하시나요? #59](https://github.com/8th-woowacourse-study/level-wiki/discussions/59)

  ## Database

  1. [UK, FK를 DB에서 설정하지 않을 때의 장단점과 설정하는 기준 #41](https://github.com/8th-woowacourse-study/level-wiki/discussions/41)
  2. [HardDelete vs SoftDelete 그 선택의 기준은? #44](https://github.com/8th-woowacourse-study/level-wiki/discussions/44)
  3. [Redis는 왜 싱글 스레드를 택했을까요?](https://github.com/8th-woowacourse-study/level-wiki/discussions/66)
  4. [서비스에서 중복 검증을 하는데 DB UNIQUE 제약이 필요할까?](https://github.com/8th-woowacourse-study/level-wiki/discussions/72)

  ## AI
  1. [효율적인 AI 컨텍스트 관리는 어떻게 하면 좋을까?](https://github.com/8th-woowacourse-study/level-wiki/discussions/64)
  2. [AI 성공 기준을 어떻게 잡아야 할까요?](https://github.com/8th-woowacourse-study/level-wiki/discussions/65)
  3. [시장에서는 왜 다중 에이전트 시스템(MAS)이 채택되었을까요?](https://github.com/8th-woowacourse-study/level-wiki/discussions/73)
 
</details>

<details>
  <summary><h1>Level 3</h1></summary>

  ## Design & Architecture
  1. [Message Queue 선택 기준 #80](https://github.com/8th-woowacourse-study/level-wiki/discussions/80)
  2. [서버 및 데이터베이스의 기준 시간을 KST와 UTC 중 무엇으로 운영할 것인가 #77](https://github.com/8th-woowacourse-study/level-wiki/discussions/77)
  3. [왜 클린 아키텍처를 이야기할까? #82](https://github.com/8th-woowacourse-study/level-wiki/discussions/82)

  ## AI

  1. [시장에서는 왜 다중 에이전트 시스템(MAS)이 채택되었을까요? #73](https://github.com/8th-woowacourse-study/level-wiki/discussions/73)
  2. [동작하지만 이해하지 못한 코드는 내 코드일까? #74](https://github.com/8th-woowacourse-study/level-wiki/discussions/74)
  3. [AI가 짠 코드, 이해했다고 말할 수 있는 기준은 무엇일까? #75](https://github.com/8th-woowacourse-study/level-wiki/discussions/75)
  4. [AI가 SQL과 매핑을 대신 해주는 시대에도 ORM이 필요한가? #76](https://github.com/8th-woowacourse-study/level-wiki/discussions/76)
  5. [사람에게 좋은 코드가 AI에게도 좋은 코드일까? #83
](https://github.com/8th-woowacourse-study/level-wiki/discussions/83)

## OS

  1. [OS 프로세스 메모리 구조(Stack & Heap)와 스레드 간 메모리 공유 #91](https://github.com/8th-woowacourse-study/level-wiki/discussions/91)

## Design & Architecture
  1. [캐시는 언제, 왜 사용해야 할까? #88](https://github.com/8th-woowacourse-study/level-wiki/discussions/88)
  2. [도커, 도커 컴포즈 알고 써보자~ #89](https://github.com/8th-woowacourse-study/level-wiki/discussions/89)

## FinOps

  1. [우리에게 제공된 AWS 크레딧은 어느정도 자원일까? #90](https://github.com/8th-woowacourse-study/level-wiki/discussions/90)

## Network

  1. [HTTP가 HTTPS로 전환되는 과정 #78](https://github.com/8th-woowacourse-study/level-wiki/discussions/78)
  2. ['동기/비동기'와 '블로킹/논블로킹'의 차이, 확실히 구별하고 계신가요? #81](https://github.com/8th-woowacourse-study/level-wiki/discussions/81)
  3. [로드 밸런싱은 왜 해야할까? #86](https://github.com/8th-woowacourse-study/level-wiki/discussions/86)

## Database

  1. [데이터베이스에서 데드락이 발생하면 어떻게 처리할까? #79](https://github.com/8th-woowacourse-study/level-wiki/discussions/79)
  2. [데이터베이스 락의 종류와 동작 방식 #85](https://github.com/8th-woowacourse-study/level-wiki/discussions/85)
  3. [Uber가 postgresql에서 mysql로 바꾼 이유 #87](https://github.com/8th-woowacourse-study/level-wiki/discussions/87)
  4. [DB 인덱스는 어떻게 동작할까? (B-Tree 탐색 원리와 올바른 활용법) #84](https://github.com/8th-woowacourse-study/level-wiki/discussions/84)

## Java
  1. [JDK 버전 선택 기준 #92](https://github.com/8th-woowacourse-study/level-wiki/discussions/92)
  
</details>

<details>
  <summary><h1>Level 4</h1></summary>

  ## 카테고리
  
  1. [내용](링크)
  2. [내용](링크)

</details>

<details>
  <summary><h1>Level 5</h1></summary>

  ## 카테고리
  
  1. [내용](링크)
  2. [내용](링크)

</details>
