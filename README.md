# Day1 

Notion DashBoard : https://www.notion.so/Project-2-edf85dd05b1946128cfa7a50cb4d9a0e
Trello DashBoard : https://trello.com/b/Gv3E8isJ/project-2

Team : Baek, Jang, Choi

1) Setting Data Schema
Index.html
- User
- - Join
- - Login 
- - Welcome
- - Mypage

- Board
- - Write
- - View
- - List
- - Delete

2) Axios Setting Page
- Get
1) check/?userid 
2) check/?nickname
3) /${categoryMain}
4) /${categoryMain}/view/:id
5) /${categorysub}
6) /${categorysub}/view/:id


- Post
1) /${categoryMain}
2) /${categorySub}

- Put
1) /${categoryMain}/view/:id
2) /${categorysub}/view/:id

- Delete
1) /${categoryMain}/view/:id
2) /${categorySub}/view/:id


Day 1 Completed 
1) Data Schema 구성 및 설계
2) DB Table Initial 및 Field 초안 작성
3) HTML Template (Layout) 작성
4) Index Page Desion
5) Login/Join Page Design

Day 2 Will be update
1) HTML Page 1차 작성 완료
2) Backend Defaults Setting / FrontEnd 영역 분배
3) Backend & Frontend Initial 예정

Day 1 Isuse / Wiki
1) Data Schema 관계도 설정
- DB 간 PK / FK 설정시 중복값 및 연계값 중복
- Categories 설정시 데이터 중복 저장으로 인한 DB 효율성 저하 Issue 발생

2) Index Layout 불러오기 사용시 올바르게 가져와지지 않음
- Template Code Block/End Point setting error 로 인해 올바르게 가져와지지 않음
- Block Content / endpoint 설정시 맞춤법 주의

