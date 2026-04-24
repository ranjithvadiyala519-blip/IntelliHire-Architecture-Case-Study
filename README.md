# IntelliHire: Bridging Talent Acquisition Strategy with AI Intelligence

## 📌 Project Overview
IntelliHire is a comprehensive AI-powered application designed from a recruiter's perspective to streamline the end-to-end hiring workflow. Having spent 15 years in the US IT Recruitment industry, I built this suite to address specific gaps in traditional search and analysis tools—focusing on contextual understanding rather than just keyword matching.

---

## 🔍 Module 1: IntelliSearch (High-Scale Hybrid Retrieval)
The search pipeline is designed to handle high-volume data with the precision required for specialized IT roles.

### Technical Specifications:
* **Vector Infrastructure:** Utilizing **Voyage-3** for high-fidelity embeddings and **Qdrant** hosted on a Google Cloud VM.
* **Scale:** Processing over **700,000 resumes**, resulting in a pipeline of approximately **270 Million vectors** (13.5M Dense and 13.5M Sparse vectors per index).
* **Hybrid Logic:** Executes a dual-stream search combining Semantic (contextual meaning) and Sparse (technical keyword) retrieval.
* **RRF Reranking:** Implements **Reciprocal Rank Fusion (RRF)** to merge result sets, ensuring the most balanced and relevant candidates are prioritized.
* **LLM Suitability Scoring:** Candidates are processed by a high-reasoning LLM to assign a percentage-based suitability score, allowing recruiters to filter by tiers (90%+, 80%+, etc.).

---

## 📊 Module 2: IntelliAnalysis (Deep Contextual Evaluation)
This module automates the analytical heavy lifting of the recruitment lifecycle:

* **JD Analysis:** Deep extraction of core requirements, required tech stacks, and soft skill expectations.
* **Resume vs. JD Evaluation:** A multi-layered assessment of how a candidate's specific journey aligns with a job's needs.
* **Resume Comparison:** Side-by-side evaluation of multiple candidates to highlight unique strengths and potential gaps.
* **Interview Intelligence:** * Automated **Interview Question Generation** tailored to the candidate's specific resume and the JD.
    * **Interview Analysis** to evaluate feedback and assess technical/cultural fit.
* **Automated Outreach:** Generation of hyper-personalized, context-aware emails to increase candidate engagement rates.

---

## 🤖 The AI Stack & Methodology
As a non-technical founder and AI practitioner, I utilize a "Multi-Model" development workflow to ensure both high-reasoning capability and production reliability.

* **Primary Analysis Engine:** DeepSeek (Current 2026 Release).
* **Production Fallback:** Gemini 2.5 Pro (Ensuring zero-downtime and consistent performance).
* **AI-Assisted Development:** Built using **Cursor**, leveraging **Opus 4.6** for complex logic implementation and **Gemini 3.1 Thinking** for architectural brainstorming and problem-solving.

---

## 📺 Product Demonstration
Below is a walkthrough of the IntelliHire interface, showcasing the IntelliSearch pipeline and IntelliAnalysis features in action.

[DRAG AND DROP YOUR VIDEO FILE HERE]

---

## 💡 Why I Built This
Traditional recruitment platforms often struggle with the nuances of technical roles. IntelliHire is my attempt to bridge the gap between high-scale data processing and the "human intuition" I've developed over 15 years in the industry. It is built by a recruiter, for recruiters.
