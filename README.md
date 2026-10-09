# Bilal Delais

**AI / Data Science Engineer — applied AI for aerospace and industry**
IMT Mines Alès (AI & Data Science), graduating November 2026 · Open to full-time roles in ML / GenAI from November 2026 (Paris · Toulouse · Bordeaux · Switzerland · international)

I build ML systems that start from a messy engineering problem and end as a tool a team actually uses — from deep-learning anomaly detection on rocket-engine test data to LLM assistants running in production for a real client.

---

### Selected work

**Anomaly detection on rocket-engine test benches** — *ArianeGroup, end-of-studies internship (Mar – Jul 2026)*
Multivariate time-series anomaly detection on Vulcain, Vinci and Prometheus test-bench data. Transformer-GAN, TranAD and LSTM-Autoencoder in PyTorch; data scarcity (~300 tests, fewer than 10 real anomalies) handled with synthetic anomaly generation and transfer learning; per-test train/test split, Optuna tuning, SHAP-based diagnostics and automatic pre-reports for test engineers.
<sub>Industrial, confidential work — no public code.</sub>

**Learning to correct the SGP4 orbital propagator — and auditing the result** — *academic project (Dec 2025), revisited in 2026*
We trained MLP, LSTM/GRU and Transformer models to learn SGP4's residual error against JPL Horizons ephemerides (ISS, Hubble). Revisiting the pipeline, I found that most of that "error" was a time-synchronisation bug in our own data (median ISS error 4.1 km → 0.085 km once fixed) and that Horizons is not an independent reference for these objects. The repository documents the fix, the corrected datasets and why the original model results should not be read as a correction of SGP4.
[Code & analysis](https://github.com/bilaldls/IMT_DeepLearning_project)

**Agentic RAG over ESA's ECSS space standards** — *personal project, in progress*
An agent that answers engineering questions over the ECSS standards corpus, with retrieval, tool use and cited sources.
<sub>Work in progress — repository will be published with the first release.</sub>

**Generative AI in production** — *Ochralab, architecture firm, Marrakech (Sept – Nov 2026)*
Fully local LLM assistant (Gemma via Ollama on a dedicated RTX 3060) over heterogeneous sources (PDF plans and quotes, Excel, e-mails), plus a quote-comparison app built on the Claude API, deployed on the firm's workstations — weekly time spent on quotes cut by about half.

**Measuring domain shift for few-shot object detection** — *academic research (Feb 2026)*
A Domain Shift Index combining few-shot classifiers on ResNet-50 embeddings with Wasserstein-1 and MK-MMD distances, to rank 13 source datasets by proximity to aerial targets (DOTA, DIOR). 10-shot DOTA → DIOR transfer with Detectron2: AP 41.97 / AP50 63.98.
[Code](https://github.com/cyyyp100/Domain_Shift_Study) · [Report (PDF)](https://bilaldelais.com/assets/reports/adaptation-de-domaine.pdf)

**Surrogate model for production processes** — *Airbus × 2iA hackathon (2025)*
Predicting process satisfaction from simulated data with 7,500+ raw features: constant/collinear feature pruning down to 5,528 variables, then LightGBM / CatBoost ensembles with residual learning.
[Code](https://github.com/bilaldls/IMT_Kaggle_Airbus)

---

### Toolbox

- **ML / Deep learning** — PyTorch, TensorFlow, scikit-learn, Hugging Face Transformers, Optuna, SHAP
- **Generative AI** — LLM APIs (Claude), local LLMs (Ollama, Gemma), RAG, agents & tool use, LangChain, ChromaDB
- **Data & engineering** — Python, SQL, Pandas, NumPy, Git, GitLab CI, Linux, Jupyter
- **Engineering background** — propulsion R&D at Agena Space (SolidWorks, test-bench assembly), CPGE PSI

---

### Contact

[bilaldelais.com](https://bilaldelais.com) · [LinkedIn](https://www.linkedin.com/in/bilal-delais-8903b518b)
