  # 02-3-2. TypeChange

<h3>자동 타입 변환(promotion)</h3>

허용 범위가 작은 타입이 큰 타입으로 저장될 때 발생   
메소드를 호출할때 많이 발생   

범위의 크기 순  
byte < short < int < float < double

![화면 캡처 2022-07-16 191920](https://user-images.githubusercontent.com/102217688/179350837-78223199-c658-4504-bb73-e314c119fb05.png)

자식 클래스는 부모타입으로 자동 타입 변환이 가능하다

<h3>강제 타입 변환(casting)</h3>

큰 허용 범위 타입을 작은 단위로 강제로 나눠서 저장하는 것   
자식 객체가 부모 타입으로 변환된 상태에서 다시 원래로 변환하려 할때 캐스팅() 연산자를 사용해 강제 타입 변환 가능


![화면 캡처 2022-07-16 192729](https://user-images.githubusercontent.com/102217688/179351179-04305f5f-788e-43df-b997-3737e7ed43c7.png)
