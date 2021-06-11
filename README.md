# MyTube 📺


쌓여만 가는 유튜브 구독 채널들!   어떻게 관리하시나요?   
이제는 음악, 운동, 요리, 먹방 등 **카테고리별로 나누어 관리하세요!**   
http://firstquarter.shop/

<br>

## 1. 제작 기간 & 팀원 소개
- 2021년 6월 7일 ~ 2021년 6월 10일
- 4인 1조 팀 프로젝트
  + 양다현 : 카테고리 CRD
  + 양현정 : 전체페이지 CSS
  + 장상현 : 로그인 + 회원가입
  + 최민서 : 유튜브 채널 CRUD

<br>

## 2. 사용 기술
`Back-end`
- Python 3
- Flask 2.0.1
- MongoDB 4.4

`Front-end`
- JQuery 3.5.1
- Bulma 0.9.2

`deploy`
- AWS EC2 (Ubuntu 18.04 LTS)

<br>

## 3. 실행화면

<img src="https://user-images.githubusercontent.com/70243735/121630462-2ba5a000-cab8-11eb-8434-5ac030a5229c.gif">
자세한 영상 : https://youtu.be/K7LGtKgeIMI

<br>

## 4. 핵심기능

+ **로그인, 회원가입**   
  : JWT를 이용하여 로그인과 회원가입을 구현하였습니다.   
  : 아이디와 닉네임의 중복확인이 가능합니다.    

+ **카테고리 CRD**   
  : JWT를 사용하여 사용자별 카테고리의 유튜브 채널을 조회합니다   

+ **유튜브 채널 CRUD**   
  : JWT를 사용하여 사용자별 카테고리의 유튜브 채널을 조회합니다   
  : youtube 채널 url을 입력하면 채널의 프로필 이미지, 채널명, url을 웹스크래핑합니다.   
  : mongoDB의 '_id' 를 이용하여 수정, 삭제합니다.   

<br>

## 5. 개인 회고
