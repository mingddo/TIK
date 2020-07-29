07.22

1. 함수 기본 문법

   * 함수의 선언은 `def`로 시작

   * 함수의 값은 ` return`으로 결과 값을 전달한다. (return을 입력하지 않을 경우 None이 반환된다.)

   * ! 주의! `pirnt()` , `sort()` 와 같은 몇 몇 함수는 return 값이 없다( None)

   * ```  python
     result = print(c)
     print(result)
     #### 결과 값은 'None'이 나옴
     ```

   * 파이썬 내장함수의 종류 조회 : ``` dir(__builtins__)``` 

2. 함수의 변수

   * 매개변수( parameter)의 경우 함수의 정의 시점에서, 전달인자( argument)는 함수의 호출 시점에서 사용됨
   * ```def sum(a, b = '')``` 이와 같이 변수에 초기값을 줄 수 있음 (아무것도 입력하지 않았을 경우, 해당 초기값을 반환함.)이를 기본 인자 값이라고 함
   * !주의! 기본 값이 있는 인자 다음에는 기본값이 없는 인자는 사용할 수 없음 (기본 인자값이있는 인자가 무조건 뒤에 오거나 모든 인자가 다 기본값을 가져야함)
   * 가변인자 리스트는 입력할 인자의 개수가 정해지지 않았을 경우에 사용함 (* args)
   * 가변 키워드 인자는 (** kwarg) - 인자들은  dictionary처리가 되어 사용됨
   * !주의! 키워드 인자 사용 시 ```name (a = 'b')``` 형식으로 함수를 호출할 때 a의 자리는 `' '`를 사용하지 않고 그냥 입력한다.(이 자리는 문자열이 들어가면 안됨)

3. 함수와 스코프
   * 이름공간(namespace)- `LEGB rule` 
   * local scope > enclosed scope > global scope > builtin scope 순으로 이름을 찾아감.
4. 재귀함수
   
   * 최대 재귀 깊이는 1,000으로 정해져 있음.

5.  리스트가 비어있거나   True/ False로 코드 짤 때 

   if not i :( 비어있다는 뜻)

   for True/False (조건을 붙이기 애매할 때 사용 ) 단, 반드시 빠져나가는   break 나 return 을 사용해줘야함

   

   