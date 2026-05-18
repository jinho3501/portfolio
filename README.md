# 👋 안녕하세요, 진호(Jinho)입니다

> **데이터로 검증하고 코드로 풀어내는** Flutter · iOS 모바일 개발자

<p align="left">
  <img src="https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white" alt="Flutter"/>
  <img src="https://img.shields.io/badge/Swift-F05138?logo=swift&logoColor=white" alt="Swift"/>
  <img src="https://img.shields.io/badge/SwiftUI-007AFF?logo=swift&logoColor=white" alt="SwiftUI"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white" alt="Dart"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black" alt="Firebase"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/AWS-FF9900?logo=amazonaws&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python"/>
</p>

---

## 🙋 About Me

- 🎓 **LG전자 DX School 1기** 수료 (Team. 바잇킹 — RunInk 프로젝트)
- 💻 **Flutter / SwiftUI** 모바일 개발 + **FastAPI / Firebase** 백엔드 경험
- 📊 SNS 3만 건 크롤링 → NLP 토픽 모델링 → PCA·계층 클러스터링까지 **데이터 기반 사고**
- 🚀 **App Store 출시 경험** (ChuckChuck v1.0 → v1.1)
- 🛠 Flutter 30개 화면 + 자체 백엔드(FastAPI + AWS EC2/S3/RDS) **풀스택 운영 경험**

> 추가 학력·경력 정보는 [📑 포트폴리오 PDF](포트폴리오(임진호).pdf)에서 확인하실 수 있습니다.

---

## 🌟 Featured Projects

### 🏃 [RunInk — GPS 아트 러닝 앱](https://github.com/jinho3501/Runink)

> **사진 한 장으로 사용자 위치 기반 GPS 아트 러닝 경로를 자동 생성**하는 풀스택 모바일 서비스
> LG전자 DX School 1기 바잇킹 팀 프로젝트 (4인)

<p>
  <img src="https://img.shields.io/badge/Flutter-3.5-02569B?logo=flutter&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-Backend-009688?logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-EC2%20·%20S3%20·%20RDS-FF9900?logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Firebase-Auth-FFCA28?logo=firebase&logoColor=black"/>
  <img src="https://img.shields.io/badge/OpenCV-Canny%20%2B%20Contours-5C3EE8?logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/OSMnx-Dijkstra-2C5F2D"/>
</p>

**역할**: Flutter 앱 전체 + 백엔드 API 연동 + AWS 인프라 운영

**기술적 도전**:
- 🧮 **알고리즘 직접 구현** — Haversine 거리 계산, atan2 Bearing, 경로 이탈 감지(20m tolerance + 인덱스 ±5 탐색 최적화)
- 🎨 **이미지 → GPS 경로 파이프라인** — OpenCV Canny edge + Douglas-Peucker 단순화 + OSMnx Dijkstra 도로망 매칭
- 📸 **RepaintBoundary 위젯 캡쳐 + SNS 공유** — 데이터에서 도출한 "인증 욕구" 인사이트를 코드로 풀어냄
- 📊 **데이터 기반 페르소나 도출** — 3만 건 SNS 크롤링 + PCA + 계층 클러스터링

**규모**: Flutter 30개 화면 / ~8,000 LOC + FastAPI 백엔드 10+ 엔드포인트 + AWS EC2/S3/RDS 운영

**🔗 자세히 보기**:
- 📖 [README](https://github.com/jinho3501/Runink#readme) — 프로젝트 전체 개요
- 🧠 [INTERVIEW_GUIDE.md](https://github.com/jinho3501/Runink/blob/main/INTERVIEW_GUIDE.md) — Flutter + 백엔드 deep-dive 코드 리뷰 (~670줄)
- 📑 [10분 PT 발표 자료 PDF](https://github.com/jinho3501/Runink/blob/main/RunInk_final_10min_pt.pdf)

---

### 🧠 [ChuckChuck — 척척박사](https://github.com/jinho3501/ChuckChuck)

> 친구와 1:1로 겨루는 **한국형 상식 퀴즈 앱** — iOS 네이티브로 만든 **1인 개발 + App Store 출시** 프로젝트

<p>
  <img src="https://img.shields.io/badge/Swift-F05138?logo=swift&logoColor=white"/>
  <img src="https://img.shields.io/badge/SwiftUI-007AFF?logo=swift&logoColor=white"/>
  <img src="https://img.shields.io/badge/Firebase-Auth%20·%20Firestore%20·%20FCM-FFCA28?logo=firebase&logoColor=black"/>
  <img src="https://img.shields.io/badge/App%20Store-Released-0D96F6?logo=appstore&logoColor=white"/>
  <img src="https://img.shields.io/badge/MVVM-Architecture-purple"/>
</p>

**역할**: 기획·디자인·개발·배포 전 과정 1인 담당

**핵심 기능**:
- 🎮 **싱글 플레이** — 18 카테고리 × 3 난이도, 한 라운드 10문제
- ⚔️ **1:1 배틀 모드** — 6자리 코드로 친구 초대, 실시간 스코어 동기화, 패자 점수 10% 탈취 시스템
- 🏆 **랭킹 TOP 50** — 전체/친구 한정 두 가지 뷰, 본인 행 하이라이트
- 🎯 **퀘스트·업적·도감** — 일일·주간 미션, 카테고리별 마스터 업적
- 💎 **상점** — 보석·입장권·닉네임 변경권 인앱 구매

**기술 스택**: SwiftUI · MVVM · Firebase (Auth + Firestore 실시간 동기화 + FCM 푸시 + Cloud Functions)

**기술적 도전**:
- ⚡ **클라이언트 캐싱 전략** — Firestore 호출 비용 최적화 (v1.1에서 콘텐츠 5배 확장하면서도 비용 유지)
- 🔄 **실시간 동기화** — 1:1 배틀의 실시간 스코어보드를 Firestore listener로 구현
- 📲 **푸시 알림** — FCM 토큰 관리 + 친구 초대/배틀 결과 알림

**📦 출시 이력**: v1.0 (싱글 + 배틀 + 랭킹) → **v1.1** (푸시 알림 + 콘텐츠 5배 확장 + 캐싱)

**🔗 자세히 보기**:
- 📖 [README](https://github.com/jinho3501/ChuckChuck#readme) — 핵심 구현 + 트러블슈팅 + 비용 최적화 전략
- 📱 App Store에서 "척척박사" 검색

---

## 📂 Other Projects

| 프로젝트 | 언어 | 한 줄 설명 | 링크 |
|---|---|---|---|
| 🗺 **Routour** | Flutter (MVVM) | 라우팅·여행 컨셉의 Flutter 앱 (v1.0에서 ViewModel 패턴 도입) | [Repo](https://github.com/jinho3501/Routour) |
| 📝 **SCHE** | Swift | "돌아서면 까먹는 나를 위한" 메모 서비스 | [Repo](https://github.com/jinho3501/SCHE) |
| 🎨 **Filter** | Swift | 이미지 필터 실습 프로젝트 | [Repo](https://github.com/jinho3501/Filter) |

---

## 📚 학습·실습 리포지토리

| 리포 | 영역 | 설명 |
|---|---|---|
| [Algorithems](https://github.com/jinho3501/Algorithems) | Python | 코딩 테스트·자료구조 학습 |
| [Java](https://github.com/jinho3501/Java) | Java | Java 기초 학습 |
| [StudioProjects](https://github.com/jinho3501/StudioProjects) | Dart | Flutter 실습 모음 |
| [HTML-CSS-JS](https://github.com/jinho3501/HTML-CSS-JS) | HTML/CSS/JS | 웹 프론트엔드 기초 |

---

## 🛠 기술 스택

### 모바일
![Flutter](https://img.shields.io/badge/Flutter-3.5+-02569B?logo=flutter&logoColor=white&style=for-the-badge)
![Swift](https://img.shields.io/badge/Swift-5+-F05138?logo=swift&logoColor=white&style=for-the-badge)
![SwiftUI](https://img.shields.io/badge/SwiftUI-007AFF?logo=swift&logoColor=white&style=for-the-badge)
![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?logo=dart&logoColor=white&style=for-the-badge)

### 백엔드 & 인프라
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white&style=for-the-badge)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black&style=for-the-badge)
![AWS EC2](https://img.shields.io/badge/AWS%20EC2-FF9900?logo=amazonec2&logoColor=white&style=for-the-badge)
![AWS S3](https://img.shields.io/badge/AWS%20S3-569A31?logo=amazons3&logoColor=white&style=for-the-badge)
![AWS RDS](https://img.shields.io/badge/AWS%20RDS-527FFF?logo=amazonrds&logoColor=white&style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=for-the-badge)

### 데이터 & ML
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white&style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white&style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white&style=for-the-badge)

---

## 📈 GitHub Stats

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=jinho3501&show_icons=true&theme=tokyonight&hide_border=true" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jinho3501&layout=compact&theme=tokyonight&hide_border=true" height="170"/>
</p>

---

## 📑 추가 자료

- 📄 [포트폴리오 PDF (상세 버전)](포트폴리오(임진호).pdf) — 학력·경력·프로젝트 디테일

---

## 📬 연락처

> 진호님께서 직접 채워주세요 — 아래는 placeholder입니다.

- 📧 Email: `your-email@example.com`
- 💼 LinkedIn: `https://linkedin.com/in/...`
- 📱 Phone: `010-xxxx-xxxx`

---

<p align="center">
  <i>읽어주셔서 감사합니다 🙇</i>
</p>
