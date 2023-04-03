# :speaker: Auction <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white"><img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"><img src="https://img.shields.io/badge/Socker.io-010101?style=for-the-badge&logo=Socker.io&logoColor=white">
## :tada: Node.js와 MySQL을 활용한 실시간 경매 시스템
Node.js와 MySQL을 활용한 실시간 경매 시스템 <br>
2023.03.31-2023.03.31 (1차 완성) <br>

<img src="https://user-images.githubusercontent.com/119637883/229034068-6a35dcb4-6430-4a17-abfc-154f6d3304be.PNG"/> <br>

<img src="https://user-images.githubusercontent.com/119637883/229034095-cd2651ca-cb7f-4b04-9388-fb09632c5d59.PNG"/> <br>

<img src="https://user-images.githubusercontent.com/119637883/229034092-5e999f55-813c-4251-8174-88af45b210bf.PNG"/>

***

### :computer: 개발 환경 및 기술 세부 스택
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white"><img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"><img src="https://img.shields.io/badge/Socker.io-010101?style=for-the-badge&logo=Socker.io&logoColor=white"><img src="https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white"><img src="https://img.shields.io/badge/Passport-34E27A?style=for-the-badge&logo=Passport&logoColor=white"><img src="https://img.shields.io/badge/Nunjucks-1C4913?style=for-the-badge&logo=Nunjucks&logoColor=white"><img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=for-the-badge&logo=Visual Studio Code&logoColor=white"> <br>
* Node.js
* MySQL
* Web Socket
* SSE
* Sequlieze
* Passport
* Nunjucks
* VSC

***

### :wrench: 핵심 기능
#### 유저
* 로그인, 로그아웃 기능
* 경매 상품 등록 기능
* 입찰 기능
* 낙찰 기능

***

### :bookmark: 코드 설명
추가 예정

***

### :adhesive_bandage: 이슈 관리 및 업데이트
* 업데이트 할 기능
  * 상품 등록자의 참여 방지
  * 경매 시간 조정 기능
  * 노드 서버가 꺼졌을 때의 대처 방안 생각하기

***

### :bell: 프로젝트 회고
* 웹 소켓과 SSE의 차이에 대해 알게 되었고, 프로젝트 내에서의 역할도 나누어 사용할 수 있었다.
* 로그아웃 기능이 구동되지 않아 애먹었는데, passport 미들웨어의 버전이 상향되며 req.logout()에 콜백 함수를 사용해야 한다는 것을 알게 되었다.
