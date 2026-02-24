# 🚀 NeuralMatch AI  
### Transformer-Based Resume–Job Description Alignment System  

NeuralMatch AI is a deep learning-powered ATS scoring system that leverages Transformer-based neural networks to evaluate semantic similarity between resumes and job descriptions.  
It combines contextual embeddings with statistical NLP techniques to generate a recruiter-grade compatibility score.

---

## 📌 Problem Statement  

Traditional ATS systems rely heavily on keyword matching, often failing to capture semantic meaning and contextual relevance.  
This leads to qualified candidates being overlooked due to lexical mismatches.

---

# ⭐ STAR Framework

## 🟡 S — Situation  

Recruiters receive hundreds of resumes per job posting.  
Most ATS systems use basic keyword filtering, which lacks contextual intelligence and semantic understanding.

---

## 🔵 T — Task  

Develop an intelligent resume screening system that:

- Understands semantic meaning using deep neural networks  
- Evaluates contextual similarity between resume and job description  
- Incorporates recruiter-centric signals (impact metrics, business verbs)  
- Produces a weighted ATS compatibility score  

---

## 🟢 A — Action  

To solve this, the following approach was implemented:

### 1️⃣ Semantic Matching (Neural Network Core)
- Used `SentenceTransformer (all-MiniLM-L6-v2)`
- Generated contextual sentence embeddings
- Computed cosine similarity between resume and JD embeddings
- Captured deep semantic alignment beyond keyword overlap

### 2️⃣ TF-IDF Keyword Extraction
- Applied `TfidfVectorizer`
- Extracted top dynamic keywords
- Calculated keyword overlap score

### 3️⃣ Business Impact Analysis
- Detected action verbs (e.g., led, optimized, delivered)
- Extracted measurable results (% growth, X improvement)

### 4️⃣ Weighted Scoring Model
Final Score =  
- 45% Semantic Similarity  
- 30% Keyword Match  
- 15% Business Verb Strength  
- 10% Quantified Impact  

---

## 🟣 R — Result  

- Built a hybrid AI system combining deep learning + statistical NLP  
- Achieved recruiter-style resume evaluation logic  
- Produced interpretable and actionable ATS alignment score  
- Demonstrated real-world application of Transformer-based neural networks  

---

# 🧠 Technical Stack  

- Python  
- Sentence Transformers (Transformer-based Neural Networks)  
- Scikit-learn (TF-IDF, Cosine Similarity)  
- NLTK  
- pdfplumber  
- Google Colab  
