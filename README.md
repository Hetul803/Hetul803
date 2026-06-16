## Hi, I'm Hetul 👋

I'm a CS graduate student and builder focused on **AI infrastructure**, 
**vector retrieval systems**, and **autonomous agent tooling**.

My work spans performance-critical backend systems, large-scale 
experimentation pipelines, and governance tooling for AI agents.

---

## 🔧 What I'm building

### **Aegisure — AI Agent Governance & Audit Platform**
A vendor-neutral control and audit plane for AI coding agents 
(Claude Code, Codex, Cursor, Copilot).
- Intercepts and audits agent actions at the commit/PR layer
- CLI-first, integrates with existing GitHub workflows via webhooks
- Targets SOC2 compliance automation and enterprise AI governance
- Published on PyPI (v0.2.1)

➡️ [PyPI](https://pypi.org/project/aegisure/) · 
[GitHub](https://github.com/Hetul803/aegisure)

---

### **VecLite — Vector Database Engine (MCN Algorithm)**
A production-grade vector database built on Memory Compression 
Networks — achieving massive compression without sacrificing recall.
- **12.71× compression** with **exact recall parity** vs FAISS 
  (Recall@10 = 39.34% — identical to FAISS IndexFlatIP)
- Outperforms FAISS on fraud detection recall (4.30% vs 3.55%)
- Non-blocking index finalization via atomic snapshot swap — 
  zero downtime during 137s cluster rebuilds
- 0 errors across 23,269 concurrent queries during online mutation test
- Multi-tenant SaaS backend: 5 plan tiers, token-bucket rate limiting, 
  no external database

➡️ Live demo: [veclite.com](https://veclite.com) · 
[Backend (open source)](https://github.com/Hetul803/Veclite_backend)

---

### **GSIN — Global Strategy Intelligence Network**
A self-evolving algorithmic trading research platform for systematic 
strategy discovery.
- Evaluated **45,672 strategies** via genetic algorithm evolution 
  across 9 users
- Walk-forward backtesting + Monte Carlo simulation + 
  regime-aware scoring
- Discovered and diagnosed a WFA trade aggregation bug producing 
  systematically inflated win rates across the entire strategy corpus
- Multi-objective scoring: Sharpe, win rate, drawdown, 
  out-of-sample stability
- Full-stack: Next.js 14, FastAPI, Supabase, Railway

➡️ Live demo: [gsin.trade](https://gsin.trade)

---

## 🧠 Research

**Hyperspectral Imaging + ML** — Auburn University at Montgomery  
Targeting publication in *Atmospheric Measurement Techniques (AMT)*  
Single-camera design hypothesis confirmed via radiance transfer 
experiment. Key ML results complete.

---

## 🛠️ Tech stack

**Languages:** Python, TypeScript, SQL  
**AI/ML:** Vector search, genetic algorithms, walk-forward 
backtesting, scikit-learn, NumPy, Hugging Face  
**Backend:** FastAPI, Next.js, REST APIs, WebSockets  
**Infrastructure:** Supabase, Railway, Vercel, Docker  
**Tools:** Git, PyPI packaging, GitHub Actions  

---

## 📫 Connect

- LinkedIn: [linkedin.com/in/hetulkumar-patel](https://www.linkedin.com/in/hetulkumar-patel)
- Email: hetul.patel.career@outlook.com
- Portfolio: [hetul-patel-portfolio.vercel.app](https://hetul-patel-portfolio.vercel.app)
