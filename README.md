# 2018년 1학기 공개 sw 4조 RolyPoly
# Project : phaser 3 와 node.js를 이용한 웹게임 개발
오픈소스 HTML5 게임 프레임워크 Phaser 3 와 Node.js, Socket.io 를 이용한 멀티플레이가 가능한 웹 게임의 개발 과 무료 호스팅 서비스 Heroku 를 배포

## 팀원
김인제(팀장, 게임 기획 및 개발) 2014112049 helios789@naver.com

김형우(서버 개발) 2014112048 hwjw9599@naver.com

장현석(웹 Front End 개발 및 호스팅) 2014112067 gustjr1259@dongguk.edu

## 프로젝트 설명
오픈소스 HTML5 게임 프레임워크 인 Phaser 3 를 이용하여 웹 브라우저에서 접속만으로 실행할 수 있는 웹 게임을 개발
Node.js 와 Socket.io 를 이용하여 플레이어 간 실시간 데이터 통신을 통한 멀티플레이 게임으로의 확장
저희가 사용한 오픈소스는 (https://github.com/CSID-DGU/2017-2-OSSP-Awesome-1)을 사용하였습니다.

라이센스 : MIT License

문의 : 김인제(Phaser3 Game)

##실행 방법
실제 게임 플레이(호스팅) : https://phaser-hosting.herokuapp.com/main으로 접속하여 mirty or solo button 클릭
사방에서 오는 적 패턴을 피해 살아남는 dodge 게임

게임 서버 생성(로컬 호스팅) : server.js파일 컴파일 후 로컬호스트 서버로 접속 후 위와 동일하게 진행

1.서버 접속

2.solo or multi 버튼 클릭

3-1. solo클릭시 실행되는 게임 진행

3-2. mirty클릭시 다른 플레이어가 들오올때 까지 대기

4.다른 플레이어 모두 방에 접속시 4번째 player가 start버튼을 누르면 게임 진행
  

