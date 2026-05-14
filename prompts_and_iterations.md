Case Study: LLM Stylistic Alignment & Editorial QA (Stephen King Emulation)

## 1. Project Objective
This repository documents a practical case study in **AI Quality Assurance**, **Prompt Design**, and **Output Auditing**. The core objective was to deploy an LLM as an automated literary editor tasked with transforming raw, factual autobiographical data into the distinctive prose style of Stephen King. 

My role in this project was that of an **AI Auditor and Quality Lead**—establishing constraints, evaluating the model's editorial performance, and correcting stylistic or factual deviations (hallucinations).

---

## 2. The Execution Framework (AI as Editor, Human as Auditor)

### The System Prompt & Reference Material:
To establish a precise stylistic foundation, the model was instructed to analyze Stephen King's non-fiction autobiographical masterpiece, **"On Writing: A Memoir of the Craft"**. 

The prompt framework was designed as follows:
> *"Are you familiar with Stephen King’s autobiographical book 'On Writing: A Memoir of the Craft'? Based on a deep analysis of his specific style in that book, we will co-create my autobiography. I will provide raw, factual text, and your task is to process and rewrite it using Stephen King's literary voice from that memoir."*

---

## 3. Human-in-the-Loop QA & Auditing Log

As the human Auditor, I conducted rigorous quality checks on the AI's output to identify technical limitations and linguistic bugs:

### Audit Pass 1: Identifying Repetitive Sequences & Pacing Issues
* **AI Editor Behavior (The Bug):** In subsequent paragraphs, the AI model began to unnaturally repeat specific adjectives and stylistic patterns. Furthermore, it over-saturated the text by constantly trying to build intense suspense in every single line, which felt artificial and exhausted the reader.
* **Auditor Intervention:** I implemented strict narrative pacing controls. I rejected repetitive outputs and commanded the model to balance the tension, ensuring the prose retained the natural, conversational yet sharp flow found in King's actual memoir.

### Audit Pass 2: Factual Integrity Check (Data Guardrails)
* **AI Editor Behavior (The Bug):** The model occasionally drifted into fiction writing, hallucinating imaginary events and dramatic subplots to make the story fit a typical thriller template.
* **Auditor Intervention:** I reviewed every line of the generated text to enforce strict factual guardrails. I intervened with precise corrections, reminding the model: *"The autobiography must remain 100% authentic and truthful. Only the writing style should be enhanced, no factual details may be invented."*

---

## 4. Final Output Verification
The final text achieved perfect alignment: it captures the raw, practical, and gripping essence of *'On Writing'*, while remaining completely loyal to my real-life history. Every single line has been manually verified during this QA process to meet professional publishing and linguistic standards.
