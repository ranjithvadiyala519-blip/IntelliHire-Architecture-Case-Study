# IntelliHire: Bridging Talent Acquisition Strategy with AI Intelligence

## 📌 Project Overview
IntelliHire is a comprehensive AI-powered application designed from a recruiter's perspective to streamline the end-to-end hiring workflow. Having spent 15 years in the US IT Recruitment industry, I built this suite to address specific gaps in traditional search and analysis tools—focusing on contextual understanding rather than just keyword matching.

---

## 🔍 Module 1: IntelliSearch (High-Scale Hybrid Retrieval)
To solve for the complexity of IT hiring, I designed a multi-layered retrieval strategy that transitions from high-volume vector search to deep AI-led reasoning, ensuring high-fidelity candidate matches at scale.

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
* **Resume vs. JD Suitability:** Assesses the alignment of a resume against a specific JD, providing a detailed suitability analysis along with a suitability score. 
* **Resume Comparison:** Analyzes multiple resumes against a specific job requirement to generate a relative assessment of strengths and alignment gaps across the candidate pool.
* **Interview Intelligence:**
    * **Tailored Question Generation:** Outputs personalized interview questions based on the candidate's specific resume and the job description.
    * **Interview Analysis:** Analyzes interview transcripts to evaluate the candidate's technical answers and cultural fit.
    * **Complete Candidate Assessment:** Combines the initial resume analysis with the actual interview performance to give a final, unified recommendation.
* **Automated Outreach:** Generation of hyper-personalized, context-aware emails to increase candidate engagement rates.

---

## 🤖 The AI Stack & Methodology
As a Senior TA Professional and AI practitioner, I utilize a multi-model "Vibe Coding" workflow to ensure both high-reasoning capability and production reliability.

### **Production Architecture**
* **Primary Engine:** All IntelliHire functions utilize **DeepSeek** reasoning models for deep candidate and JD analysis.
* **Reliability Fallback:** **Gemini 2.5 Pro** serves as the primary failover to ensure consistent performance and high availability.

### **Development Workflow**
* **IDE Implementation:** Developed primarily in **Cursor**. I utilize **Anthropic Opus 4.6** for high-complexity coding tasks and rely on **Auto-model routing** for standard feature implementation.
* **Strategic Planning:** Leveraged **Gemini 3.1 Pro** and **Gemini 3.1 Thinking** for initial architectural brainstorming, logic planning, and roadmapping.
* **Infrastructure & Data Orchestration:** Utilized **Gemini** for specialized code generation and deployment tasks conducted outside the IDE, specifically for orchestrating the **Google Cloud Platform (GCP)** environment and the **Qdrant** vectorization pipeline.

---

## 💡 The Vision Behind IntelliHire
While IntelliHire serves a practical purpose, its origin is rooted in a deeper conviction. I believe Artificial Intelligence is a milestone in human history as profound as the discovery of fire, the invention of the printing press/Electricity, or the dawn of the internet.

While I missed the earlier IT and internet revolutions, to some extent, I am determined not to miss the AI bus. Developing IntelliHire has demonstrated that with an AI-assisted workflow, I can independently build applications that would have required a team of software developers and years of specialized training in the pre-AI era. 

While this project focused on recruitment, my confidence in building for other sectors is rooted in my natural ability to quickly grasp the logic and nuances of diverse industries. AI has effectively removed the technical friction, allowing me to translate my multidisciplinary understanding into functional, high-scale software solutions. To me, AI is the ultimate equalizer, shifting the focus from technical limitations to the ability to understand and architect complex systems.

