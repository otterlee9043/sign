# 청중 응답 시스템 Sign

![Apple_iPhone_11_Pro_Max_Presentation](https://github.com/otterlee9043/sign/assets/43086065/d5f2c32b-0438-4a98-89fd-e7f555921185)


## **Github** https://github.com/otterlee9043/sign

## **개발노트**  https://enormous-lime-c78.notion.site/Sign-f46fdfda5ef8493983e70ca025712d7d?pvs=4

**요약 / 서비스 내용**

 청중 응답 시스템 애플리케이션입니다. 코로나로 인해 온라인 수업의 비중이 늘어나면서 생겨난 교수와 학생 간의 의사소통의 불편함을 해소하고자 시작한 서비스입니다. 학생들은 색과 이모지로 자신의 이해도를 표현하면서 비대면 상황에도 적극적으로 수업에 참여하게 되고, 교수는 시각적으로 표현된 학생들의 이해도를 한눈에 즉각적으로 파악하는 것을 목표로 하였습니다.

**주요 기능**

- 방 생성 및 방 코드 검색
- 입장한 방에서 좌석 선택, 색과 이모지 선택
- 같은 줄에 앉은 사람들간의 채팅

**역할**

- 2021.08 ~ 2021.12
    - ‘공학프로젝트기획’ 수업의 프로젝트
    - 팀 리더로서 팀원 3명과 함께한 팀 프로젝트
    - 서비스 기획 및 Flask로 프로토타입 구현
- 2023.05 ~ 2023.09
    - 서비스 기획 내용을 토대로 Spring boot와 React 프레임워크 이용하여 새로 구현

**사용 기술 및 도구**

Spring Boot, React, MariaDB, AWS EC2, ECS, Docker, Nginx

**개발 내용**

- REST API 설계 및 개발
- JWT를 이용한 인증
- 소셜 로그인과 자체 로그인 구현
- 서버/클라이언트 검증 구현
- WebSocket과 STOMP 이용한 메시징
- ECS와 로드 밸런서를 이용한 무중단 배포
- Github Actions 이용한 자동 배포화

**서비스 화면**

- 회원가입

    [screen-recording_(7).webm](https://github.com/otterlee9043/sign/assets/43086065/b1f2dd9d-efe0-4931-9236-49fa8facf20b)


- 소셜 로그인
    
    [screen-recording (6).webm](https://github.com/otterlee9043/sign/assets/43086065/2ccf44f4-caf2-4181-ae08-8f47721e07f8)
    

- 방 생성
    
    [screen-recording (4).webm](https://github.com/otterlee9043/sign/assets/43086065/5026572f-42ad-49d5-8630-70a70fea1e4d)
    

- 방 참여
    
    [screen-recording (5).webm](https://github.com/otterlee9043/sign/assets/43086065/8d5282ea-8520-4a1c-9e8e-81f279e125d5)
    

- 이해도 표현 기능
    
    [screen-recording (2).webm](https://github.com/otterlee9043/sign/assets/43086065/d02d487d-a11e-480f-918b-31776e0841d8)
  

- 채팅방
    
    [screen-recording (3).webm](https://github.com/otterlee9043/sign/assets/43086065/c0d9afe4-b78f-401e-b596-e62856731544)
    

## 시스템 아키텍처

![Sign 시스템 아키텍처](https://github.com/otterlee9043/sign/assets/43086065/bc52bb45-382d-4b58-bf15-d4a863781e87)

### CI/CD

![Sign_CICD](https://github.com/otterlee9043/sign/assets/43086065/ef12db41-dab9-48ef-81c1-c9b01a3c1d7c)

## 데이터베이스 설계 및 ERD

![sign_ERD](https://github.com/otterlee9043/sign/assets/43086065/046f9ed2-8ad8-40f9-8653-bbf3211f7b6b)


### REST API 디자인

