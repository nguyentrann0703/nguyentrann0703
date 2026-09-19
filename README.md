<h1 align="center">Hi, I'm Nguyen 👋</h1>

<p align="center">
  <strong>Tran Tat Nguyen · Data Science @ UEH</strong><br />
  Exploring applied AI through retrieval, vision, and multimodal projects.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/tat-nguyen-t-08a2a4405/](https://drive.google.com/file/d/1tK_vQTlBbviFHKdyHVj0BkxRB-RVPlFZ/view?usp=drive_link">My CV</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/tat-nguyen-t-08a2a4405/">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:tatnguyen2007@gmail.com">Email</a> &nbsp;·&nbsp;
  <a href="https://www.threads.com/@nt.jazzmine">Study Blog</a>
</p>

---

## A little about me

I'm a second-year Data Science student at the **University of Economics Ho Chi Minh City**. I enjoy working with messy, unstructured inputs — product labels, transcripts, long videos — and building something useful around them.

My projects have taken me from **OCR and retrieval-augmented generation** to **multimodal video pipelines and LLM integration**. I'm interested in how the pieces fit together: preparing data, retrieving the right context, integrating models, and bringing the result into a working app.

## Things I've built

### [🎬 Multimodal Video Highlight Agent](https://github.com/cuctuyetaz258/Cross-Domain-Video-Highlight-Agent)

*Team project · HCMUT MLIoT Lab, Summer Course 2026 · My role: Backend & LLM Integration*

AI agent that extracts 3–5 short highlights from long-form lecture and podcast videos, from YouTube/local ingestion to a rendered, captioned clip.

- **Multimodal pipeline** — Audio, transcript, visual, and speaker-interaction signals feeding ranking, temporal localization, and boundary refinement
- **LLM semantic layer** — Assesses candidate highlights against transcript context and explains each selection
- **Rendering** — FFmpeg-based clip export with transcript-aligned captions
- **Modeling** — Supported training and evaluation of Learning-to-Rank and experimental ActionFormer models

**Stack:** Python, PyTorch, LangGraph, faster-whisper, FFmpeg, Streamlit

---

### [🧴 Cosmetic Ingredient Analyzer](https://github.com/nguyentrann0703/skincare-ingredient-analyzer)

[View Walkthrough](https://rag-project-report.vercel.app/)

End-to-end AI pipeline for analyzing cosmetic product ingredients — classifying safety concerns and answering ingredient questions via RAG.

- **Concern Classifier** — Exact + fuzzy matching against 2,509 ingredients, grouped into ✓ Safe / ⚠ Potential Concerns / ✕ Alert
- **RAG Q&A** — Hybrid BM25 + vector search (Weaviate) powered by Qwen2.5:7b for natural language Q&A
- **OCR Pipeline** — YOLOv11s + EasyOCR + LLM cleaner for scanning physical product labels
- **7,459 semantic chunks** from BAAI/bge-base-en-v1.5 embeddings over Paula's Choice Ingredient Dictionary

**Stack:** Python, YOLOv11s, EasyOCR, Weaviate, Sentence Transformers, Ollama, Docker, Streamlit

---

### [🍅 TomatoHub — LotusHack 2026](https://github.com/hoaianthai345/TomatoHub_TOTMA_LotusHack2026)

[View Walkthrough](https://devpost.com/software/tomatohub-ai-powered-relief-campaign?ref_content=user-portfolio&ref_feature=in_progress)

Social impact platform connecting organizations, supporters, and campaign operations in one workflow — built at LotusHack 2026.

- **Campaign flows** — Discovery, creation, editing, publishing, and closure for organizations
- **Supporter flows** — Donation handling, volunteer registration, and participation tracking
- **AI campaign drafting** — AI-assisted recommendation and autofill for campaign creation
- **Volunteer checkpoint** — QR-based attendance scanning and checkpoint management
- **Dual dashboards** — Separate workspace UIs for organizations and supporters

**Stack:** Python, FastAPI, PostgreSQL, SQLAlchemy

---

## Tech Stack

**Languages:** Python, HTML/CSS, LaTeX<br />
**AI & ML Libraries:** Pandas, NumPy, Matplotlib, PyTorch (Basic), Sentence Transformers, EasyOCR<br />
**Database:** Weaviate (Vector DB)<br />
**Tools & Deployment:** AWS, Git, Docker, Streamlit, Figma

## A few milestones

- **Excellent · Top 10%** — [Python & Machine Learning Summer Courses 2026]([https://mliotlab.com/courses/python-ml/2026](https://drive.google.com/file/d/1A5OPC1-qrSeMmw-i5Qj3L1fNGHSZqG-C/view?usp=sharing)), HCMUT MLIoT Lab.
- **Top 5 UEH Representatives** — NextGen Consumer Challenge 2026, organized by GIZ. Proposed **ScanHealth**, a product-verification and ingredient-decoding app concept, with an interactive Figma prototype. [Certificate](https://drive.google.com/file/d/1DBSH32QHYzBBQwO74QV6RVYzEt0BiZFK/view) · [Prototype](https://byvn.net/p8bs)
- **[AWS Certified Cloud Practitioner](https://drive.google.com/drive/u/0/folders/1D1YG4KXtS2cjgtQUbJRVUBcgolLWXUiF)** — Amazon Web Services.

---

Always happy to exchange ideas about applied AI or talk through a project. [Say hello →](mailto:tatnguyen2007@gmail.com)
