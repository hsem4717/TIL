# 05-4. Access Modifier

<h3>접근 제한자</h3>

![wqjrms](https://user-images.githubusercontent.com/102217688/179446277-83d08390-1298-4f93-9b88-22d53912d7c0.png)

`public`-모든 패키지, 제한없이 생성자 호출   
`protected`-같은패키지의 클래스에서 생상자 호출, 해당클래스의 자식 클래스라면 생성자 호출 가능   
`default`-같은패키지에서만 생성자 호출   
`privated`-생성자 호출 불가, 클래스 내부에서만 가능   

<h3>외부에서 private 사용법</h3>

![aasd](https://user-images.githubusercontent.com/102217688/193393817-6c8d2731-3d33-445f-b2e4-0dca27a837c5.png)

set로 클래스 안에서 private의 값 변경 후 get으로 값 반환

게터 세터 명명법
- get또는set + 필드명

