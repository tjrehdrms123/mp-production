# 추억지도(2022.10.24 ~ 2022.11.07)

한 해를 기억하면 추억을 지도에 기록해보세요. 다양한 추억을 기록해 보고 링크를 공유해 자랑해 보세요
<br><br>
## [추억지도 접속하기](https://mp.donggeun.co.kr/map)

<br><br>
# Git Repo
## [Frontend GIT](https://github.com/tjrehdrms123/mp-client)
## [Backend GIT](https://github.com/tjrehdrms123/mp-server)
<br><br>

# 📖 목차 
 - [소개](#소개) 
 - [개발 환경](#개발-환경)
 - [사용 기술](#사용-기술)
 - [아키텍처](#시스템-아키텍처) 
 - [E-R 다이어그램](#e-r-다이어그램)
 - [Api 명세서](#-api-명세서)
 - [릴리즈 노트](#-MP-릴리즈-노트)
 - [화면 구성](#화면-구성)

<br><br>
## 📃소개
**추억지도**는 한 해를 기억하며 다양한 추억을 기록해 친구들과 공유하며 자랑 할 수 있습니다
<br>
참여율을 높이기위해 유저별 지도가 있으며 모든 추억을 볼수있는 지도도 있습니다.


## 개발 환경

![window](https://img.shields.io/badge/windows-%230078D6.svg?&style=flat&logo=windows&logoColor=white")
![vscode](https://img.shields.io/badge/vscode-blue?style=flat&logo=VisualStudioCode)
![github](https://img.shields.io/badge/github-606060?style=fat&logo=github)
![dbeaver](https://img.shields.io/badge/DBeaver-blue?style=flat)

 - Window 
 - Visual Studio Code
 - GitHub
 - DBeaver

## 사용 기술 

![EC2](https://img.shields.io/badge/AWS-ec2-FF8C00?style=flat&logo=amazonec2)
![RDS](https://img.shields.io/badge/AWS-RDS-FF8C00?style=flat&logo=amazonrds)

![express](https://img.shields.io/badge/express-%23000000.svg?&style=flat&logo=express&logoColor=white)
![ParseServer](https://img.shields.io/badge/ParseServer-0078d6?style=flat)
![ParseDashboard](https://img.shields.io/badge/ParseDashboard-0078d6?style=flat)

![React](https://img.shields.io/badge/react-%2361DAFB.svg?&style=flat&logo=react&logoColor=black)
![BootStrap](https://img.shields.io/badge/BootStrap-purple?style=flat&logo=Bootstrap)
![Postgre](https://img.shields.io/badge/postgresql-%23336791.svg?&style=flat&logo=postgresql&logoColor=white)

**웹서버**
 - Nginx

**백엔드**
 - NVM 
 - Node 16.18.0
 - Express
 - ParseServer & ParseDashboard

**프론트엔드**
 -  React
 -  Bootstrap
 
**빌드 툴**
 - Webpack

**데이터베이스**
 - PostgreSQL

**인프라** 
 - AWS EC2
 - Docker
 - Docker Compose

## 시스템 아키텍처
![시스템 아키텍처](./images/system.png)


## 🛠 MP 릴리즈 노트

<details>
<summary> 2022-10-31 MP v1.1.0 릴리즈 보기</summary>
<div markdown="1">   
  <ul>
    <li>이메일 인증 제거</li>
    <li>폰트 변경</li>
    <li>글쓰기 유효성 검사 강화</li>
  </ul>
</div>
</details>
<details>
<summary> 2022-11-05 MP v1.2.0 릴리즈 보기</summary>
<div markdown="1">       
  <ul>
    <li>요청 Body 사이즈 기존 5M > 10M로 변경</li>
    <li>회원가입 여부에 따라 활성화 버튼 변경</li>
    <li>애드핏 광고 1개 > 4개로 변경</li>
  </ul>
</div>
</details>
<br><br>

## 💻화면 구성
![로그인](./images/page/login.png)|![회원가입](./images/page/register.png)|
| :-----------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------: | 
|로그인|회원가입

![전체 추억](./images/page/allmap.png)|![내 추억](./images/page/mymap.png)|
| :-----------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------: | 
|전체 추억|내 추억

![비회원](./images/page/nonuser.png)|![지도 상세](./images/page/mapdetail.png)|
| :-----------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------: | 
|비회원|지도 상세

![추억 남기기](./images/page/mapwrite.png)|![지도 검색하기](./images/page/mapwrite_01.png)|
| :-----------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------: | 
|추억 남기기|지도 검색하기