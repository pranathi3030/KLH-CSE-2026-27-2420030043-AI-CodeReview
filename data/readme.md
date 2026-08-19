# AI Copilot Code Review using Large Language Models

## Team Members

| Name                | Roll Number |
| ------------------- | ----------- |
| Bandi Srihitha      | 2420030099  |
| Emani Mahathi       | 2420030093  |
| Prathipati Pranathi | 2420030043  |

## Supervisor

Dr. K. Swanthana

## Abstract

Traditional software code review is time-consuming and requires significant manual effort. Static analysis tools such as Pylint, PMD, and ESLint can detect rule-based coding issues but have limited contextual understanding, while Large Language Models (LLMs) may generate generic or unsupported suggestions without relevant repository context. This project develops an AI-powered code review pipeline that integrates CodeLlama, CodeBERT, FAISS, Static Analysis, and Retrieval-Augmented Generation (RAG). The system supports Python, Java, and JavaScript by combining language-specific static analysis with semantic retrieval of similar code from CodeSearchNet and selected GitHub repositories. Retrieved context, static-analysis findings, and source code are provided to CodeLlama to generate context-aware, explainable, and severity-ranked code review suggestions.

## Setup and Execution Instructions

1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Prepare the datasets or documented data-source references under `/data`.
4. Configure the CodeLlama inference environment.
5. Run the Streamlit application: `streamlit run app.py`
6. Upload or paste source code and view the generated code review.

## Project Structure

* `/src` — source code for language detection, static analysis, code chunking, CodeBERT embeddings, FAISS retrieval, prompt construction, CodeLlama integration, and evaluation
* `/docs` — architecture diagrams, literature survey, methodology, and project documentation
* `/data` — CodeSearchNet, CodeXGLUE, and selected GitHub repository data or documented data-source references
* `/results` — static-analysis outputs, retrieval results, generated code reviews, and evaluation results
* `/reports` — Review 1, Review 2, and final project reports
* `/README.md` — project overview, setup instructions, execution instructions, and current phase status

## Current Phase Status

Review 1 — in progress
