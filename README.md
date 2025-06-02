# Educat

> AI 디지털 교과서 보조

---

## 📑 목차
1. [📋 프로젝트 소개](#-프로젝트-소개)
2. [🚀 주요 기능](#-주요-기능)
3. [🛠️ 기술 스택](#-기술-스택)
4. [📂 프로젝트 구조](#-프로젝트-구조)
5. [👨‍👩‍👧‍👦 팀원 정보](#-팀원-정보)

---

## 📋 프로젝트 소개
> 

### 메인페이지
![mainpage](GIF/mainpage.gif)
---

## 🚀 주요 기능

---

## 🛠️ 기술 스택

### 💻 프론트엔드
![React](https://img.shields.io/badge/react-%230db7ed.svg?style=for-the-badge&logo=react&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![Axios](https://img.shields.io/badge/axios-%23663399.svg?style=for-the-badge&logo=axios&logoColor=)


### ⚙️ 백엔드
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![SpringBoot](https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=Spring&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white)
![YAML](https://img.shields.io/badge/yaml-black.svg?style=for-the-badge&logo=yaml&logoColor=white)

### 🗄️ 데이터베이스
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Amazon S3](https://img.shields.io/badge/Amazon%20S3-FF9900?style=for-the-badge&logo=amazons3&logoColor=white)


### 👊 협업 툴
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![KakaoTalk](https://img.shields.io/badge/kakaotalk-ffcd00.svg?style=for-the-badge&logo=kakaotalk&logoColor=000000)

---

## 📂 프로젝트 구조

### 📦 프론트엔드
```bash
src/
├── assets/         # 이미지, 폰트 등 정적 파일
├── components/     # 재사용 가능한 컴포넌트
└── pages/          # 유틸리티 함수
```

### 🖥️ 백엔드
1. Spring Boot
```bash
src/
├── Appication/       # 서비스
├── Auth/             # 서비스
├── aspects/          # AOP 설정 (로깅)
├── config/           # 애플리케이션 설정 파일
├── controller/       # REST API 요청을 처리하는 컨트롤러
│   ├── request/      # 요청(Request) DTO 관리
│   ├── response/     # 응답(Response) DTO 관리
├── model/            # 비즈니스 로직과 관련된 데이터 모델
    ├── entity/       # JPA 엔티티 클래스 (DB 테이블 매핑)
    └── repository/   # 데이터베이스 CRUD를 위한 Repository 인터페이스
```
2. Flask
```bash
Contents_recommend_system/
├── .git/                     # Git 버전 관리 폴더
├── __pycache__/              # Python 컴파일된 바이트코드 캐시
├── database/                 # 데이터베이스 관련 파일들
├── recommendation/           # 추천 알고리즘 관련 모듈
├── recommenddation/          # 추천 시스템 추가 모듈 (폴더명 오타로 보임)
├── app.py                    # Flask 메인 애플리케이션 파일 (793행, 1,723자)
├── gcn_model_weights.pth     # PyTorch GCN 모델 가중치 (4,739KB, 6,368자)
├── README.md                 # 프로젝트 설명서 (96행, 110자)
└── schema.sql                # 데이터베이스 스키마 정의 (343행, 819자)
```

### 🏗️ 아키텍처


### 📚 ERD


---

## 👨‍👩‍👧‍👦 팀원 정보

| 🧑‍💻 **이름**    | 🏆 **역할**        |
|:----------------:|:-----------------:|
| **전승기**       | 팀장, 백엔드 |
| **정채연**       | 프론트 개발자     |
| **권상웅**       | 프론트 개발자     |
| **이기창**       | AI 개발자 |


## 🛠 담당 파트  

### 전승기  
- **백엔드**
  - 교과서 데이터 크롤링 및 수집
  - JWT 인증, 인가
  - 전체적인 스프링 백엔드 서비스

### 정채연  
- **프론트엔드 개발**  
  - 디자인 및 퍼블리싱

### 권상웅  
- **프론트엔드 개발**  
  - 퍼블리싱 및 api 연동
  - ai 서버 연동동
  - 
### 이기창  
- **AI 개발**
  - 협업 필터링을 통한 AI 추천시스템 개발


### 공통 파트
- 기획, 요구사항 명세서, ERD구성, API 명세서

---

# 기능 시연


---

