# TASI-2425-115 Final Project
## *Implementation Of Personas-Based Generative Ai With Retrieval-Augmented Generation (Rag) Approach For Improved Dormitory Service Response*

This repository contains the final implementation of an undergraduate thesis project (TASI-2425-115) focusing on the development of a dormitory service chatbot using Retrieval-Augmented Generation (RAG) and persona-based interactions.

---

## 🚀 Features
- Complete chatbot system for dormitory services, implemented using a Retrieval-Augmented Generation (RAG) approach.
- Knowledge base consisting of documents used as RAG input to generate accurate and context-aware responses.
- Code for evaluating faithfulness  using RAGAS metrics to measure the chatbot's contextual relevance and hallucination rate.

---

## ⚙️ Installation

Follow these steps to install and set up the project on your local machine.

```bash
1️⃣ Clone the repository
git clone https://github.com/elshadaysimamora/personas-based-ai-115

2️⃣ Install PHP dependencies using Composer:
composer install

3️⃣ Install JavaScript dependencies with npm:
npm install

4️⃣ Copy the environment file and configure it:
cp .env.example .env

5️⃣ Generate the application key:
php artisan key:generate

6️⃣ Run database migrations:
php artisan migrate

7️⃣ Build frontend assets:
npm run dev

8️⃣ Start the local server:
php artisan serve


Visit your application at: http://127.0.0.1:8000
