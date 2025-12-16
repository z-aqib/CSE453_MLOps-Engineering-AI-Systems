# CSE453 — MLOps and LLMOps: Engineering AI Systems | IBA Karachi (Fall 2025)

![Course](https://img.shields.io/badge/Course-CSE453%20MLOps%2FLLMOps-0A66C2)
![Institute](https://img.shields.io/badge/Institute-IBA%20Karachi-111111)
![Semester](https://img.shields.io/badge/Semester-Fall%202025-2E7D32)
![Focus](https://img.shields.io/badge/Focus-Production%20AI%20Systems-6A1B9A)

A structured course repository for **MLOps and LLMOps: Engineering AI Systems** at **Institute of Business Administration (IBA), Karachi**.  
This repo organizes lecture material, study notes, midterm prep packs, and revision resources in a clean week-and-topic friendly layout.

Maintained by: **Zuha Aqib** (Student, IBA Karachi)

---

## Course Information

- **Institute:** Institute of Business Administration (IBA), Karachi  
- **School:** School of Mathematics and Computer Science  
- **Semester:** Fall 2025  
- **Course Title:** MLOps and LLMOps: Engineering AI Systems  
- **Instructor:** **Sualeh Ali**  
- **Credits:** 3 (2-1)  

---

## Table of Contents

- [Quick Links](#quick-links)
- [What’s Inside](#whats-inside)
- [Repository Structure](#repository-structure)
- [Course Topic Map](#course-topic-map)
- [Milestones & Assessment](#milestones--assessment)
- [How to Use This Repo](#how-to-use-this-repo)
  - [Midterm Preparation](#midterm-preparation)
  - [After Mid / Final Preparation](#after-mid--final-preparation)
- [Notes & Disclaimer](#notes--disclaimer)

---

## Quick Links

- [Course Outline (PDF)](./MLOpsLLMOpsCourseOutline.pdf)
- [Course Outline (Duplicate Copy)](./Deep_Learning_Course_Outline_(2).pdf)
- [Lectures](./lectures)
- [Class Notes](./class_notes)
- [Guest Speaker Sessions](./guest_speaker_sessions)
- [Mid Exam Pack](./mid_exam)
- [Revision Notes (After Mid)](./revision_notes)
- [Reference Book](./book)

---

## What’s Inside

- **Course outline PDFs**
- **Lectures** (PDF/PPTX + a tutorial notebook)
- **Handwritten class notes** (before and after mid)
- **Guest speaker session notes**
- **Mid exam pack**
  - Topic-wise PDFs (lecture-by-lecture)
  - Mid topics list
  - Mock exams
  - Revision sets
- **Revision notes after mid**
  - LLM intro, pretraining
  - RAG
  - Mixed MCQs
- **Reference book** (Practical MLOps)

---

## Repository Structure

```text
.
├── Deep_Learning_Course_Outline_(2).pdf
├── MLOpsLLMOpsCourseOutline.pdf
├── book/
│   └── Practical_mlops_-_Noah_Gift.pdf
├── class_notes/
│   ├── after_mid.pdf
│   ├── before_mid.pdf
│   └── WhyMLOps_notes.pdf
├── guest_speaker_sessions/
│   └── Meeting_started_-_Notes_by_Gemini_(1).pdf
├── lectures/
│   ├── What_is_MLOps_anyways.pdf
│   ├── ML_Toolbox__1_.pdf
│   ├── AutoML_and_such__1_.pdf
│   ├── ML_Observabilitty_with_Evidently_AI__1_.pdf
│   ├── MLOps_LLMOps_Cloud_Comparison__1_.pptx
│   ├── RAGs_on_RAGs_on_RAGs.pptx
│   ├── A_Crash_Course_of_the_‘LLM’.pptx
│   ├── LLMS__Alignment,_Evaluation.pdf
│   ├── Milestone_1.pdf
│   └── llmops_comprehensive_tutorial.ipynb
├── mid_exam/
│   ├── mid_topics.txt
│   ├── lec01_what-is-mlops.pdf
│   ├── lec02_virtual-env.pdf
│   ├── lec03_containers-and-vm.pdf
│   ├── lec04_docker.pdf
│   ├── lec05_kubernetes.pdf
│   ├── lec06_feature-stores.pdf
│   ├── lec07_automl.pdf
│   ├── lec08_cloud.pdf
│   ├── lec09_mlflow.pdf
│   ├── lec10_drift.pdf
│   ├── lec11_ci-cd-fastapi.pdf
│   ├── lec12_conda.pdf
│   ├── mock-exam-1.pdf
│   ├── mock-exam-2.pdf
│   ├── mock-exam-3.pdf
│   ├── mock-exam-4.pdf
│   ├── revision-1.pdf
│   └── revision-2.pdf
└── revision_notes/
    ├── llm-intro.pdf
    ├── llm-pretraining.pdf
    ├── rag.pdf
    └── mixed-mcqs.pdf
````

---

## Course Topic Map

High-level map of what the course covers (MLOps first, then LLMOps):

1. MLOps lifecycle: from notebooks to production systems
2. Git, environments (venv/conda), and maintainable project structure
3. Docker and serving ML via APIs (FastAPI)
4. CI/CD and automation (e.g., GitHub Actions)
5. Monitoring traditional ML: drift, metrics, dashboards (e.g., Evidently)
6. The shift to LLMOps: evaluation challenges, prompt engineering, RAG
7. Building LLM applications with RAG + vector databases
8. Evaluating LLM/RAG systems (RAG triad, AI-as-judge, evaluation frameworks)
9. CI/CD for LLMs: quality gates + prompt versioning
10. Monitoring LLMs: cost, latency, quality, observability tools
11. Responsible AI & security: bias, toxicity, prompt injection, governance

---

## Milestones & Assessment

The course is milestone/project-driven:

* **Milestone 0:** Project pitch (proposal + short presentation)
* **Milestone 1:** Traditional ML tool deployment with monitoring (containerized + API + observability)
* **Milestone 2:** LLM component deployment (RAG + vector DB + evaluation)
* **Final:** End-to-end system presentation + report (architecture, deployment, monitoring, evaluation, ethics)

Assessment (as per outline):

* Class participation
* Quizzes
* Midterm
* Final milestone-based project (Milestone 0/1/2 + final deliverable)

---

## How to Use This Repo

### Midterm Preparation

Use the midterm pack in this order:

1. **Mid topics list:** `mid_exam/mid_topics.txt`
2. **Topic-wise notes:** `mid_exam/lec01_...` to `mid_exam/lec12_...`
3. **Revision sets:** `mid_exam/revision-1.pdf`, `mid_exam/revision-2.pdf`
4. **Mock exams:** `mid_exam/mock-exam-1.pdf` to `mid_exam/mock-exam-4.pdf`
5. Cross-check weak areas using:

   * `lectures/` (core lecture files)
   * `class_notes/before_mid.pdf`

### After Mid / Final Preparation

please note: there was no final exam for this course.

1. Start from `class_notes/after_mid.pdf` to align with in-class direction.
2. Use the after-mid notes in `revision_notes/`:

   * `llm-intro.pdf`
   * `llm-pretraining.pdf`
   * `rag.pdf`
   * `mixed-mcqs.pdf`
3. Pair with the relevant lecture files in `lectures/` (LLM/RAG/observability content).
4. Use the book in `book/` for deeper understanding and real-world framing.

---

## Notes & Disclaimer

* This repository is intended for learning and revision.
* Lecture material and outlines belong to their respective authors/instructors.
* Any self-made mock exams/notes are included for practice and study support.