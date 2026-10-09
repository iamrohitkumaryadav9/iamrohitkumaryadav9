# Hi, I'm Rohit Kumar 👋

**AI/ML Engineer** | Generative AI · LLM Agents · RAG · Deep Learning | M.Tech CSE, IIIT Delhi

I build AI systems end-to-end, from framing the problem and the data to model training, evaluation and deployment. I care most about whether an AI system can be **trusted**: every answer backed by evidence, and every claim checked by an evaluation harness rather than a demo.

## 🔭 What I'm working on

- **[SentinelAI](https://github.com/iamrohitkumaryadav9/SentinelAI)** *(in progress)*: a local-first AI agent that diagnoses performance incidents from kernel-level eBPF telemetry using open-weight LLMs. A pre-registered benchmark of 5 local models showed the best scored only 37.5–43.8% on hard diagnosis cases, so I declared the phase NO-GO instead of shipping an agent that sounds right and is wrong.

## 🚀 Featured projects

| Project | What it does | Stack |
|---|---|---|
| **[DocuGuard](https://github.com/iamrohitkumaryadav9/DocuGuard)** | Detects forged ID documents with a two-branch fusion CNN (RGB + Error-Level Analysis) trained from scratch: **94.0% accuracy, 0.990 ROC-AUC**, +24 pts over a Random Forest baseline. Grad-CAM explainability, privacy-safe synthetic data (no real PII). | PyTorch, OpenCV, FastAPI, Docker, pytest |
| **[AgentRAG](https://github.com/iamrohitkumaryadav9/AgentRAG)** | Multi-agent RAG service (router → retriever → synthesizer → critic) that returns cited answers with confidence scores, or refuses when evidence is insufficient. Golden-set eval harness gated in CI. | LangGraph, FAISS, Gemini, Pydantic, OpenTelemetry |
| **DocQA** | RAG question answering over PDFs with source citations and low-confidence refusal; chunking strategies and LLM/embedding providers compared with RAGAS. | LangChain (LCEL), ChromaDB, FastAPI, RAGAS |
| **Quantis** | Real-time AI stock-analysis platform: live WebSocket prices, Gemini-generated company summaries, strategy backtesting and paper trading. | Next.js, TypeScript, MongoDB, Gemini API |

## 🛠️ Tech

**GenAI & Agents:** LLM APIs (Gemini, OpenAI, Claude) · Ollama (local LLMs) · LangGraph · LangChain · RAG · Multi-Agent Systems · Prompt Engineering · Structured Outputs (Pydantic) · LLM Evaluation (RAGAS, golden sets)
**ML & Deep Learning:** PyTorch · scikit-learn · OpenCV · CNNs · Computer Vision · Explainable AI (Grad-CAM) · NumPy · Pandas
**Vector Search:** FAISS · ChromaDB · Embeddings
**Engineering:** Python · TypeScript · SQL · FastAPI · Next.js · React · Docker · GitHub Actions (CI/CD) · pytest · Linux · OpenTelemetry

## 💡 How I work

- **Evaluate before you trust.** Golden sets, pre-registered tests and CI gates, not cherry-picked demos.
- **Refuse rather than hallucinate.** My AI systems say "insufficient evidence" when they don't know.
- **AI-assisted, human-judged.** I use AI coding agents heavily, and I design the tests that catch them when they're wrong.

## 🤝 Connect

[LinkedIn](https://www.linkedin.com/in/rohit-k-327030387/) · 📧 rohitiiitdm25@gmail.com
