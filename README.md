# Hi, I'm Siddardha Shayini 👋

**AI/ML Engineer** · creator of **OlaiEdge**, **HERM4AI** and **TAEL-Agent** · building applied AI that holds up under real-world constraints, on devices never meant to run AI.

📍 Hyderabad, India &nbsp;|&nbsp; 🟢 Open to AI/ML and software engineering roles

[![Portfolio](https://img.shields.io/badge/Portfolio-siddardhashayini.github.io-DD9152)](https://siddardhashayini.github.io/SiddardhaShayini/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/siddardha-shayini-734639317/)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-SiddardhaShayini-FFD21E?logo=huggingface&logoColor=black)](https://huggingface.co/SiddardhaShayini)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-4285F4?logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?hl=en&user=eQvxPZIAAAAJ)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0002--6909--073X-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0002-6909-073X)

---

### 🧠 About Me

* 💼 **Role:** AI/ML Engineer specializing in Generative AI, Agentic AI, LLM fine-tuning, agent memory, Computer Vision, and edge/local LLM inference.
* 🔬 **Focus:** Local-first, privacy-preserving AI: fine-tuning small models (QLoRA), serving them as GGUF on CPU-only hardware, and wrapping them in reliable agent runtimes (tool calling, persistent memory, context management).
* 🎓 **Education:** B.Tech in CSE (AI & ML), Vignan Institute of Technology and Science, Hyderabad (2022–2026).
* 👀 **Interests:** Applied AI, Agentic AI, Local LLMs, NLP, Computer Vision, MLOps.

---

### 🚀 Featured Projects

| Project | What it is | Stack |
|---|---|---|
| ⚡ **[OlaiEdge](https://github.com/SiddardhaShayini/OlaiEdge)** *(formerly FastAgent · Open Source, MIT)* | Headless, drop-in local LLM runtime (SDK + background daemon) for desktop apps. Cuts steady-state prompt latency from **~3,500 ms to ~73 ms** on a CPU-only, 8 GB machine with **zero OOM failures** in long tool loops. Adds a RAM-budget enforcer, process watchdog, multi-tab slot cache, and offline signed licensing; **26 tests**. [Paper](https://doi.org/10.5281/zenodo.22918273) | Python, llama.cpp, LCP slot caching, 8-bit KV-cache quantization, GBNF, Electron/Tauri/Flutter SDKs |
| 🧠 **[HERM4AI](https://github.com/SiddardhaShayini/HERM4AI)** *(Open Source, MIT)* | Human-like Evolving & Reasoning Memory for AI: a model-free cognitive memory architecture for LLM agents (valid-time store, 7-slot working memory, associative knowledge graph, sleep-phase consolidation, ACT-R arbitration, Q-MIA provenance). Shows flat vector RAG suffers temporal inversion (41.7% obsolete retrievals), dual collapse (9.0% top-1 at 10k passages), and prompt poisoning (33–40% hallucination); HERM4AI reaches **100% on 7 benchmark suites at <2 ms CPU latency**; **36 tests**. [Paper](https://zenodo.org/records/23978209) | Python, SQLite, Knowledge Graphs, ACT-R |
| 🛠️ **[TAEL-Agent](https://github.com/SiddardhaShayini/TAEL_Agent)** · [🤗 Model](https://huggingface.co/SiddardhaShayini/TAEL_Agent) | Privacy-preserving local autonomous SWE agent. IBM Granite 3.1 2B Instruct fine-tuned with QLoRA on a 29,900-sample, three-phase curriculum, deployed as a 4-bit GGUF. Runtime has 9-category task routing, 10 sandboxed workspace tools, four-pillar persistent memory, and context-budget management. VS Code extension with refactoring, diff previews, and autonomous tool execution. **8/8 benchmark-domain passes** in the reported evaluation suite. | QLoRA, GGUF, Ollama, TypeScript, VS Code API |
| 🐾 **[WildGuardAI](https://github.com/SiddardhaShayini/WildGuardAI-Real-Time-Wildlife-Conflict-Prediction)** *(IEEE Xplore, 2026)* | Real-time wildlife-conflict prediction from camera feeds with GPS-based alerts for forest officers and villagers. | YOLOv12n, BoT-SORT, Kalman Filter, Flask, SQLite |
| 🧓 **[JivanMitra](https://github.com/SiddardhaShayini/JivanMitra---Offline-First-Intelligent-AI-Assistant-using-RAG-Agents)** | Offline-first, voice-enabled, multilingual AI companion for elders in India. | LangChain, RAG, agentic AI |

**More projects:**
* 🌍 [Terrascope AI](https://terrascope-ai.pages.dev/) *(live)*: zero-paid-API platform scoring any city or coordinate across 16 socio-environmental dimensions and 5 personas, using rule-based scoring over Open-Meteo, OpenStreetMap Overpass, and Wikipedia data. Deployed on Cloudflare Pages.
* 🔒 [Personal AI Agent](https://github.com/SiddardhaShayini/Personal-AI-Agent): local-first, privacy-focused assistant (Ollama, LanceDB).
* 📚 [Offline Deep Research Agent](https://github.com/SiddardhaShayini/Offline-Deep-Research-Agent-using-Ollama-Mistral-and-LangChain): reasons over documents entirely offline (Ollama, Mistral, LangChain).
* 🧑‍💼 [TalentRank AI](https://github.com/SiddardhaShayini/TalentRank-AI) ([live demo](https://talent-rank-ai-mocha.vercel.app/)): AI-assisted recruiting platform with JWT auth, AI candidate ranking, and analytics (React 18, Vite, Express, SQLite).
* 🪶 [Hearthwren](https://github.com/SiddardhaShayini/Hearthwren) *(in development)*: local-first, CPU-only AI coding agent.

Full list in the [portfolio archive](https://siddardhashayini.github.io/SiddardhaShayini/#archive).

---

### 📄 Research

* **HERM4AI: Human-like Evolving & Reasoning Memory for Artificial Intelligence** — Zenodo, 2026 · [Read the paper](https://zenodo.org/records/23978209)
* **Hardware-Adaptive Inference Orchestration: Zero-Overhead Local LLM Agents on Resource-Constrained Edge Devices** (OlaiEdge) — Zenodo, 2026 · [Read the paper](https://doi.org/10.5281/zenodo.22918273)
* **Wild Guard AI: Real-Time Wildlife Conflict Prediction** — IEEE Xplore, ICICI 2026 · [View on IEEE Xplore](https://ieeexplore.ieee.org/author/626245326465493)

---

### 🤝 Open Source

* **OlaiEdge**, **HERM4AI** and **TAEL-Agent:** Creator and maintainer.
* **[sklearn-genetic-opt](https://github.com/rodrigo-arenas/Sklearn-genetic-opt):** Contributor. Documented parallel processing with `n_jobs` in `GASearchCV` (PR #178 merged, resolving Issue #152).

---

### 🛠️ Tech Stack & Skills

| Area | Tools |
|---|---|
| **Languages** | Python, TypeScript, JavaScript, Java, C, C++, SQL |
| **AI/ML & Vision** | LLMs, Agentic AI, LLM Fine-Tuning (QLoRA/LoRA), RAG, NLP, Computer Vision, scikit-learn, TensorFlow, YOLOv12n, BoT-SORT, Kalman Filter, Vector Embeddings, Knowledge Graphs |
| **LLM & Agent Systems** | Ollama, llama.cpp, GGUF, KV-Cache Quantization, Prompt Caching, Grammar-Constrained Decoding (GBNF), Tool Calling, Persistent Agent Memory, ReAct |
| **Frameworks & Tools** | FastAPI, Flask, LangChain, LangGraph, React, Node.js, Streamlit, LanceDB, ChromaDB, SQLite, Hugging Face, Git/GitHub, VS Code Extension Development, REST APIs |

---

### 🏅 Certifications & Training

* Oracle Certified Foundations Associate: Agentic AI
* Deep Research with LangGraph (LangChain Academy)
* Hugging Face Agents Course
* Databricks Fundamentals (Databricks Academy)
* TCS iON NQT (IT): Qualified

---

### 📫 Get in Touch

Open to AI/ML engineering and software roles: [LinkedIn](https://www.linkedin.com/in/siddardha-shayini-734639317/) · [Email](mailto:siddardhashayini3@gmail.com) · [Portfolio](https://siddardhashayini.github.io/SiddardhaShayini/)

---

### ⚡ Fun Fact

I enjoy turning **complex AI ideas into simple, usable systems**, especially for people in low-resource settings and for devices that were never meant to run AI.