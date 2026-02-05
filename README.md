# LLM Projects (Academic & Applied Portfolio)

This repository is an academic-oriented portfolio of **Large Language Model (LLM)** projects with an emphasis on **applied NLP**, **interactive systems**, and (where applicable) **agentic / tool-using workflows**.  
The goal is to demonstrate end-to-end competence in building practical LLM-based systems—from data preparation and prompting strategies to evaluation, reliability, and deployment-ready design.

> Context: maintained as part of my transition from Electrical Engineering to Computer Science with a strong interest in **Applied AI & Interactive Systems** and research-oriented work.

---

## What You’ll Find Here

Depending on the project, notebooks / codebases typically include:

- **LLM-powered applications**
  - enterprise-style assistants / knowledge chatbots (RAG-style pipelines if included)
  - task-oriented assistants (classification, extraction, summarization, QA)
- **Agentic AI workflows** (if included)
  - tool calling / function execution
  - multi-step reasoning pipelines with explicit state & memory (engineering-focused)
- **Experimentation & evaluation**
  - prompt iterations, ablations, and comparison baselines
  - qualitative + quantitative evaluation (accuracy, factuality checks, latency, cost)
- **Engineering practices**
  - modular code, configs, reproducibility notes
  - safety considerations and failure-mode analysis

---

## Project Index

> Replace the placeholders below with your actual folders/notebooks.

1. **Project A — [Name]**
   - Goal: …
   - Methods: …
   - Key results: …
   - Notes: dataset / prompt strategy / evaluation

2. **Project B — [Name]**
   - Goal: …
   - Methods: …
   - Key results: …
   - Notes: …

(…)

---

## Methodology (Research-Oriented)

Across projects, I aim to follow a consistent experimental workflow:

1. **Problem formulation**  
   Clear task definition, constraints (latency/cost), and expected outputs.
2. **Baselines**  
   Simple prompts / non-LLM baseline or smaller model baseline when feasible.
3. **Iterative design**
   - prompt engineering (instruction + formatting + few-shot when helpful)
   - retrieval design (chunking, embeddings, reranking) if RAG is used
   - agent design (tools, policies, guardrails) if tool-use is used
4. **Evaluation**
   - task metrics (when labels exist)
   - error taxonomy (hallucination, retrieval misses, format errors, tool errors)
   - robustness checks (edge cases, adversarial prompts, long-context cases)
5. **Documentation**
   Decisions, limitations, and next steps are recorded inside each project.

---

## Tech Stack

Typical stack (varies per project):

- **Python 3**, Jupyter / scripts
- LLM tooling: `transformers`, OpenAI-compatible SDKs, or other providers
- RAG tooling (if used): vector stores + embedding models
- NLP/ML: `numpy`, `pandas`, `scikit-learn`
- Visualization: `matplotlib`, `seaborn`
- Optional: Docker, FastAPI/Streamlit for demos

---
