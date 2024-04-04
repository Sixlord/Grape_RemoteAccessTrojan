# Grape_RemoteAccessTrojan
Grape_RemoteAccessTrojan
----------------------------------------------------------------------------------------------------
도커 생성
![도커 생성](https://github.com/Sixlord/Grape_RemoteAccessTrojan/assets/157137422/cc40aa67-36ea-445a-a02e-3bad238cd1a5)

RAT 실습
![rat 실습](https://github.com/Sixlord/Grape_RemoteAccessTrojan/assets/157137422/dd420210-506c-46fb-b97c-a4eaa8296edd)

---------------------------------------------------------------------------------------------------

### 트로이목마(Trojan)

: 다른 컴퓨터에서 몰래 실행되면서, 악의적인 행동을 하는 컴퓨터 프로그램

→ 원격 접속 트로이목마(Remote Access Trojan, RAT)

### 공격자(Attacker) / 피해자(Victim)

### C&C서버

: C&C or C2, Command and Control, RAT를 이용해 피해자의 컴퓨터에 원격 접속하여 조종하는 공격자의 서버

### Payload

: 내용물, 해킹에서는 악성행위에 쓰이는 데이터를 뜻함 

### 지속성(Persistance)

: 악성코드가 계속해서 실행되도록 함, 악성 행위가 끊기지 않도록 방지하는 해킹 기술

### 폴링(Polling)

: 상태를 주기적으로 검사하는 것

### 리눅스 백그라운드 실행 명령어

- 명령어 뒤에 & 붙이면 백그라운드 실행
- nohup 맨 앞에 붙이면 유저 로그아웃해도 실행

→ ex) nohup python3 payload.py &

→ ps 명령어로 pid 입력해서 수동으로 종료
