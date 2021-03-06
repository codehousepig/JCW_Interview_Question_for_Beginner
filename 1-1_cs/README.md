# Part 1-1 Development common sense
- [객체 지향 프로그래밍이란 무엇인가](#object-oriented-programming)
  - 객체 지향 개발 원칙은 무엇인가?

## Object Oriented Programming
- 1줄: 독립적인 객체들의 집합을 통하여 전체 프로그램이 객체들의 상호작용 구조로 구현될 수 있도록 하는 것. <br>
- 추가설명

### 객체 지향적 설계 원칙
1. SRP(Single Responsibility Principle) : 단일 책임 원칙 <br>
클래스는 단 하나의 책임을 가져야 하며 클래스를 변경하는 이유는 단 하나의 이유이어야 한다.
2. OCP(Open-Closed Principle) : 개방-폐쇄 원칙 <br>
확장에는 열려 있어야 하고 변경에는 닫혀 있어야 한다.
3. LSP(Liskov Substitution Principle) : 리스코프 치환 원칙 <br>
상위 타입의 객체를 하위 타입의 객체로 치환해도 상위 타입을 사용하는 프로그램은 정상적으로 동작해야 한다.
4. ISP(Interface Segregation Principle) : 인터페이스 분리 원칙 <br>
인터페이스는 그 인터페이스를 사용하는 클라이언트를 기준으로 분리해야 한다.
5. DIP(Dependency Inversion Principle) : 의존 역전 원칙 <br>
고수준 모듈은 저수준 모듈의 구현에 의존해서는 안된다.
