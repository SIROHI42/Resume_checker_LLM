# 🧠 AI Resume Quality Checker using Hugging Face + LangChain + Falcon 3B

An open-source **AI-powered Resume Quality Checker** that uses **Hugging Face NLP models** and **LangChain** to automatically evaluate resumes against a **Data Analyst job profile**.

It extracts skills, compares them to an ideal benchmark list, and generates feedback using **Falcon 3B Instruct LLM** — all locally and without OpenAI API keys.

---

## 🚀 Features

✅ Extracts resume text (PDF/Text)  
✅ Detects skills using `yashpwr/resume-ner-bert-v2` (Hugging Face NER model)  
✅ Compares extracted skills with a Data Analyst skill list  
✅ Calculates Skill Match % and lists missing skills  
✅ Generates AI-written feedback using **Falcon 3B Instruct**  
✅ 100% Offline and Open-Source (no API key required)  

---

## 🧩 Architecture Overview

