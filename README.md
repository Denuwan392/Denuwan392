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

> Repositories beyond the 6 pinned slots. Click to expand details.

<details open>
<summary><strong>01 &nbsp; AGENTIC AI &nbsp;&nbsp;&nbsp; Neural Surge</strong></summary>

**Multi-agent system for autonomous task planning, reasoning, and orchestration.**

Agentrix 2026 Finalist (HomeOS). An 8-node LangGraph state machine orchestrating inventory audit, spoilage analysis, semantic recipe matching via Qdrant RAG, budget enforcement, and reflection loops. Includes two-stage receipt parsing (RapidOCR + Gemini fallback), React Native mobile companion with voice assistant, and full LangSmith observability suite.

`Python` `FastAPI` `LangGraph` `Gemini 2.5 Flash` `Qdrant` `React Native` `LangSmith`

 [Agentrix-ComES/AGENTRIX26-TEAM39-Neural-Surge](https://github.com/Agentrix-ComES/AGENTRIX26-TEAM39-Neural-Surge)

</details>

<details>
<summary><strong>02 &nbsp; MACHINE LEARNING / NLP &nbsp;&nbsp;&nbsp; Speaker Role Classifier</strong></summary>

**Classifies meeting participants into functional roles using hybrid linguistic heuristics and semantic embeddings.**

Standalone module for SpeechInSight. Predicts Lead, HR, Junior Developer, or Other roles from unstructured meeting utterances using XGBoost on 40-dimensional feature vectors (TF-IDF + Truncated SVD + handcrafted heuristics). Group-aware data splitting prevents leakage. MLflow-tracked experiments with Streamlit dashboard for qualitative testing.

`Python` `XGBoost` `Scikit-learn` `MLflow` `Streamlit` `SMOTE`

🔗 [Denuwan392/speaker-role-classifier](https://github.com/Denuwan392/speaker-role-classifier)

</details>

<details>
<summary><strong>03 &nbsp; CLASSICAL AI / REASONING &nbsp;&nbsp;&nbsp; Leadership Expert System</strong></summary>

**Deductive reasoning engine analyzing leadership traits and styles from organizational conversations.**

Hybrid architecture: SWI-Prolog knowledge base for rules/facts/explanations, Python backend (PySwip, MVC) for scoring logic, Tkinter dark-themed GUI. Features dynamic speaker management, step-by-step reasoning traceability, weighted leadership rankings, and PDF report generation for individuals or groups.

`Python` `Prolog` `PySwip` `Tkinter`

🔗 [Denuwan392/leadership_expert_system](https://github.com/Denuwan392/leadership_expert_system)

</details>

<details>
<summary><strong>04 &nbsp; APPLIED NLP PIPELINE &nbsp;&nbsp;&nbsp; SpeechInSight</strong></summary>

**AI speech analysis pipeline: transcription, diarization, multimodal emotion recognition, and RAG-powered evaluation scoring.**

Processes audio/video through Wav2Vec2 CTC transcription, pyannote diarization, and fused emotion recognition (acoustic Wav2Vec2 + linguistic BERT + VADER sentiment). Scores five categories (Template, WarmUp, Praise, Suggest, Listen) via ChromaDB RAG with Gemini-2.5-flash. FastAPI backend + React 19 frontend with developer-mode provenance visualization.

`Python` `FastAPI` `React 19` `ChromaDB` `LangChain` `Wav2Vec2` `BERT` `Gemini` `FFmpeg`

🔗 [silham/Speach-Insight](https://github.com/silham/Speach-Insight)

</details>

<details>
<summary><strong>05 &nbsp; COMPETITION / AI SYSTEMS &nbsp;&nbsp;&nbsp; NEED TO GO — Synexis</strong></summary>

**Trilingual AI mobility assistant with agentic routing and RAG-powered transit search across Sri Lanka.**

SLAIC 2025 competition entry. LangGraph state machine routes between Sinhala/Tamil/English query classification, bus/train schedule search, response translation, and live tracking APIs. Persistent ChromaDB vector store eliminates re-indexing overhead. Monorepo with FastAPI backend and responsive Tailwind web app.

`Python` `FastAPI` `LangGraph` `ChromaDB` `TypeScript` `Docker`

🔗 [Denuwan392/SLAIC073_Synexis](https://github.com/Denuwan392/SLAIC073_Synexis)

</details>

<details>
<summary><strong>06 &nbsp; HARDWARE / ENGINEERING &nbsp;&nbsp;&nbsp; CDAKS Hardware Projects</strong></summary>

**Vision-based fruit cashier system integrating Arduino, computer vision models, and web interface.**

Automated checkout pipeline: Arduino handles weight sensors and actuator control, Python backend runs object detection/classification models, HTML frontend provides operator interface. Demonstrates full-stack IoT integration from embedded C++ to web UI.

`Python` `C++` `Arduino` `HTML` `Computer Vision`

🔗 [Denuwan392/cdaks_hardware_projects1](https://github.com/Denuwan392/cdaks_hardware_projects1)

</details>
