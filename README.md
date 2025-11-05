# 📚 El-Bayan: Arabic Grammar Adaptive Learning Platform

El-Bayan is an **AI-powered adaptive learning platform** designed to teach and assess **Arabic grammar** using Natural Language Processing (NLP).  
It combines **diacritized text**, **morphological tagging**, **error detection**, and **personalized feedback** to help learners master Arabic grammar step by step.

---

## ✅ Project Objectives

- ✅ Build a **structured Arabic grammar dataset** including diacritics, morphology, syntax, and common mistakes.  
- ✅ Automatically **detect grammar errors** in student answers.  
- ✅ Provide **personalized feedback and correction** based on grammatical rules.  
- ✅ Enable adaptive learning (difficulty increases based on learner progress).  
- ✅ Support **Modern Standard Arabic (MSA)** – extendable to dialects in future.

---

## 📂 Repository Structure
el-bayan-arabic-grammar-nlp/
│
├── README.md 
│
├── data/
│ ├── raw/ # Original text, textbooks, Quran, news, etc.
│ ├── processed/ # Cleaned and structured datasets
│ └── examples/ # Sample data files for contributors
│
├── data_structure/
│ ├── dataset_schema.md # Explanation of each dataset field
│ ├── grammar_tags.md # List of grammar topics & labels
│ └── feedback_format.md # Structure of feedback messages
│
├── notebooks/
│ ├── data_cleaning.ipynb
│ ├── diacritization.ipynb
│ ├── pos_morphology.ipynb
│ └── grammar_rule_extraction.ipynb
│
├── src/
│ ├── preprocessing/ # Tokenization, normalization, diacritics
│ ├── annotation/ # Grammar rule and POS tagging scripts
│ ├── models/ # Machine learning models (POS, error detection)
│ ├── feedback/ # Feedback and correction logic
│ └── utils/ # Helper functions


