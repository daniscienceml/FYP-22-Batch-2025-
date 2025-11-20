# LLM Base Sindhi Health Text Generator (RAG)

**Short description**  
This repository contains the Final Year Project: *LLM Base Sindhi Health Text Generator (RAG)* — a retrieval-augmented generation system designed to produce trustworthy, fluent Sindhi-language health text to improve access to healthcare information for Sindhi speakers.

## Contents
- `presentation/` — Project slides (PPTX): `FYP-22 Batch.pptx`
- `notebooks/` — Jupyter notebooks for dataset preparation, retrieval, and generation experiments
- `code/` — Core scripts: data processing, retriever (FAISS / Elastic/others), generator (fine-tuning / inference), and evaluation
- `data/` — Processed dataset (note: raw sensitive data is excluded; see license and dataset notes)
- `results/` — Evaluation logs, metrics, and sample outputs
- `README.md` — This file

> Presentation file (attached in repo): `/mnt/data/FYP-22 Batch.pptx`

## Project Overview
- **Goal:** Build a RAG-based system that retrieves relevant health passages and generates accurate Sindhi health text with high factuality and fluency.
- **Key components:** document retrieval (FAISS/Elastic), passage ranking, contextual prompt engineering, LLM-based generator, and automated + human evaluation.
- **Primary outcomes:** improved factual accuracy and usability in Sindhi health text generation; working prototype and evaluation framework included.

## How to run (quick start)
> These commands assume a Linux/WSL environment with Python 3.9+ and a GPU for model inference.

1. Clone the repo:
```bash
git clone <your-repo-url>
cd <repo-folder>
```

# Precision@k ≈ 0.82, Recall@k ≈ 0.76, F1 ≈ 0.79, factual accuracy ≈ 81%
Contributors

- [Muhammad Danyal Javed's GitHub](https://github.com/daniscienceml) — AI specialist & researcher
- [Muhammad Yousif's GitHub](https://github.com/Muhammad-Yousif) - Team Leader, Data Scientist & ML Engineer
- [Hajan's LinkedIn](https://www.linkedin.com/in/hajjan-dahre/) — Data analytics, databases, and ML researcher

- Supervisor: Dr. Azeem Ayaz Mirani — Assistant Professor, SBBU
  Assistant Professor, SBBU
  PhD (Information Technology)
  Your guidance, motivation, and continuous support kept us focused and confident at every stage.
  Thank you, sir, for believing in us and helping us grow as researchers and professionals.


## Contact:
- For questions or collaboration:
[Muhammad Danyal Javed](https://www.linkedin.com/in/danyal-ai/?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3BLXWBufgLQAKGhz1IdWcDnQ%3D%3D)
- Email: dani.ai.practitioner@gmail.com
