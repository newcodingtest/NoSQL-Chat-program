
## 사용 툴
#### 1. Spring boot 2.5.6
#### 2. Mongo DB
#### 3. 인텔리제이

### SSE 프로토콜을 이용한 채팅서버 구현
![image](https://user-images.githubusercontent.com/57785267/142211705-b021c8e5-0a34-4b6b-9e34-10d620548e7d.png)

* 몽고 DB 사용법

`CMD 접속`

`
MONGO
`
몽고db 접속

`USE CHAT
`
chat db 사용 

`db.chat.find().pretty();
`
몽고db내에 있는 데이터들 출력

`db.runCommand({convertToCapped: 'chat', size:8192});`
db버퍼사이즈 8192 설정
