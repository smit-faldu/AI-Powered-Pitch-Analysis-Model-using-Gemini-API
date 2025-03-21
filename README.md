# 🚀 AI-Powered Pitch Analysis Model using Gemini API

[![Try on Hugging Face](https://img.shields.io/badge/-HuggingFace-FDEE21?style=for-the-badge&logo=HuggingFace&logoColor=black)](https://huggingface.co/spaces/smit-faldu/AI-Powered-Pitch-Analysis-Model) 
[![Open in Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)](https://colab.research.google.com/drive/1qpGDnzMy1cWvv5NcO1A1_qBwTQPBtMpW?usp=sharing)


This project is an **AI-powered web application** that analyzes startup **pitch decks (PDFs)** using **Google Gemini API**. It extracts text from PDFs, evaluates the pitch, assigns a **Pitch Score (0-100)**, identifies **Strengths & Weaknesses**, and suggests **Improvements**.

🔹 **Frontend:** HTML, Tailwind CSS, JavaScript  
🔹 **Backend:** Flask, LangChain, Gemini API  
🔹 **Vector Search:** FAISS (for potential extensions)  
🔹 **Deployment:** Google Colab with Ngrok  

---

## 📌 **Features**
✔ **Upload Startup Pitch Deck (PDF)**  
✔ **Extracts Key Sections (Problem, Solution, Market, Financials, etc.)**  
✔ **AI assigns an Overall Pitch Score (0-100)**  
✔ **Identifies Strengths & Weaknesses**  
✔ **Suggests Improvements for a Better Pitch**  
✔ **Modern UI with Tailwind CSS**  
✔ **Handles Both Short & Long Text Gracefully**  

---

## 📌 **How It Works**
1. **User Uploads a PDF** containing the startup pitch deck.
2. **Text Extraction** is done using `PyMuPDF` to extract readable content.
3. **LangChain with Google Gemini API** processes the extracted text:
   - Assigns a **Pitch Score (0-100)**
   - Identifies **Strengths & Weaknesses**
   - Suggests **Improvements**
4. **Results are displayed** on the frontend with scrollable sections.
5. **Ngrok is used** for exposing the Flask API when running on Google Colab.

---

## 📌 **Tech Stack & Libraries Used**
### **Frontend**
- `HTML`, `CSS`, `Tailwind CSS` → UI design
- `JavaScript` → Handles file upload & displays results

### **Backend**
- `Flask` → Web framework for API
- `Flask-CORS` → Enable cross-origin requests
- `PyMuPDF (fitz)` → Extract text from PDFs
- `Google Generative AI` → Uses **Gemini API** for analysis
- `LangChain` → Handles structured AI prompting
- `FAISS (Future Extension)` → Vector search for investor matching

### **Deployment**
- `Ngrok` → Expose API on Google Colab

---

## 📌 **Installation & Setup**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/smit-faldu/ai-pitch-analysis.git
cd ai-pitch-analysis
