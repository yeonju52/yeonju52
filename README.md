# 👋 YeonJu Lee - Backend & AI Developer  

**Backend Developer** passionate about integrating **AI technologies** into **web and embedded systems**.  

## AI 기능을 서비스 로직에 녹여내는 백엔드 개발자

AI 기능을 서비스에 통합하여 **팀이 지속적으로 운영할 수 있는 구조로 비즈니스 로직을 구현하는 것**을 지향합니다.

인턴 프로젝트에서는 **OpenAI API를 활용한 LLM 기반 해설 기능**을 백엔드에 통합했습니다. 모델 호출과 데이터 처리 로직을 **별도 레이어로 분리하여**, 기능 확장이나 모델 변경에도 **서비스 전체가 안정적으로 동작하도록 설계했습니다.**

<img src="img/NANGPAGO/Award.jpeg" height="180"/>

## 🛠️ Tech Stack
<p align="center"> <!-- 💻 Language -->
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/> </p>
<p align="center"> <!-- 🌱 Framework -->
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
  <img src="https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white"/> </p>
<p align="center"> <!-- 🗄️ Database -->
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black"/>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white"/> </p>
<p align="center"> <!-- 🔍 Infra / Message Queue / AI -->
  <img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white"/>
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/> </p>
<p align="center"> <!-- ⚙️ DevOps / Tools -->
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/> </p>

---

## 🌟 Intern

### [ILTA(일타) — AI 수학 선생님 웹 서비스](https://github.com/ocy-likelion/AI_teacher_2_backend/)

LLM과 OCR을 결합해 **학부모가 문제 이미지를 업로드하면 자녀에게 설명할 수 있도록 해설을 제공하는 AI 기반 수학 학습 도우미**

* **GPT API 기반 해설 생성 로직** 구현으로 QA 정확도 95% 달성
* **OCR 전처리(pytesseract)** 로 수식 인식률 향상 (lang='kor+eng+equ')
* Render 기반 **CI/CD 파이프라인 구축** (256MB 환경에서 모델 경량화)
* Stack: Spring Boot · Flask · PostgreSQL · OpenAI API · Render

<img src="img/INTERN/UserFlow.png"/>
<img src="img/INTERN/Architecture.jpg" height="180"/>

---

## 🌟 Projects

### [NangPaGo(냉파고) — Elasticsearch 기반 검색·추천 웹 서비스](https://github.com/MARS-LIKELION/NangPaGo)

**Elasticsearch 기반 자연어 검색 시스템**으로 사용자의 재료 입력에 맞춰 **맞춤형 레시피를 추천**하고,
**비동기 이벤트 아키텍처 기반 실시간 커뮤니티·알림 기능**을 제공하는 웹 서비스

* **Elasticsearch 기반 검색 및 자동완성 API** 구현으로 검색 응답속도 85% 개선
* **RabbitMQ + SSE 이벤트 아키텍처** 로 좋아요 토글 및 실시간 알림 기능 구현
* **Admin Dashboard** 구축으로 통계·감사 로그 실시간 모니터링
* Stack: Spring Boot · MySQL · Elasticsearch · Docker · Jenkins

[👉 서비스 배포 URL](https://nangpago.site/)

<img src="img/NANGPAGO/Web2.png" height="180"/> <img src="img/NANGPAGO/Architecture.png" height="180"/>

### [MOIRO — Vision AI 자율 촬영 로봇](https://github.com/MOIRO-KAIROS/moiro_ws)
Flask 기반 RESTful API로 로봇(AGV·로봇 암·카메라)을 통합 제어하는 하드웨어-소프트웨어 오케스트레이션 시스템  
- 3대 디바이스 통합 제어로 13fps/15fps 실시간 프레임 유지율 달성  
- **Stack:** Flask, ROS2, YOLOv8, AdaFace

<img src="img/MOIRO/MOIRO_Result.png" height="180"/> <img src="img/MOIRO/MOIRO_WEB.png" height="180"/>

### [AIFT — 실시간 얼굴 필터 웹 서비스](https://github.com/Filter-Web/AI)
Spring Boot와 Flask를 연동해 웹캠 영상을 실시간으로 인식·처리하는 얼굴 필터 웹 서비스  
- NVIDIA GPU를 활용한 AI 객체 탐지 모델을 Flask 서버에 배포하고, 이를 웹과 실시간 연동하여 스트리밍 기반 얼굴 필터 적용 구현
- **Stack:** Spring Boot, Flask, OpenCV, YOLO-Face

<img src="img/PROJECT/2_FilterWeb1.jpeg" height="180"/> <img src="img/PROJECT/2_FilterWeb2.png" height="180"/>

### [Cometext — 문장 맥락 기반 도서 추천 시스템](https://github.com/Hanium-Cometext/cometext-gpt)
KoGPT와 S-BERT를 결합해 문장의 의미를 벡터화하고 유사도 기반으로 도서를 추천하는 자연어 처리 서비스  
- 기존 연구를 벤치마킹해 자체 데이터셋에 특화된 GPT 기반 문맥 검색 시스템을 독자적으로 구현
- **Stack:** Flask, PyTorch, KoGPT, S-BERT

<img src="img/PROJECT/1_GPT_Prompt.png" height="180"/>

### [CRM 고객 이탈 예측 모델](https://github.com/yeonju52/Market_RecSys.git)
고객 행동 데이터를 기반으로 LightGBM·NCF 모델을 활용해 이탈 예측 및 맞춤형 상품 추천을 수행한 프로젝트  
- LGBM 모델로 F1 Score 0.73 달성, 세분화된 고객군 타깃팅 성공  
- **Stack:** Pandas, LightGBM, PyTorch


<!--
|          Project          |                                                                                  Preview                                                                                  |
| :-----------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|        **NangPaGo**       |         <img src="img/NANGPAGO/Web2.png" height="100"/> <img src="img/NANGPAGO/Architecture.png" height="100"/> <img src="img/NANGPAGO/Award.jpeg" height="100"/>         |
|         **MOIRO**         |          <img src="img/MOIRO/MOIRO_HW.png" height="100"/> <img src="img/MOIRO/MOIRO_Result.png" height="100"/> <img src="img/MOIRO/MOIRO_WEB.png" height="100"/>          |
|          **AIFT**         |                                                          <img src="img/PROJECT/2_FilterWeb1.jpeg" height="100"/> <img src="img/PROJECT/2_FilterWeb2.png" height="100"/>   |
|        **Cometext**       |                               <img src="img/PROJECT/1_GPT_Prompt.png" height="100"/>                                                                                      |
| **Research & Internship** | <img src="img/INTERN/1_OpenPose.png" height="100"/> <img src="img/INTERN/2_YOLO_FACE.jpeg" height="100"/> <img src="img/INTERN/3_Bit-Depth_Expansion.jpeg" height="100"/> |
-->

---

## 📊 Algorithm & Study

[![Solved.ac 프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=yeonju509)](https://solved.ac/yeonju509)

- [Velog — 알고리즘 TIL 기록](https://velog.io/@yeonju52/series/%EC%BD%94%ED%85%8CC)  
- [학부연구 인턴십 — Computer Vision Research](https://github.com/yeonju52/ComputerVision.git)

<img src="img/CV/1_OpenPose.png" height="180"/> <img src="img/CV/2_YOLO_FACE.jpeg" height="180"/> <img src="img/CV/3_Bit-Depth_Expansion.jpeg" height="180"/>
---

<p align="center">
  <sub>© 2025 YeonJu Lee — Backend & AI Developer</sub>
</p>
