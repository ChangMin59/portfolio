# Developer Portfolio

안녕하세요 👋
개발자 **이창민(ChangMin59)** 입니다.

저는 **데이터 전처리 → AI 모델링 → 서비스 배포** 전 과정을 직접 수행하며,
아이디어를 실제 사용자 가치로 전환하는 데 강점을 가진 개발자입니다.

특히 다음 영역에서 강점을 보유하고 있습니다.

  - **LangChain + RAG**: 비정형 데이터를 구조화하고 벡터 검색을 결합해 **정확하고 근거 기반**의 답변을 생성

  - **LLM Fine-tuning & Prompt Engineering**: 도메인 특화 QnA 시스템을 구축해 **정책·전문용어 이해도 향상**

  - **Agent + LangGraph**: 복잡한 다단계 질의를 자동 라우팅해 주택·대출 등 **멀티 도메인 챗봇**을 설계 및 구현

  - **FastAPI** 서비스화: AI 모델과 챗봇을 **실제 배포 가능한** API 서비스로 제공

본 저장소에는 이러한 경험이 담긴 대표 프로젝트와 포트폴리오 **PDF**가 포함되어 있으며,
모든 프로젝트는 단순 구현을 넘어 현실 **문제 해결**과 **서비스 적용**을 목표로 설계되었습니다.

---

## 📂 Portfolio Files & Projects
### 👉📘 [Developer Web Page.pdf](./portfolio/Developer_Web_Page.pdf)  
Spring Boot + JPA + MySQL 기반의 **백엔드 로직 설계**와 HTML/CSS/JavaScript 기반의 **프론트엔드 UI 구현**을 결합해
풀스택 웹 애플리케이션을 직접 구축한 프로젝트입니다.

단순한 학습용 예제를 넘어서, **회원가입 → 로그인 인증 → 대시보드 렌더링**까지
실제 서비스 흐름을 고려해 개발했고, GSAP ScrollTrigger와 Canvas 인터랙션을 적용해
사용자가 몰입할 수 있는 **애니메이션 기반 UX**를 구현했습니다.

이 경험을 통해 **백엔드–프론트엔드 통합 개발**, **REST API** 통신, 사용자 경험 중심 **UI 설계**를
끝까지 경험했으며, 서비스 전체 흐름을 스스로 설계하고 최적화하는 능력을 키웠습니다.

**주요 기능**
  - **회원가입**: 사용자 정보 저장 (DTO → Entity 변환)  
  - **로그인**: 이메일/비밀번호 인증 → 사용자 정보 반환  
  - **대시보드**: 로그인된 사용자 정보 요청 후 클라이언트에서 조회 및 표시  
  - **로그아웃**: 인증 상태 해제 후 로그인 페이지로 리다이렉트  
  - **UX 인터랙션**: GSAP ScrollTrigger + Canvas 기반 애니메이션  

**기술 스택**
  - **Frontend**  
    - HTML, CSS, Sass(SCSS), JavaScript, GSAP(ScrollTrigger), Canvas
    - GitHub Pages 배포  

- **Backend**  
  - Spring Boot + JPA + MySQL 기반 RESTful 구조 설계  
  - Render 서버를 통한 백엔드 분리 배포  
  - Railway 기반 클라우드 MySQL 연동 

**배포 링크 & 저장소**
- **포트폴리오 웹**: [GitHub Pages (실제 서비스)](https://changmin59.github.io/portfolio_client/)  
- **Frontend 코드**: [portfolio_client](https://github.com/ChangMin59/portfolio_client)  
- **Backend 코드**: [portfolio_server](https://github.com/ChangMin59/portfolio_server)  
---

### 👉🔎 [FindGo.pdf](./portfolio/FindGo.pdf)  
→ **YOLOv8 + ByteTrack 기반 실시간 물건 탐지·추적 AI**  

- **문제 정의**:  
  - 바쁜 현대인의 반복적인 **물건 분실 문제** 해결 필요  
  - 고령층·알츠하이머 환자의 **기억력 한계로 인한 분실** 문제 보완  
  - 기존 CCTV·스마트홈 장치의 한계: 단순 녹화 기능에 그쳐 **실시간 탐지·알림 부족**  


- **기술 스택**:  
  - **데이터 수집**: COCO 데이터셋 + 직접 촬영한 100여 장 이미지 라벨링  
  - **객체 탐지**: YOLOv8 (다양한 물품 인식)  
  - **객체 추적**: ByteTrack (프레임 간 ID 유지, 안정적 추적)  
  - **영상 처리**: OpenCV (실시간 스트리밍 및 전처리)  
  - **데이터 증강**: Albumentations (조명, 각도, 그림자, 가림 등 다양한 상황 학습)  

- **주요 기능**:
  - **실시간 탐지**: 카메라 입력 기반 물건 위치 탐지  
  - **객체 추적**: 이동·가림 상황에서도 동일 객체 지속 추적  
  - **강화된 인식**: 데이터 증강으로 다양한 환경(조명/각도/그림자)에 대응  
  - **시각화 제공**: 탐지된 객체에 Bounding Box 및 ID 표시  

- **성과**:  
  - **탐지율 개선**: 데이터 증강 적용 후 인식률 향상  
  - **추적 안정성 확보**: 증강 적용 후 인식률 향상, 추적 안정성 개선(예: ID 스위치 감소, 탐지율 +6.3%)

## 🔗 데모 & 저장소
- **Colab 데모**: [Open in Colab](https://colab.research.google.com/drive/1w_tqy06pbsKyC61KbOjjVGVDjizUolVz?usp=sharing)
- **FindGo 코드**: [findgo](https://github.com/ChangMin59/findgo)

---

### 👉💳 [Card Chatbot.pdf](./portfolio/cardchatbot.pdf)  
→ **Card Fit (질문 유형 분기(Prompt Engineering) → 카드/혜택은 RAG, 기타는 Tavily”로 흐름 중심 정리)**  

- **문제 정의**:  
  - 카드 혜택은 복잡해 사용자가 직접 비교·선택하기 어려움  
  - 카드사 제공 정보는 정형화되어 있지만, 사용자 질문은 비정형적임  
  - 기존 검색만으로는 혜택·조건·비교 정보를 빠르게 제공하기 어려움  

- **기술 스택**:  
  - **데이터 수집**: 카드사 웹사이트 데이터 크롤링 (Selenium) 
  - **벡터 검색**: FAISS + HuggingFaceEmbeddings (`jhgan/ko-sroberta-multitask`)  
  - **검색 구조**: Retriever + ReRanker  
  - **질문 분류**: Prompt Engineering (Custom Template 적용)
  - **LLM 모델**: `Mistral` (Ollama 연동)  
  - **프레임워크**: LangChain, RAG
  - **대화 관리**: ConversationBufferMemory (대화 맥락 유지)  
  - **API 연동**: Tavily API (카드 외부 검색 질의 처리)  
  - **서버 구현**: Streamlit 

- **주요 기능**:  
  - 사용자 조건 기반 **카드 추천 및 혜택 비교**  
  - **질문 유형 분기** → (카드/혜택 질문 vs 외부 검색 질문)  
  - 카드 관련 질문 → 카드사 데이터 기반 추천·비교 제공  
  - 기타 질문 → Tavily API 활용해 외부 검색 후 응답
  - **대화 맥락 유지** (ConversationBufferMemory 활용)  

- **질문 유형 분기 (Prompt Engineering)**  
  - "카드 추천·비교 질문" → 카드사 데이터 기반 RAG 검색  
  - "카드 외부 정보 질문" → Tavily API 연동으로 실시간 답변  

- **성과**:  
  - **질문 자동 분류 체계** 구축 → 카드 추천·비교 / 외부 질문을 정확히 라우팅  
  - **검색 정확도 향상** → Retriever + ReRanker로 카드 정보 탐색 신뢰도 개선  
  - **응답 효율성 강화** → 불필요한 카드사 검색 최소화, 외부 검색은 필요한 경우에만 호출  
  - **사용자 경험 개선** → 반복 질문에도 맥락 유지(ConversationBufferMemory 적용)

  ## 🔗 저장소
- **Card Chatbot 코드**: [Card Chatbot](https://github.com/ChangMin59/Card_Chatbot)

---

### 👉🏠 [WELHOME.pdf](./portfolio/welhome.pdf)  
→ **LH 주택청약 추천·대출 QnA 챗봇 (Intent Router + RAG + Fine-tuning + LangGraph Agent)**  

- **문제 정의**:  
  - 공고문 100건 이상, PDF 직접 열람 필요 → 조건 확인 비효율  
  - 정책 전문용어 난해 → 청년·신혼부부·저소득층 정보 격차 발생  
  - 당첨 이후 자금 문제로 계약 포기 사례 다수 발생

- **기술 스택**:  
  - **데이터 수집**: 공공데이터포털 API(data.go.kr)
  - **데이터 추출**: Upstage(PDF→HTML)
  - **벡터 검색**: BGE-M3 + ChromaDB(공고별 chunk 저장/검색)
  - **질문 유형 분류**: Intent Router (주택 / 대출 라우팅)  
  - **주택·대출 챗봇 모델**: `exaone3.5:7.8b`  
  - **QnA 챗봇**: `naver-hyperclovax/HyperCLOVAX-SEED-Text-Instruct-1.5B` (Fine-tuning)  
  - **데이터베이스**: SQLite (대출 / 주택 정보 저장)
  - **프레임워크**: FastAPI, Uvicorn, LangChain, LangGraph , Agent
  - **공고문 원문 확인**: PyMuPDF/pdf2image (추천된 PDF 페이지 이미지 렌더링)  

- **주요 기능**:  
  - 사용자 조건 기반 맞춤형 **LH 청약 공고 추천**  
  - **정책 용어 QnA** 챗봇 (전문용어 → 일상어 설명)  
  - **주택 / 대출 상담 챗봇**  
    - 조건 입력 시 맞춤형 **주택 공고** 및 **대출 정보** 제공  
  - **PyMuPDF 연동 → 해당 공고문 PDF 페이지도 함께 제공** (신뢰성 확보)  
    - 공고문 PDF를 HTML로 파싱 → 비정형 텍스트 구조화 후 검색 최적화  

- **질문 유형 분기 (Intent Routing)**  
  - "청약 관련 질문" → 조건 기반 LH 공고문 검색 + 해당 PDF 페이지 제공  
  - "대출 관련 질문" → 조건별 대출 계산 및 상품 비교  
  - "전문용어 질문" → 파인튜닝된 QnA 챗봇에서 응답  

- **성과**:  
  - PDF 탐색 소요 시간 **평균 2시간 → 10분 내 단축 (80% 절감)**  
  - Intent Router 기반 질문 분기 → **주택/대출 상담 정확도 향상**  
  - Fine-tuning 적용 QnA 챗봇 → **정책 용어 이해도 개선**  
  - PyMuPDF 연동 → **추천 공고문 PDF 원문·페이지 직접 제시** (신뢰성 확보)
    
 ## 🔗 저장소
- **welhome 결과**: [Welhome 결과 영상](./portfolio/welhome_결과영상.mp4)
- **welhome 코드**: [welhome](https://github.com/ChangMin59/welhome) 
    
---
## 🚀 Tech Highlights
- **AI/ML Models**: Mistral, Exaone3.5, HyperCLOVAX-SEED, YOLOv8  
- **AI Frameworks**: LangChain, LangGraph, FAISS, ChromaDB, ByteTrack  
- **Data & Vision Tools**: OpenCV, Albumentations  
- **Backend**: Spring Boot, JPA, MySQL, FastAPI, Render, Railway  
- **Frontend**: HTML, CSS, Sass(SCSS), JavaScript, GSAP(ScrollTrigger), Canvas, GitHub Pages  
- **Infra & Data Tools**: SQLite, Selenium, PyMuPDF, Tavily API, 공공데이터포털 API  
- **Dev Tools**: VS Code, Cursor, IntelliJ IDEA Community Edition 2024.3.5

---

📌 각 프로젝트는 이론 검증을 넘어 실제 문제 해결과 서비스 적용을 목표로 설계·구현되었습니다.
👉 세부 과정과 정량적 성과는 첨부된 PDF 포트폴리오에서 확인 가능합니다.
