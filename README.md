## 영어 학습 단어 사이트 LEWA(Learning English with Article)
2020년 1학기 상명대학교 스터디 상생플러스의 개발 프로젝트 repository입니다.   
Javascript 기반 Web/Mobile application 개발 플랫폼 Meteor를 이용하여 영어기사를 보며 영단어를 학습할 수 있는 웹사이트 개발   
<br/><br/>
[Meteor](https://www.meteor.com/)
<br/>
html, css, javascript  
Node.js, npm  
mongoDB  
## Application sample
<img src="https://user-images.githubusercontent.com/60168680/92593185-a2b8c880-f2db-11ea-8a4d-2a3151ff9a19.png">
<img src="https://user-images.githubusercontent.com/60168680/92593509-2d99c300-f2dc-11ea-91de-113f61d8f6eb.png">
<img src="https://user-images.githubusercontent.com/60168680/92593552-3ee2cf80-f2dc-11ea-92b5-f36180fb7081.png">
<img src="https://user-images.githubusercontent.com/60168680/92593592-56ba5380-f2dc-11ea-82b9-959a00580058.png">
<img src="https://user-images.githubusercontent.com/60168680/92593842-c2042580-f2dc-11ea-9211-1ca67cbd878c.png">
<img src="https://user-images.githubusercontent.com/60168680/92593862-cf211480-f2dc-11ea-8a29-28383cf45143.png">
<img src="https://user-images.githubusercontent.com/60168680/92593968-ff68b300-f2dc-11ea-9e63-f5c14ab3b23c.png">
<img src="https://user-images.githubusercontent.com/60168680/92594113-48206c00-f2dd-11ea-8726-dbd9dc38db35.png">
<img src="https://user-images.githubusercontent.com/60168680/92594785-42775600-f2de-11ea-87f2-bb39a7410713.png">
<img src="https://user-images.githubusercontent.com/60168680/92594816-5327cc00-f2de-11ea-899f-0fc0ef14f634.png">
<img src="https://user-images.githubusercontent.com/60168680/92594532-de549200-f2dd-11ea-94c7-d9550957b4a1.png">
<img src="https://user-images.githubusercontent.com/60168680/92594746-325f7680-f2de-11ea-8cdd-43b0e0aa26a6.png">
<img src="https://user-images.githubusercontent.com/60168680/92594485-cb41c200-f2dd-11ea-88b3-ae7c72be1ce3.png">
<img src="https://user-images.githubusercontent.com/60168680/92594439-bcf3a600-f2dd-11ea-8caf-7a62c5d19ec1.png">

## Run Project
#### install meteor
* [미티어 설치](https://www.meteor.com/install)
#### npm install (최초 1회 실행)
```
meteor npm install
```
#### run
```
meteor
```
* 실행 후 웹브라우저에서 localhost:3000 접속  (```meteor run --port <port number>```로 포트번호 지정 가능)
* Sign up 또는 Login. admire@gmail.com으로 signup하면 관리자 계정임
* localhost:3000/postingAuto에서
[The Korea Herald](http://www.koreaherald.com/index.php) 기사의 링크를 scraping한 후 upload하여 기사 업로드 가능

## Document
* [페이지 구성](/docs/client_structure.md)
* [DB 구조](/docs/DB_collection.md)
* [추가한 package](/docs/npm_install.md)

## Project Structure
* Client : 화면 구성 모음
* docs : 정리한 문서 모음
* public : 사진 파일 등 모음
* server : 백엔드 관련
* lib : html HEAD, 라이브러리, 함수 등..  

