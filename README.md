# 안녕하세요, 오병주입니다 👋

**생성형 AI를 실제로 쓸 수 있는 서비스로 만드는 AI 백엔드 개발자**를 지향합니다.
모델을 돌려보는 데서 끝내지 않고, 서빙·UX·인프라 제약까지 해결해 사용자가 쓰는 형태로 완성하는 데 관심이 있습니다.

- 🔭 관심 분야: LLM 에이전트(RAG · LangGraph), 이미지 생성 파이프라인, 컴퓨터 비전 서빙
- 🛠 주로 하는 일: FastAPI 기반 모델 서빙, 프롬프트/파이프라인 설계, 팀 프로젝트 PM
- 📫 Contact: ossang1119@gmail.com

<br>

## 🧰 Tech Stack

**Language**
<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>

**AI / ML**
<br>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/YOLO-111F68?style=flat-square&logo=yolo&logoColor=white"/>
<img src="https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=mediapipe&logoColor=white"/>
<img src="https://img.shields.io/badge/Diffusers-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>

**Backend / Infra**
<br>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>

**Frontend**
<br>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
<img src="https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=white"/>

<br>

## 🚀 Main Projects (팀 프로젝트)

### 🎨 [AdGen](https://github.com/OH-BJ/Team-AdGen-Project) — 소상공인 광고 생성 AI 서비스
`5인 팀 · Backend` · Python, FastAPI, Flux-2-Klein, GPT-5, SSE
- 상품 이미지 → 광고 이미지 + 카피를 한 번에 생성하는 파이프라인
- 이미지 생성과 텍스트 렌더링을 분리해 생성형 AI의 '글씨 뭉개짐' 문제 해결
- **SSE**로 30초 대기 시간을 실시간 진행 표시로 전환해 UX 개선
- Swap 메모리 + 심볼릭 링크로 저사양 GPU 환경의 **OOM 문제 해결**

### 📑 [Bidding-Mate](https://github.com/OH-BJ/Bidding-Mate) — 입찰 공고 분석 RAG 에이전트
`5인 팀` · LangGraph, ChromaDB, Ragas, Docker
- 평균 7만 자 공공 입찰 공고문에서 예산·기간·평가 기준을 추출
- Router → Retriever(MMR) → Grader → Generator 순환형 **LangGraph** 구조로 할루시네이션 억제
- Ragas 기반 평가, Docker Compose로 원커맨드 실행

### 💊 [HealthEat](https://github.com/OH-BJ/HealthEat-Pill-Detection) — 경구약제 이미지 인식
`4인 팀 · PM` · YOLOv8/11, SAM, CBAM, FastAPI, Android
- 데이터 누수·라벨 한계 확인 후 BBox → **Segmentation으로 전략 전환** 의사결정
- mAP50-95 **0.870 → 0.990**, F1 **0.852 → 0.970**
- 프로젝트 총괄, 방향 설정, 발표·문서화 담당

<br>

## 🧪 Side Projects (개인)

| 프로젝트 | 설명 | Stack |
|---|---|---|
| [cosmos-desktop](https://github.com/OH-BJ/cosmos-desktop) | 3D 우주 파일 탐색기 | Tauri · Rust · three.js |
| [arcanum-tarot](https://github.com/OH-BJ/arcanum-tarot) | 시네마틱 3D 타로 + Gemini 해석 | Next.js · R3F |
| [magician](https://github.com/OH-BJ/magician) | 손 모양·입으로 주문을 거는 웹캠 마법 게임 | MediaPipe |
| [aipulse](https://github.com/OH-BJ/aipulse) | 개인용 AI 뉴스/논문 큐레이션 | TypeScript |
| [saju-service](https://github.com/OH-BJ/saju-service) | 한지 콘셉트 사주 서비스 | TypeScript |

<br>

## 🤝 Collaboration
- 팀 프로젝트 3건(4~5인)에서 **Backend 개발 · PM** 역할 수행
- Notion 기반 회의록·개인 협업 일지 작성, GitHub로 코드 협업
- 함께한 팀원: [@SYLforge](https://github.com/SYLforge) · [@Seo-Junbeom](https://github.com/Seo-Junbeom) · [@carsy078-maker](https://github.com/carsy078-maker) 외

<br>

## 📊 GitHub Stats
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=OH-BJ&layout=compact&hide_border=true"/>
