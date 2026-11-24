# Hi, I'm Rohit Kumar 👋

**AI/ML Engineer** | Generative AI · Agentic AI · LLM Agents · RAG · Deep Learning | M.Tech CSE, IIIT Delhi

🎯 Open to a 6-month internship from **Jan 2027** and full-time roles from **July 2027**.

I build AI systems end-to-end, from framing the problem and the data to model training, evaluation and deployment. I care most about whether an AI system can be **trusted**: every answer backed by evidence, and every claim checked by an evaluation harness rather than a demo.

## 🔭 What I'm working on

- **[AEGIS](https://github.com/iamrohitkumaryadav9/ageis)** *(in progress)*: an ML incident-commander. It monitors a deployed model, diagnoses what went wrong, proposes fixes and validates them in a sandbox, with a human approving before anything ships.
- **[RepoGym](https://github.com/iamrohitkumaryadav9/repogym)** *(in progress)*: an RL environment and evaluation harness for coding agents, built from real GitHub pull-request data rather than synthetic tasks.

## 🚀 Featured projects

| Project | What it does | Stack |
|---|---|---|
| **[Holdout](https://github.com/iamrohitkumaryadav9/holdout)** · [live demo](https://holdout.streamlit.app) | Self-auditing data-science agent for tabular CSVs: it seals a holdout before touching the data, turns LLM proposals into validated leakage-safe scikit-learn pipelines, runs **12 audit checks** for leakage and misleading metrics, and exports a standalone `pipeline.py`. Pre-registered benchmark (28 planted-trap tasks, 2 seeds): the audit layer caught **75.0%** of traps vs **35.7%** for an LLM judge (exact McNemar p = 0.012), at **~₹1.2/run vs ₹8.8** for a ReAct baseline. I report the misses too: the full agent didn't beat its own audits or ReAct. | LangGraph, Gemini, scikit-learn, LightGBM, Streamlit, OpenTelemetry, Hypothesis |
| **[AgentRAG](https://github.com/iamrohitkumaryadav9/AgentRAG)** · [live demo](https://agentragpreregisteredllm.streamlit.app/) | 4-agent LangGraph RAG system (router → hybrid retriever → synthesizer → critic) evaluated on BEIR SciFact. Hybrid BM25 + dense retrieval raised **nDCG@10 from 0.670 to 0.711** (significant, Holm-corrected); a Gemini verifier reached **κ 0.67 vs expert labels**. A pre-registered test showed the LLM self-critique loop gave **no significant gain**, and pinned the bottleneck on the judge, not retrieval. | LangGraph, Gemini, BM25, FAISS, DeBERTa-NLI, FastAPI, Streamlit |
| **[TraceGuard](https://github.com/iamrohitkumaryadav9/traceguard)** · [live demo](https://traceguardfirstversionusingelliptical.streamlit.app/) | Evaluation-first AML investigation agent on the real Elliptic Bitcoin dataset: LightGBM detector at **0.79 PR-AUC** (vs 0.18 baseline), a LangGraph agent that drafts SAR-style reports where code renders every fact, and a critic that caught **98/98 injected faults** with 0/20 false rejections. | LightGBM, LangGraph, FAISS, BM25, Gemini, FastAPI, Streamlit |
| **[RFLens](https://github.com/iamrohitkumaryadav9/rflens)** | Agentic RF data platform: LLM agents and MCP tool servers for querying and analysing RF datasets. v1 complete. | Python, MCP, LangGraph |
| **[DocuGuard](https://github.com/iamrohitkumaryadav9/DocuGuard)** | Detects forged ID documents with a two-branch fusion CNN (RGB + Error-Level Analysis) trained from scratch: **94.0% accuracy, 0.990 ROC-AUC**, +24 pts over a Random Forest baseline. Grad-CAM explainability, privacy-safe synthetic data (no real PII). | PyTorch, OpenCV, FastAPI, Docker, pytest |
| **[MCP Tool Server & Agent Client](https://github.com/iamrohitkumaryadav9/MCP)** | MCP servers over stdio and Streamable HTTP with typed tools, a Python client and a LangChain agent that discovers and calls them, plus a gateway routing one client to multiple servers. | FastMCP, LangChain, Docker |

**Earlier work:** [SentinelAI](https://github.com/iamrohitkumaryadav9/SentinelAI) (local-first agent diagnosing performance incidents from eBPF telemetry; a pre-registered benchmark of 5 open-weight LLMs led me to call the phase NO-GO rather than ship an unreliable agent) · [Signalist](https://github.com/iamrohitkumaryadav9/Stock_Tracker) (Next.js stock-tracking app with alerts, watchlists and AI insights) · DocQA (PDF question answering with citations, compared with RAGAS).

## 🛠️ Tech

**GenAI & Agents:** LLM APIs (Gemini, OpenAI, Claude) · Ollama (local LLMs) · LangGraph · LangChain · RAG (hybrid BM25 + dense, reranking) · Multi-Agent Systems · MCP · Prompt Engineering · Structured Outputs (Pydantic) · LLM Evaluation (LLM-as-a-judge, RAGAS, pre-registered tests)  
**ML & Deep Learning:** PyTorch · scikit-learn · LightGBM · AutoML / leakage-safe pipelines · OpenCV · CNNs · Computer Vision · Explainable AI (Grad-CAM) · NumPy · Pandas  
**Vector Search:** FAISS · ChromaDB · Embeddings  
**Engineering:** Python · TypeScript · SQL · FastAPI · Streamlit · Next.js · React · Docker · GitHub Actions (CI/CD) · pytest · Hypothesis · mypy · Linux · OpenTelemetry

## 💡 How I work

- **Evaluate before you trust.** Golden sets, pre-registered tests and CI gates, not cherry-picked demos. I report the null results too.
- **Refuse rather than hallucinate.** My AI systems say "insufficient evidence" when they don't know.
- **AI-assisted, human-judged.** I use AI coding agents heavily, and I design the tests that catch them when they're wrong.

## 🤝 Connect

[LinkedIn](https://www.linkedin.com/in/rohit-k-327030387/) · 📧 rohitiiitdm25@gmail.com
