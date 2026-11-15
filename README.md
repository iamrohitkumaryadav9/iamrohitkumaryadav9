# Hi, I'm Rohit Kumar 👋

**AI/ML Engineer** | Generative AI · Agentic AI · LLM Agents · RAG · Deep Learning | M.Tech CSE, IIIT Delhi

🎯 Open to a 6-month internship from **Jan 2027** and full-time roles from **July 2027**.

I build AI systems end-to-end, from framing the problem and the data to model training, evaluation and deployment. I care most about whether an AI system can be **trusted**: every answer backed by evidence, and every claim checked by an evaluation harness rather than a demo.

## 🔭 What I'm working on

- **[AEGIS](https://github.com/iamrohitkumaryadav9/ageis)** *(in progress)*: an ML incident-commander. It monitors a deployed model, diagnoses what went wrong, proposes fixes and validates them in a sandbox, with a human approving before anything ships.
- **[Signalist](https://github.com/iamrohitkumaryadav9/Stock_Tracker)** *(modernizing)*: full-stack stock-tracking app (Next.js, React, TypeScript) with real-time prices, alerts, watchlists and AI insights.
- **[SentinelAI](https://github.com/iamrohitkumaryadav9/SentinelAI)** *(in progress)*: a local-first AI agent that diagnoses performance incidents from kernel-level eBPF telemetry using open-weight LLMs. A pre-registered benchmark of 5 local models showed the best scored only 37.5–43.8% on hard diagnosis cases, so I declared the phase NO-GO instead of shipping an agent that sounds right and is wrong.

## 🚀 Featured projects

| Project | What it does | Stack |
|---|---|---|
| **[AgentRAG](https://github.com/iamrohitkumaryadav9/AgentRAG)** · [live demo](https://agentragpreregisteredllm.streamlit.app/) | 4-agent LangGraph RAG system (router → hybrid retriever → synthesizer → critic) evaluated on BEIR SciFact. Hybrid BM25 + dense retrieval raised **nDCG@10 from 0.670 to 0.711** (significant, Holm-corrected); a Gemini verifier reached **κ 0.67 vs expert labels**. A pre-registered test showed the LLM self-critique loop gave **no significant gain**, and pinned the bottleneck on the judge, not retrieval. | LangGraph, Gemini, BM25, FAISS, DeBERTa-NLI, FastAPI, Streamlit |
| **[TraceGuard](https://github.com/iamrohitkumaryadav9/traceguard)** · [live demo](https://traceguardfirstversionusingelliptical.streamlit.app/) | Evaluation-first AML investigation agent on the real Elliptic Bitcoin dataset: LightGBM detector at **0.79 PR-AUC** (vs 0.18 baseline), a LangGraph agent that drafts SAR-style reports where code renders every fact, and a critic that caught **98/98 injected faults** with 0/20 false rejections. | LightGBM, LangGraph, FAISS, BM25, Gemini, FastAPI, Streamlit |
| **[DocuGuard](https://github.com/iamrohitkumaryadav9/DocuGuard)** | Detects forged ID documents with a two-branch fusion CNN (RGB + Error-Level Analysis) trained from scratch: **94.0% accuracy, 0.990 ROC-AUC**, +24 pts over a Random Forest baseline. Grad-CAM explainability, privacy-safe synthetic data (no real PII). | PyTorch, OpenCV, FastAPI, Docker, pytest |
| **[RFLens](https://github.com/iamrohitkumaryadav9/rflens)** | Agentic RF data platform: agents and MCP tooling over RF datasets. v1 complete. | Python, MCP, LangGraph |
| **[MCP Tool Server & Agent Client](https://github.com/iamrohitkumaryadav9/MCP)** | MCP servers over stdio and Streamable HTTP with typed tools, a Python client and a LangChain agent that discovers and calls them, plus a gateway routing one client to multiple servers. | FastMCP, LangChain, Docker |

**Earlier work:** DocQA (PDF question answering with citations, compared with RAGAS).

## 🛠️ Tech

**GenAI & Agents:** LLM APIs (Gemini, OpenAI, Claude) · Ollama (local LLMs) · LangGraph · LangChain · RAG (hybrid BM25 + dense, reranking) · Multi-Agent Systems · MCP · Prompt Engineering · Structured Outputs (Pydantic) · LLM Evaluation (LLM-as-a-judge, RAGAS, pre-registered tests)  
**ML & Deep Learning:** PyTorch · scikit-learn · LightGBM · OpenCV · CNNs · Computer Vision · Explainable AI (Grad-CAM) · NumPy · Pandas  
**Vector Search:** FAISS · ChromaDB · Embeddings  
**Engineering:** Python · TypeScript · SQL · FastAPI · Streamlit · Next.js · React · Docker · GitHub Actions (CI/CD) · pytest · Linux · OpenTelemetry

## 💡 How I work

- **Evaluate before you trust.** Golden sets, pre-registered tests and CI gates, not cherry-picked demos. I report the null results too.
- **Refuse rather than hallucinate.** My AI systems say "insufficient evidence" when they don't know.
- **AI-assisted, human-judged.** I use AI coding agents heavily, and I design the tests that catch them when they're wrong.

## 🤝 Connect

[LinkedIn](https://www.linkedin.com/in/rohit-k-327030387/) · 📧 rohitiiitdm25@gmail.com
