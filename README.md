# 📚 AI-Powered Personalized Study Assistant

This project is an intelligent, NLP-based tool that helps students study smarter by turning academic PDFs into summaries, flashcards, quizzes, and more — all personalized and interactive.

---

## ✨ What It Does

- 📄 Extracts text from academic PDFs
- 🧠 Summarizes long content into short, clear summaries
- 📌 Highlights key points for quick revision
- 🗂️ Creates flashcards automatically
- ❓ Generates multiple-choice quiz questions (MCQs)
- 🧾 Answers your academic questions using AI
- 📊 Tracks your study activity with graphs

---

## 🔧 Tech Stack

- **Python**
- `pdfplumber` – for extracting content from PDFs
- `transformers` – Hugging Face models for summarization and Q&A
  - BART (`facebook/bart-large-cnn`) for summarization
  - T5 (`valhalla/t5-small-qg-prepend`) for question generation
- `matplotlib` – for plotting your daily study progress
- `json` – to store and retrieve your learning logs

---

## 🚀 How to Run

1. First, install the required libraries:
   ```bash
   pip install pdfplumber torch transformers matplotlib

##  Run the script:
python study_assistant.py

## Follow the on-screen instructions:

 Upload a .pdf file of your study notes
Get summaries, flashcards, MCQs, and Q&A
Interact by asking your own questions
See your study progress in a chart


## Features Breakdown

    PDF to Text – Clean extraction using pdfplumber

    Smart Summarizer – Breaks large text into chunks and summarizes them

    Flashcard Maker – Creates questions and answers to boost memory

    MCQ Generator – Builds quiz questions with smart distractors

    Ask Anything – Asks questions and gets answers from the uploaded notes

    Progress Tracker – See how much you studied each day

  ## Created By
     Yettapu Jyothsna 

     G. Bhagya Yashaswini

    Batta Sai Sailu 

    Chunduri V V S Manisha 
 
## References

    BART Summarization: https://arxiv.org/abs/1910.13461

    SQuAD Dataset for Q&A: https://arxiv.org/abs/1606.05250

    Hugging Face Transformers: https://huggingface.co

    pdfplumber Library: https://github.com/jsvine/pdfplumber

    Matplotlib Docs: https://matplotlib.org

    
## ## ✅ License

This project is for educational purposes. You can use or adapt it with credit to the authors.



   
