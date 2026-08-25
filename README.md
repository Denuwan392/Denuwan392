# Denuwan Wijesinghe

Artificial Intelligence undergraduate at the University of Moratuwa and AI Engineer at WIWIS.AI.

Interested in building intelligent systems that combine reasoning, learning, and interaction. My current work explores agentic AI, language technologies, multimodal intelligence, and machine learning for real-world applications, with a particular interest in low-resource languages.

## Selected Work

* **HomeOS** *(AgentriX 2026 Finalist)* — Multi-agent system for autonomous task planning and orchestration.
* **Smart Transit Companion** *(SLAIC 2025 Finalist)* — Multilingual transportation assistant built around retrieval and reasoning.
* **WEISION** *(Presented at SLAAI 2025 AI Project of the Year)* — Edge AI system for vision-based produce identification and automated billing.
* **Speaker Role Classification** *(Industry collaboration project with Embla Software Innovation (Pvt) Ltd.)* — Machine learning approach for understanding organizational roles from meeting conversations.

> *"Build carefully. Measure honestly. Publish what matters."*

📍 Sri Lanka



## Featured Projects

<details open>
<summary><strong>01 &nbsp; AGENTIC AI &nbsp;&nbsp;&nbsp; Neural Surge</strong></summary>

**Multi-agent system for autonomous task planning, reasoning, and orchestration.**

Agentrix 2026 Finalist (HomeOS). An 8-node LangGraph state machine orchestrating inventory audit, spoilage analysis, semantic recipe matching via Qdrant RAG, budget enforcement, and reflection loops. Includes two-stage receipt parsing (RapidOCR + Gemini fallback), React Native mobile companion with voice assistant, and full LangSmith observability suite.

![Python](https://img.shields.io/badge/Python-3.12-007acc?style=flat-square) ![FastAPI](https://img.shields.io/badge/FastAPI-0.110%2B-55b62b?style=flat-square) ![LangGraph](https://img.shields.io/badge/LangGraph-Agent%20Framework-e06c28?style=flat-square) ![ChromaDB](https://img.shields.io/badge/ChromaDB-Vector%20Store-800080?style=flat-square) ![Google Gemini](https://img.shields.io/badge/Google%20Gemini-2.5%20Flash%20Lite-00bcd4?style=flat-square)

🔗 [Agentrix-ComES/AGENTRIX26-TEAM39-Neural-Surge](https://github.com/Agentrix-ComES/AGENTRIX26-TEAM39-Neural-Surge)

</details>

<details>
<summary><strong>02 &nbsp; MACHINE LEARNING / NLP &nbsp;&nbsp;&nbsp; Speaker Role Classifier</strong></summary>

**Classifies meeting participants into functional roles using hybrid linguistic heuristics and semantic embeddings.**

Standalone module for SpeechInSight. Predicts Lead, HR, Junior Developer, or Other roles from unstructured meeting utterances using XGBoost on 40-dimensional feature vectors (TF-IDF + Truncated SVD + handcrafted heuristics). Group-aware data splitting prevents leakage. MLflow-tracked experiments with Streamlit dashboard for qualitative testing.

![Python](https://img.shields.io/badge/Python-3.12-007acc?style=flat-square) ![XGBoost](https://img.shields.io/badge/XGBoost-Classification-1565c0?style=flat-square) ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML%20Pipeline-f57c00?style=flat-square) ![MLflow](https://img.shields.io/badge/MLflow-Experiment%20Tracking-00bcd4?style=flat-square) ![Streamlit](https://img.shields.io/badge/Streamlit-Dashboard-ff4b4b?style=flat-square)

🔗 [Denuwan392/speaker-role-classifier](https://github.com/Denuwan392/speaker-role-classifier)

</details>

<details>
<summary><strong>03 &nbsp; CLASSICAL AI / REASONING &nbsp;&nbsp;&nbsp; Leadership Expert System</strong></summary>

**Deductive reasoning engine analyzing leadership traits and styles from organizational conversations.**

Hybrid architecture: SWI-Prolog knowledge base for rules/facts/explanations, Python backend (PySwip, MVC) for scoring logic, Tkinter dark-themed GUI. Features dynamic speaker management, step-by-step reasoning traceability, weighted leadership rankings, and PDF report generation for individuals or groups.

![Python](https://img.shields.io/badge/Python-3.12-007acc?style=flat-square) ![Prolog](https://img.shields.io/badge/Prolog-SWI--Prolog-e65100?style=flat-square) ![PySwip](https://img.shields.io/badge/PySwip-Bridge-43a047?style=flat-square) ![Tkinter](https://img.shields.io/badge/Tkinter-GUI-8e24aa?style=flat-square)

🔗 [Denuwan392/leadership_expert_system](https://github.com/Denuwan392/leadership_expert_system)

</details>

<details>
<summary><strong>04 &nbsp; APPLIED NLP PIPELINE &nbsp;&nbsp;&nbsp; SpeechInSight</strong></summary>

**AI speech analysis pipeline: transcription, diarization, multimodal emotion recognition, and RAG-powered evaluation scoring.**

Processes audio/video through Wav2Vec2 CTC transcription, pyannote diarization, and fused emotion recognition (acoustic Wav2Vec2 + linguistic BERT + VADER sentiment). Scores five categories (Template, WarmUp, Praise, Suggest, Listen) via ChromaDB RAG with Gemini-2.5-flash. FastAPI backend + React 19 frontend with developer-mode provenance visualization.

![Python](https://img.shields.io/badge/Python-3.12-007acc?style=flat-square) ![FastAPI](https://img.shields.io/badge/FastAPI-Backend-55b62b?style=flat-square) ![React](https://img.shields.io/badge/React-19-61dafb?style=flat-square) ![ChromaDB](https://img.shields.io/badge/ChromaDB-Vector%20Store-800080?style=flat-square) ![Wav2Vec2](https://img.shields.io/badge/Wav2Vec2-Audio%20CTC-ff9800?style=flat-square)

🔗 [silham/Speach-Insight](https://github.com/silham/Speach-Insight)

</details>

<details>
<summary><strong>05 &nbsp; COMPETITION / AI SYSTEMS &nbsp;&nbsp;&nbsp; NEED TO GO — Synexis</strong></summary>

**Trilingual AI mobility assistant with agentic routing and RAG-powered transit search across Sri Lanka.**

SLAIC 2025 competition entry. LangGraph state machine routes between Sinhala/Tamil/English query classification, bus/train schedule search, response translation, and live tracking APIs. Persistent ChromaDB vector store eliminates re-indexing overhead. Monorepo with FastAPI backend and responsive Tailwind web app.

![Python](https://img.shields.io/badge/Python-3.12-007acc?style=flat-square) ![FastAPI](https://img.shields.io/badge/FastAPI-0.110%2B-55b62b?style=flat-square) ![LangGraph](https://img.shields.io/badge/LangGraph-Agentic%20Routing-e06c28?style=flat-square) ![ChromaDB](https://img.shields.io/badge/ChromaDB-Vector%20Store-800080?style=flat-square) ![Google Gemini](https://img.shields.io/badge/Google%20Gemini-2.5%20Flash%20Lite-00bcd4?style=flat-square)

🔗 [Denuwan392/SLAIC073_Synexis](https://github.com/Denuwan392/SLAIC073_Synexis)

</details>

<details>
<summary><strong>06 &nbsp; HARDWARE / ENGINEERING &nbsp;&nbsp;&nbsp; CDAKS Hardware Projects</strong></summary>

**Vision-based fruit cashier system integrating Arduino, computer vision models, and web interface.**

Automated checkout pipeline: Arduino handles weight sensors and actuator control, Python backend runs object detection/classification models, HTML frontend provides operator interface. Demonstrates full-stack IoT integration from embedded C++ to web UI.

![Python](https://img.shields.io/badge/Python-3.12-007acc?style=flat-square) ![Arduino](https://img.shields.io/badge/Arduino-Sensors-00979d?style=flat-square) ![C++](https://img.shields.io/badge/C%2B%2B-Embedded-00599c?style=flat-square) ![Computer Vision](https://img.shields.io/badge/Computer%20Vision-YOLO-ff6f00?style=flat-square)

🔗 [Denuwan392/cdaks_hardware_projects1](https://github.com/Denuwan392/cdaks_hardware_projects1)

</details>
