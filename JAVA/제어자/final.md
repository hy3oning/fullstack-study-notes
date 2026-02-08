 1. final 필드 -값변경 불가
 2. final 지역변수 -값변경 불가
 3. final 메서드 -상속시 [[Overriding|override]]불가
 4. final 클래스 -상속 자체 불가

==처음 지정된 값을 바꿀 수 없음==


| 대상              | 메모리 위치                             | 의미       |
| --------------- | ---------------------------------- | -------- |
| final 지역변수      | [[스택영역 (stack)]]                   | 재할당 불가   |
| final 매개변수      | [[스택영역 (stack)]]                   | 값 변경 불가  |
| final 인스턴스 변수   | [[힙영역 (heap)]]                     | 객체마다 고정값 |
| static final 변수 | [[메서드영역 (method)]] / Constant Pool | 클래스 상수   |
| final 참조변수      | Stack(참조) + Heap(객체)               | 참조 고정    |
| final 메서드       | [[메서드영역 (method)]]                 | 오버라이딩 금지 |
| final 클래스       | [[메서드영역 (method)]]                 | 상속 금지    |
