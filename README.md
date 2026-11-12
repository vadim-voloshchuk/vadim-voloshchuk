<div align="center">

<img src="./assets/hero.png" alt="Pixel-art banner: Vadim Voloshchuk — ML Engineer and AI Researcher" width="100%" />

**Engineer of structured intelligence. Explorer of hidden connections.**

[🇷🇺 Русская версия](./README.ru.md) · [ORCID](https://orcid.org/0009-0003-0336-9305) · [Scopus](https://www.scopus.com/authid/detail.uri?authorId=58624116300) · [eLIBRARY](https://www.elibrary.ru/author_profile.asp?authorid=1245932) · [Telegram](https://t.me/nosignalx2k)

</div>

<img src="./assets/activities.png" alt="Four pixel-art modes: build, research, explore, recharge" width="100%" />

## `> whoami`

I'm **Vadim Voloshchuk**, an **ML engineer, AI researcher and PhD student** at **Southern Federal University (SFedU)**. I've worked on applied ML systems since 2021, from computer vision and predictive modeling to document intelligence, retrieval, and experimental language-model architectures.

| Currently | Focus |
|:--|:--|
| 🔬 **R&D Engineer, SFedU** | Document AI, NLP/RAG, computer vision, experiments and evaluation |
| 🎓 **Teaching Assistant, SFedU** | Discrete mathematics and mentoring student ML projects (since September 2026) |
| ⚙️ **Data Analyst, SKRIPT LLC** | Regression, boosting, ensembles and applied ML (part-time) |
| 🚀 **Founder / ML Engineer, NeuroFlexDev — Lernium** | AI-powered educational workflows, search, backend and infrastructure |

📍 Rostov-on-Don / Taganrog, Russia · RU native · EN B1.

## `> research --telemetry`

<img src="./assets/telemetry.png" alt="RAG retrieval Recall@5 57.7% on 1114 queries; language model natural validation perplexity SSM 26.25 and Transformer 28.99; 350M tokens per model" width="100%" />

- **Technical-document retrieval:** evaluated BM25, dense retrieval, SPLADE and uniCOIL on **1,114 queries**; best **Recall@5 = 57.7%**. [Paper](https://doi.org/10.3390/fi18060327) · [Code](https://github.com/vadim-voloshchuk/MicroRAG)
- **From-scratch language models:** compared three SSM/Transformer models with **~73–77M parameters** and **350M processed tokens per model** on NVIDIA H100. Natural-validation PPL: **26.25 (SSM-only)**, **26.36 (SSM + explicit memory)**, **28.99 (Transformer)**. **Exploratory single-seed runs with unequal context availability, not evidence of architectural superiority.** [Experiment notes & code](https://github.com/vadim-voloshchuk/TfPLSLM)
- **Vector–graph retrieval:** studied hybrid semantic search and graph traversal, including quality–latency tradeoffs. [Paper](https://doi.org/10.3390/bdcc10020051)

**PhD research:** reducing the infrastructure load of distributed multi-agent systems in digital twins: inter-agent traffic, semantic caching at the edge, context compression, KV-cache handling, heterogeneous routing and distributed inference.

<img src="./assets/research-map.png" alt="Research map showing documents, vector-graph retrieval, context compression and caching, routing and distributed agents" width="100%" />

## `> publications --selected`

| Year | Work | Venue |
|:---:|---|---|
| **2026** | [Application of a Hybrid Approach in the Synthesis of a Knowledge Extraction Module of an Intelligent Assistant for a Microcontroller Technical Specialist](https://doi.org/10.3390/fi18060327) | *Future Internet*, 18(6), 327 · **First author** |
| **2026** | [Hybrid Method of Organizing Information Search in Logistics Systems Based on Vector-Graph Structure and Large Language Models](https://doi.org/10.3390/bdcc10020051) | *Big Data and Cognitive Computing*, 10(2), 51 · **First author** |
| **2025** | [Analysis of Drought Dynamics Using SPI and SARIMA Models: A Case Study of the Rostov Region, Russia](https://doi.org/10.18393/ejss.1682888) | *Eurasian Journal of Soil Science*, 14(3) |
| **2024** | [An Ontological Model for the Automated Data Replenishment Method Implementation for the Synthesis of Applied Photogrammetry Systems](https://doi.org/10.1109/RusAutoCon61949.2024.10694212) | *IEEE RusAutoCon* |
| **2024** | [An Approach to Building Adaptive Object Accounting Systems Using Artificial Intelligence Methods](https://doi.org/10.18522/2311-3103-2024-5-152-162) | *Izvestiya SFedU. Engineering Sciences* |
| **2023** | [An Approach for Making a Conversation with an Intelligent Assistant](https://doi.org/10.1007/978-3-031-35314-7_47) | Springer, *AI Application in Networks and Systems* |

**Research identifiers:** [ORCID 0009-0003-0336-9305](https://orcid.org/0009-0003-0336-9305) · [Scopus Author ID 58624116300](https://www.scopus.com/authid/detail.uri?authorId=58624116300) · [RSCI AuthorID 1245932](https://www.elibrary.ru/author_profile.asp?authorid=1245932).

<details>
<summary><b>Publication metrics — dated snapshots</b></summary>

- **21 Oct 2026 / Scopus:** 5 indexed documents; 5 citations; h-index 2.
- **21 Oct 2026 / eLIBRARY:** 34 publications (31 RSCI); 47 citations; h-index 3.
- A later October 2026 personal update reported **39 eLIBRARY records / 49 citations**; this has not been independently checked against a live author profile.
- Databases overlap and have different inclusion rules; counts are not additive.

</details>

## `> ls projects/`

| Project | What I built / studied | Source |
|---|---|---|
| **MicroRAG** | Reproducible document retrieval and RAG research: PDF ingestion, BM25 / FAISS, evaluation and benchmarks | [GitHub](https://github.com/vadim-voloshchuk/MicroRAG) |
| **TfPLSLM** | Selective state-space / Transformer language-model research, training from scratch and reproducible experiment notes | [GitHub](https://github.com/vadim-voloshchuk/TfPLSLM) |
| **Lernium / NeuroLearn** | AI-assisted educational platform: course generation, document OCR, source-aware search and versioning | [Backend](https://github.com/NeuroFlexDev/ciBack) |
| **doc2text-demo** | OCR and field extraction from documents, OpenCV preprocessing and Gradio interface | [GitHub](https://github.com/vadim-voloshchuk/doc2text-demo) |
| **NeuroWeave** | Graph editing, visualization, shortest paths, centrality and clustering | [GitHub](https://github.com/vadim-voloshchuk/NeuroWeave) |

**Earlier projects:** [Face Swap with Diffusion Models](https://github.com/vadim-voloshchuk/Face-Swap-with-Diffusion-Models) · [BIOHACK](https://github.com/vadim-voloshchuk/BIOHACK) · [Abeona LifeHub](https://github.com/vadim-voloshchuk/ABEONA_NEXT) · [CyberGarden](https://github.com/vadim-voloshchuk/CyberGarden).

**Award:** [Lernium — "Promising Project / PSB Bank's Choice", Gravitation 2026](https://sfedu.ru/press-center/news/80632).

## `> cat experience.log`

| Period | Role | Focus |
|---|---|---|
| **Oct 2023 — present** | **Southern Federal University** · R&D Engineer, Institute of Robotics and Control Systems | AI/ML research, evaluation, NLP and CV |
| **Sep 2026 — present** | **Southern Federal University** · Teaching Assistant, Computer Engineering | Discrete mathematics and mentoring |
| **Mar 2025 — present** | **SKRIPT LLC** · Data Analyst (part-time) | Applied classical ML and validation |
| **2025 — present** | **NeuroFlexDev / Lernium** · Founder, ML Engineer | AI services and platform engineering |
| **Apr — Jul 2026** | **Dinamika — Orthopedic Technologies** · Lead R&D Engineer | ML, 3D and engineering software |
| **Dec 2025 — Apr 2026** | **D-Technologies** · Lead R&D Engineer | Research prototypes, reusable components |
| **Oct 2021 — Dec 2022** | **Digital Skynet** · ML Developer / Engineer | Image segmentation, texture replacement, ALPR |

Earlier SFedU / student laboratory work (2021–2023) involved video analytics for industrial and transportation scenarios.

## `> cat education.json`

- **2026 — present:** PhD studies at **Southern Federal University**, specialty **2.3.1** (System Analysis, Control and Information Processing).
- **2026:** MSc, **Southern Federal University** — Computer Science and Engineering.
- **2026:** MSc, **RUDN University** — Data Management and Artificial Intelligence, **with honors**.
- **2024:** BSc, **Southern Federal University** — Computer Science and Engineering.
- **2024:** Professional retraining, SFedU — Theory of Algorithms in AI Systems (Systems Analyst).

## `> stack --list`

**ML / research:** Python · PyTorch · scikit-learn · NumPy · Pandas · Polars · Hugging Face · experiment design and evaluation.

**Retrieval / NLP:** RAG · BM25 · FAISS · dense/sparse retrieval · SPLADE · uniCOIL · reranking · embeddings.

**Document AI / CV:** OpenCV · Tesseract OCR · EasyOCR · docTR · segmentation · classification · video analytics.

**Infrastructure / applications:** FastAPI · PostgreSQL · Redis · Docker · Kubernetes · Helm · Linux · GitHub Actions · GitLab CI · pytest · React · TypeScript.

## `> connect`

[![Telegram](https://img.shields.io/badge/Telegram-20242C?style=flat-square&logo=telegram&logoColor=white)](https://t.me/nosignalx2k) [![Email](https://img.shields.io/badge/Academic_Email-20242C?style=flat-square&logo=gmail&logoColor=white)](mailto:vvoloshchuk@sfedu.ru) [![GitHub](https://img.shields.io/badge/GitHub-20242C?style=flat-square&logo=github&logoColor=white)](https://github.com/vadim-voloshchuk) [![ORCID](https://img.shields.io/badge/ORCID-20242C?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0003-0336-9305)

<img src="./assets/terminal.png" alt="Pixel terminal: think, research, build, measure, repeat" width="100%" />

<sub>Chibi pixel art extracted from a user-provided original reference sheet, background-cleaned and upscaled with nearest-neighbor resampling. Research indicators show dated experiments, not live metrics.</sub>
