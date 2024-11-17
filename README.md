# :seedling: Kinderpia 
## 프로젝트 소개

<img src="https://github.com/user-attachments/assets/2e8335b5-e8ac-4dd1-8b1e-694fb065656a"></img>


* 주제 : 부모와 아이들이 함께할 공간을 소개하며, 모임을 만들어 함께 할 수 있는 웹 페이지
* 기획 의도 : 단순한 서울시 공간 소개를 넘어 서로의 경험을 나누며 소통할 수 있는 네트워크 서비스를 제공하고자 한다.

* 기간 : 2024.10.21 ~ 2024.11.08(3주)
* 배포 주소 : http://ec2-3-38-150-41.ap-northeast-2.compute.amazonaws.com/
  * Test ID: test3859
  * Test Password: test1234

<br>

## :raising_hand: Backend Developers
#### 김어진 [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/qldirr)
- 유저, 관리자, AWS S3 사용하여 이미지 업로드 구현

#### 석원준 [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/ymind14563)
- 채팅, 신고, 파이프라인 자동화 구축
- **서버 배포**: AWS (EC2, RDS, S3), NGINX

#### 유예진 [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/yjyoo6831)
- 장소 검색, 리뷰 CRUD
#### 윤예슬 [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/errorose)
- 모임 CRUD

<br>

## 🧰 Architecture

#### Languages

<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/sass-CC6699?style=for-the-badge&logo=sass&logoColor=white"> <img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white">

#### Frameworks

<img src="https://img.shields.io/badge/nodedotjs-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white"> <img src="https://img.shields.io/badge/express-000000?style=for-the-badge&logo=express&logoColor=white"> <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=white">

#### Libraries

<img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white"> <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white"> <img src="https://img.shields.io/badge/multer-F46519?style=for-the-badge&logo=multer&logoColor=white"> <img src="https://img.shields.io/badge/redux-764ABC?style=for-the-badge&logo=redux&logoColor=white"> <img src="https://img.shields.io/badge/winston-000000?style=for-the-badge&logo=winston&logoColor=white"> <img src="https://img.shields.io/badge/sequelize-52B0E7?style=for-the-badge&logo=sequelize&logoColor=white">

#### Databases

<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">

#### Deployment

<img src="https://img.shields.io/badge/amazonwebservices-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white"> <img src="https://img.shields.io/badge/amazonec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white"> <img src="https://img.shields.io/badge/amazons3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"> <img src="https://img.shields.io/badge/amazonrds-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white"> <img src="https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"> <img src="https://img.shields.io/badge/pm2-2B037A?style=for-the-badge&logo=pm2&logoColor=white">

#### Development Environment and Tool

<img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white"> <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"> <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"> <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white">

#### Communication Tools

<img src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"> <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
<br>
Backend

Java 17
Spring Boot 3.3.4
Spring Security
Spring Data JPA
Spring WebSocket
Spring Cloud AWS 2.2.6
Spring Data Redis

Database

MySQL 8.0.33
Redis

Documentation

Springdoc OpenAPI (Swagger) 1.6.14

Dependencies

Lombok
JJWT 0.9.1
JAXB API 2.3.1

Build Tool

Gradle

Communication

WebSocket
STOMP
Spring Messaging

## ❓ 주요 기술 채택 이유
- **Spring Boot** : 모듈화된 아키텍처를 제공하며, 의존성 주입(Dependency Injection)같은 프로그래밍 패턴을 이해하고 많은 예제 및 라이브러리 사용을 위함.
- **Spring Security** : Spring Security와 통합되어 있어, 인증 및 권한 부여에 강력한 기능을 제공하기 위해 채택
- **JPA** : 객체 간 관계를 매핑해 복잡한 연관 관계도 손쉽게 관리할 수 있어 유지보수 편리성을 위해 채택
- **JWT** (JSON Web Token) : 보안 및 서버의 부하를 줄이고, 확장성을 높이기 위해 채택
- **Socket.io** : 채팅 기능을 위해 실시간 양방향 통신이 가능하고, 다양한 이벤트를 쉽게 처리하기 위해 채택
- **Multipart** : AWS 서버에 파일을 업로드하여 서버의 저장 공간 절약 및 파일 관리의 용이성과 파일 형식 및 크기 제한을 위해 채택
- **AWS** : 현재 클라우드 시장에서 가장 큰 점유율을 차지하고 있으며, EC2, S3, RDS 등 다양한 서비스를 지원하고, 자원을 확대/축소 하는 등 유연성의 이점으로 인해 채택
- **Jenkins** : 코드의 자동 빌드 및 배포 프로세스를 수행하여 버전관리의 용이 및 유지보수성 향상을 위함.

<br>

## 👩‍💻 팀내 역할

<br>

## 주요 페이지 소개 

## 메인 페이지 
![메인페이지](https://github.com/user-attachments/assets/9654fd23-52f6-41aa-ae93-e66270675524)

## 장소 상세 페이지 
![장소상세](https://github.com/user-attachments/assets/018f3597-96fb-42a3-904a-5df0868e843c)

## 장소 검색 페이지 
![장소검색](https://github.com/user-attachments/assets/ab79221d-8107-4ca7-bcde-d2f1a07efaee)

