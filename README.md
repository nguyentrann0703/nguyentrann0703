# 👋 Hi, I'm Nguyen!

🎓 Second-year Data Science student at the University of Economics Ho Chi Minh City  
🤖 Interested in machine learning, applied AI, and end-to-end AI systems  
🔍 Passionate about turning unstructured data into actionable insights  
🛠️ Currently building: AI pipelines with RAG, computer vision, and vector search  
📬 Reach me at: tatnguyen2007@gmail.com

---


# 💻 Tech Stack

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Ollama](https://img.shields.io/badge/ollama-%23000000.svg?style=for-the-badge&logo=ollama&logoColor=white)
![Weaviate](https://img.shields.io/badge/Weaviate-1B9B77?style=for-the-badge&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)
[![AWS](https://custom-icon-badges.demolab.com/badge/AWS-%23232F3E.svg?style=for-the-badge&logo=aws&logoColor=%23FF9900&logoWidth=20)](#)
---

# 🚀 Featured Projects
### [🎬 Multimodal Video Highlight Agent](https://github.com/cuctuyetaz258/Cross-Domain-Video-Highlight-Agent)
*Team project · HCMUT MLIoT Lab, Summer Course 2026 · My role: Backend & LLM Integration*

AI agent that extracts 3–5 short highlights from long-form lecture and podcast videos, from YouTube/local ingestion to a rendered, captioned clip.

- **Multimodal pipeline** — Audio, transcript, visual, and speaker-interaction signals feeding ranking, temporal localization, and boundary refinement
- **LLM semantic layer** — Candidate validation, content-aware reranking, and an explanation for each selected highlight
- **Rendering** — FFmpeg-based clip export with transcript-aligned captions
- **Modeling** — Supported training and evaluation of Learning-to-Rank and ActionFormer models

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)
---

### [🧴 Cosmetic Ingredient Analyzer](https://github.com/nguyentrann0703/skincare-ingredient-analyzer)
<u>[View Walkthrough](https://rag-project-report.vercel.app/)</u>

End-to-end AI pipeline for analyzing cosmetic product ingredients — classifying safety concerns and answering ingredient questions via RAG.

- **Concern Classifier** — Exact + fuzzy matching against 2,509 ingredients, grouped into ✓ Safe / ⚠ Potential Concerns / ✕ Alert
- **RAG Q&A** — Hybrid BM25 + vector search (Weaviate) powered by Qwen2.5:7b for natural language Q&A
- **OCR Pipeline** — YOLOv11s + EasyOCR + LLM cleaner for scanning physical product labels
- **7,459 semantic chunks** from BAAI/bge-base-en-v1.5 embeddings over Paula's Choice Ingredient Dictionary

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![YOLO](https://img.shields.io/badge/YOLO-111F68?style=for-the-badge&logo=yolo&logoColor=white)
![Weaviate](https://img.shields.io/badge/Weaviate-1B9B77?style=for-the-badge&logoColor=white)
![Ollama](https://img.shields.io/badge/ollama-%23000000.svg?style=for-the-badge&logo=ollama&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)

---

### [🍅 TomatoHub — LotusHack 2026](https://github.com/hoaianthai345/TomatoHub_TOTMA_LotusHack2026)
<u>[View Walkthrough](https://devpost.com/software/tomatohub-ai-powered-relief-campaign?ref_content=user-portfolio&ref_feature=in_progress)</u>

Social impact platform connecting organizations, supporters, and campaign operations in one workflow — built at LotusHack 2026.

- **Campaign flows** — Discovery, creation, editing, publishing, and closure for organizations
- **Supporter flows** — Donation handling, volunteer registration, and participation tracking
- **AI campaign drafting** — AI-assisted recommendation and autofill for campaign creation
- **Volunteer checkpoint** — QR-based attendance scanning and checkpoint management
- **Dual dashboards** — Separate workspace UIs for organizations and supporters

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![PostgreSQL](https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/sqlalchemy-%23D71F00.svg?style=for-the-badge&logo=sqlalchemy&logoColor=white)
