# 📊 Module 15 Public Report

## Experimental Validation of AI-Powered Adaptive Learning System

---

## 🌟 Executive Summary

Module 15 represents the **experimental validation phase** of the AI-powered adaptive learning platform developed across previous modules. This stage consolidated all technical, pedagogical, and methodological efforts into a real-world classroom experiment conducted at **Colégio Santa Escolástica**, involving sixth-to-eighth-grade students.

Through a **five-sprint framework**, this phase focused on design, deployment, and real-world validation — measuring educational effectiveness, user experience, and system performance.

**Key Achievement:** Successful controlled experiment demonstrating the **pedagogical potential** of AI-powered adaptive learning while identifying **key optimization areas** for LLM performance and UX design.

**Impact:** One of the first **empirical validations of generative AI in K-12 education** in Brazil, offering evidence-based guidelines for scalable classroom adoption.

---

## 🛠️ Experimental Framework & Objectives

### Primary Research Goals

* Measure **learning outcomes** with pre/post-test methodology
* Assess **user experience** and classroom usability
* Identify **system limitations** and optimization needs
* Develop **guidelines** for educational AI implementation

### Validation Methodology

1. **Control vs. Experimental Groups**
2. **Pre/Post-Test Assessments** — knowledge gain evaluation
3. **Qualitative Observation** — behavior and interaction analysis
4. **System Monitoring** — performance, latency, and usability

---

## 📈 Sprint-by-Sprint Validation Journey

### 🤠 Sprint 1 — Project Planning and Setup

* Defined project scope, timeline, and metrics
* Created documentation and repository structure
* Established Agile sprint workflow
* Aligned pedagogical and technical foundations

**Outcome:** Clear roadmap and research alignment for all following sprints.

---

### 📚 Sprint 2 — Experimental Design Documentation

* Detailed control/intervention design (EN/PT)
* Structured pre- and post-test instruments
* Selected schoolbook geometry content (Polygons chapter)
* Defined qualitative interview and observation methods

**Outcome:** Comprehensive experimental blueprint ready for execution.

---

### ⚙️ Sprint 3 — System Migration and Infrastructure

* Migrated from **NetworkX** to **Neo4j** for scalability
* Integrated **Google Gemini 2.5** for reasoning and OCR tasks
* Processed geometry curriculum via extraction pipeline
* Prepared **parent consent form (TCLE)**
* Submitted and revised systematic review for journal publication

**Outcome:** System ready for classroom testing with improved robustness and performance.

---

### ☁️ Sprint 4 — Cloud Deployment

* Frontend: **Vercel** hosting with SSL + global CDN
  🔗 [tcc-front-eight.vercel.app/dashboard](https://tcc-front-eight.vercel.app/dashboard)
* Backend: **Render** hosting with scaling + logging
  🔗 [ai-education-api-vb0m.onrender.com/docs](https://ai-education-api-vb0m.onrender.com/docs)
* Configured CI/CD, environment variables, and monitoring

**Outcome:** Fully operational production-ready infrastructure.

---

### 🤮 Sprint 5 — Experimental Implementation and Analysis

* Conducted **exploratory classroom experiment** (12 students: 6 control, 6 experimental)
* Collected quantitative (tests) and qualitative (observation) data
* Analyzed performance and user feedback
* Identified key improvement areas (UX, latency, visual design)

**Outcome:** Real-world validation achieved with actionable insights.

---

## 🔬 Experimental Implementation & Results

**Location:** Colégio Santa Escolástica
**Duration:** 90 minutes
**Groups:** 6 control, 6 experimental
**Topic:** Geometry — Perimeter and Unit Conversions
**Materials:** `apostila.pdf`, `pre-teste.pdf`, `post-teste.pdf`, `tcle.pdf`

### Methodology

1. **Pre-Test** (15 min)
2. **Intervention** (60 min) — platform vs. traditional instruction
3. **Post-Test** (15 min)

### Key Findings

* Students preferred **teacher-led lessons** for clarity
* AI platform effective as **review and reinforcement tool**
* Notable **learning improvement** between pre- and post-test for experimental group
* Technical issues: **LLM latency**, **Markdown formatting**, and **text-heavy content**

---

## 📊 Insights & Recommendations

### Strengths

* Personalized explanations and adaptive feedback
* Suitable for self-paced reinforcement
* Engaging when responsive

### Improvements Needed

* Optimize **response time** and **server load handling**
* Add **visual elements** and concise explanations
* Provide **teacher training** for hybrid classroom integration

### Research Implications

* Confirms AI as effective **supplementary learning aid**
* Establishes hybrid integration model between AI and teachers
* Defines UX and infrastructure requirements for educational scalability

---

## 🌟 Validation Outcomes & Future Work

**Confirmed:**

* AI-powered personalization viable for K-12 education
* Compatible with traditional classroom structures
* High engagement potential once technical issues resolved


---

## 🏆 Research Contributions & Impact

### Academic

* First exploratory validation of AI adaptive learning in Brazil
* Empirical evidence linking LLMs to measurable learning outcomes
* Systematic literature review supporting theoretical framework

### Practical

* Implementation roadmap for AI in schools
* Benchmarks for EdTech AI performance and UX

---

## 📝 Conclusion

The experiment validated the adaptive platform’s educational value and highlighted key performance and UX enhancements needed for scalability.

**Key Takeaways:**

* Demonstrated learning improvement and engagement
* Defined performance and pedagogical benchmarks

**Impact:** Sets a foundation for future large-scale adoption of **AI in Brazilian education**, combining pedagogy, technology, and empirical rigor.

---

## 🗂️ Deliverables Summary

| Category                   | Deliverables                                                      |
| -------------------------- | ----------------------------------------------------------------- |
| **Experimental Materials** | `apostila.pdf`, `pre-teste.pdf`, `post-teste.pdf`, `tcle.pdf`     |
| **Infrastructure**         | Frontend (Vercel), Backend (Render), Neo4j, Google Gemini 2.5     |
| **Academic Outputs**       | Systematic Review, Experiment Design PDFs, Manuscript Submissions |
| **Research Context**       | Exploratory classroom validation at Colégio Santa Escolástica      |

---

✅ **Status:** Completed
📅 **Period:** Five sprints (Module 15)
🏫 **Institution:** Colégio Santa Escolástica
💡 **Domains:** AI, Education, Pedagogy, UX Design
🛠️ **Tech Stack:** Neo4j, FastAPI, React/Next.js, Google Gemini 2.5
📁 **Deployment:** Vercel + Render (Production Cloud)
