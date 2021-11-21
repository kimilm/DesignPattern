## 컴포짓 패턴

그룹 전체와 개별 객체를 동일하게 처리할 수 있도록 하는 패턴

장점
- 복잡한 트리 구조를 편리하게 사용할 수 있다
- 다형성과 재귀를 사용할 수 있다
- 클라이언트 코드를 변경하지 않고 새로운 엘리먼트 타입을 추가할 수 있다


단점
- 트리를 만들어야 하기 때문에 (공통된 인터페이스를 정의해야하기 때문에) 지나치게 일반화를 해야하는 경우가 생길 수도 있다
  - 너무 과한 일반화를 적용하다보면 런타임시에 타입 체크가 필요할 때도 있는데 이때는 정말 컴포짓 패턴을 적용하는 것이 맞는지 다시 한 번 고민해볼 필요가 있다