# Hi, I'm Jimin Park

I'm an AI/ML Engineer specializing in LLM evaluation and retrieval-augmented generation for regulated, high-stakes domains. I build LLM systems that can be trusted — and measured: citation-grounded RAG pipelines, automated evaluation suites, and benchmarks that show exactly where models break.

## What I Do
- Design LLM & agent evaluation: benchmarks, ground-truth datasets, automated eval suites
- Build RAG pipelines with citation grounding and refusal handling for compliance-critical use cases
- Run multi-LLM ensembles and fully local/private deployments (Ollama)
- Apply 3+ years of production ML experience from national-scale research analytics

## Experience
**AI Engineer — Labelbox (via Alignerr)** | Feb 2026 – Present  
Calibrate multi-LLM evaluation batches producing RLHF ground truth for frontier models; build human-in-the-loop workflows validating cross-model consistency for agentic AI reliability.

**AI Engineer Intern — IBM** | May 2025 – Aug 2025  
Engineered a RAG pipeline automating OSCAL / NIST 800-53 compliance mapping, resolving an 80% manual cross-referencing bottleneck; diagnosed data-coverage gaps via segmented precision–recall analysis and built a Power BI dashboard for MLOps monitoring.

**Machine Learning Engineer — National Research Institutes of Korea (KIST, KISTEP, KIPF, KIET)** | Jul 2020 – Apr 2024  
Built an LDA topic-modeling pipeline that secured a $45M+ national R&D budget expansion (published at SETM); deployed SBERT/XGBoost semantic search boosting Web of Science search efficiency by 49%; productionized a Random Forest evaluation framework cutting decision cycles by 85% and saving $120K.

**Software Engineer — Republic of Korea Army** | Feb 2017 – Feb 2019  
Architected military LMS/MOOC infrastructure, optimizing data delivery and system reliability.

## Featured Projects
**[NIST 800-53 Compliance RAG with Gap Detection](https://github.com/ujpjm30/NIST-Compliance-RAG-with-Gap-Detection)**  
Fully local RAG pipeline (Llama 3 via Ollama + FAISS, zero data egress) enforcing inline control-ID citations — the model refuses rather than hallucinates when retrieval finds no support. Score-based semantic gap detection plus an automated evaluation suite measuring ~87% classification accuracy.

**[LLMonopoly — Agentic LLM Evaluation Benchmark](https://github.com/ujpjm30/LLMONOPOLY_EMSEMBLE-MODEL)**  
Simulation-based benchmark evaluating 5 open-weight LLMs (Llama 3.1, Qwen 2.5, Mistral, Phi-3, Gemma 2) as autonomous agents in long-horizon decision-making. An ensemble voting agent outperformed every single model with a 60% win rate against a heuristic baseline. Run on H100 GPUs (Georgia Tech PACE).

**[Knowledge Distillation for TinyML / Embedded AI](https://github.com/ujpjm30/Knowledge-Distillation-for-TinyML-Embedded-AI)**  
Compressed a 95M-parameter Transformer into a 90K-parameter student model while sustaining 94.8% accuracy for on-device inference, with ablations over distillation temperature and loss weighting.

## Technical Skills
- **Languages & Core ML:** Python, SQL, JavaScript, PyTorch, Transformers, SentenceTransformers
- **LLM Engineering:** RAG pipelines (FAISS, LangChain), LLM & agent evaluation / benchmark design, RLHF ground-truth calibration, multi-LLM ensembles, prompt engineering (citation grounding, refusal handling)
- **Infra & MLOps:** Docker, FastAPI, PostgreSQL, AWS, CI/CD (GitHub Actions), model monitoring

## Interests
- **LLM Evaluation & Reliability:** benchmarks and eval pipelines that measure whether AI systems can actually be trusted in production
- **Agentic Systems:** evaluating and orchestrating LLMs on long-horizon, multi-step tasks
- **AI for Regulated Domains:** security & compliance (NIST 800-53, OSCAL), local/private deployment, hallucination-safe design

## Contact
Email: jimin.park.mlds@gmail.com  
Portfolio: https://jimin-park.me  
LinkedIn: https://linkedin.com/in/jimin-park-ml
