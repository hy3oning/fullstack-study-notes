 - 모든 필드가 ==public [[Static]] [[final]] ==로 정의
 - 모든 메서드가 ==public [[추상메서드 (abstract method)]]==로 정의(디폴트메서드 제외)
 - 디폴트 메서드는 public으로 정의
 - 자체적으로 객체생성 불가

콘센트로 비유하자면 콘센트에 꼽히는 가전제품이 TV인지 냉장고인지 중요하지 않음.
	여기에 플러그가 꼽히는 가전제품이면 종류에 상관없이 사용할수있음 
	=
	이 인터페이스를 충족하면 사용할 수 있음

인터페이스의 정의

	interface A {
		public static final int a = 3;
		public abstract void abc(); //추상메서드는 {}가 없음
	}
	int a = 3; //디폴트가 public static final
	void abc(); //디폴트가 public abstract


>[!important]
>⭐상속시 implements 사용
>⭐==다중 상속 가능==
>	일반클래스, 추상클래스는 다중상속 불가

>[!warning]
>인터페이스가 클래스를 상속할 수 없는 이유는?
>⭐==모호성이 생기기 때문이다.==
>인터페이스가 구현을 가지지 않는 계약이라는 설계 원칙을 지키기 위해서이다.





