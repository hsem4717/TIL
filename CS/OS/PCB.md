# 프로세스 제어 블록(PCB)

> 프로세스를 실행하는 데 필요한 중요한 정보를 보관하는 자료 구조

**구성**

- 포인터 : 준비 상태나 대기 상태의 큐를 구현할 때 사용  -  대기 상태 큐에서는 같은 입출력을 요구한 프로세스끼리 연결할 때 포인터 사용
- 프로세스 상태 ( 생성, 준비, 실행, 대기.. )
- 프로세스 구분자 ( pid )
- 프로그램 카운터 ( 다음에 실행될 명령어의 위치 )
- 프로세스 우선순위 - 프로세스의 실행 순서를 결정하는 우선순위
- 각종 레지스터 정보 - 레지스터의 값
- 메모리 관리 정보 - 메모리 위치 정보, 경계 레지스터 값과 한계 레지스터 값 등
- 할당된 자원 정보 - 입출력 자원이나 오픈 파일 등에 대한 정보
- 계정 정보 - 계정 번호, CPU 할당 시간, CPU 사용 시간 등
- 부모 프로세스 구분자와 자식 프로세스 구분자 - 부모 프로세스를 가리키는 PPID(Parent)와 자식 프로세스를 가리키는 CPID(Child) 정보
