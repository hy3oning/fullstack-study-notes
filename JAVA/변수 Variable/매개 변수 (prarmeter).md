==메서드 호출 시 '전달하는 값'을 가지고 있는 변수. (지역 변수처럼 선언된 곳부터 수행이 끝날 때까지 유효함)==

ex)

	int sum;
	sum = add(1,2); #1 add메서드 호출하면서 1,2값 전달
		            #5 리턴값 c 값이 int sum에 저장
	systme.out.print(sum); #6 sum에 저장된 값 3이 출력됨 
	
	static int add(int a, b){ #2 정수(1,2)를 int로 받아줌
	int c = a+b; #3 수행
	return c; #4 수행 끝나고 리턴 값 c를 가지고 호출한 곳으로 돌아감
	}


>[!important]
>[[스택영역 (stack)]]에 저장됨

