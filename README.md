# 🌟 Professor’s Assistant – AI-Driven Academic Focus Tool  
*A distraction-free, context-aware learning assistant built for students.*  
Final Showcase Project – IDENTITY 2025, Dezyne École College (in collaboration with *Sentry*)  
Built by *Team Mohit & Lakshay*

---

## 🚀 Overview

*Professor’s Assistant* is an AI-powered academic companion built to solve one of the most common student problems:

> Students open AI tools to study… and 20 minutes later they're discussing cricket scores, movies, or random gossip.

This project introduces a *strictly academic AI agent* that never engages in small talk, never goes off-topic, and always redirects students back to their *uploaded study material*.  

It runs *fully in the browser, processes files locally, and uses a **Local RAG system* — making it private, focused, and ideal for disciplined learning.

---

## 🎯 Why We Built It

During our research, we found three major problems with how students use AI tools:

### ❗ 1. Conversation Drift  
AI tools easily get into unrelated topics—sports, memes, movies, etc.

### ❗ 2. Momentum Break  
Even small talk can disrupt study flow and derail focus.

### ❗ 3. No Context  
Typical AI tools cannot read syllabus PDFs, notes, or class material, leading to generic or wrong answers.

These challenges inspired us to build an AI that eliminates distraction, maintains focus, and stays anchored to a student’s coursework.

---

## 🧠 System Architecture

Professor’s Assistant is designed as a *lightweight, privacy-first, entirely client-side web app*.

### ⿡ File Upload & Parsing  
- Upload *PDF, TXT, CSV* files  
- Secure local extraction using *PDF.js*  
- No file is uploaded to a server  

### ⿢ Local RAG System  
- Extracted text is chunked and turned into a mini in-browser knowledge base  
- Ensures answers always come from *your syllabus*  

### ⿣ AI Engine – Google Gemini 1.5 Flash  
- Strict system prompts  
- Rejects off-topic questions  
- Only produces academic responses  
- Can generate diagrams, summaries, concept maps, and quizzes  

### ⿤ Built-In Learning Tools  
- Mermaid.js concept maps  
- Flashcards & quizzes  
- Reading panel for extracted text  
- Pomodoro timer for focus  

### ⿥ Frontend Experience  
- Responsive UI  
- Minimal, distraction-free layout  
- Dark mode support  

---

## ✨ Key Features

- 🛡 *Zero Small Talk* — AI stays strictly academic  
- 🎯 *Context-Aware Answers* — Uses uploaded files as ground truth  
- 🗂 *Distraction-Free Environment*  
- 📚 *Mermaid.js Concept Maps*  
- 🧠 *Auto-generated Flashcards & Quizzes*  
- ⏱ *Built-in Pomodoro Timer*  
- 🔒 *Completely Local Processing* — privacy-friendly  

---

## ⚙ Tech Stack

| Layer | Tools |
|------|-------|
| *Frontend* | HTML5, Tailwind CSS, Vanilla JavaScript |
| *AI Engine* | Google Gemini 1.5 Flash |
| *Local Processing* | PDF.js, Marked.js |
| *Visualizations* | Mermaid.js |
| *Logic* | Local RAG engine, client-side parsers |

---

## 🏗 Recommended Folder Structure
