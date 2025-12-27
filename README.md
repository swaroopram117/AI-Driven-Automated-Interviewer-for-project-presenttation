# 🚀 AI-Driven Automated Interviewer (Challenge 1)

## 📌 Overview
This project is an AI-powered system designed to automate the technical interview and project defense process. It "watches" a student's presentation (via screen share or screenshot), analyzes the code architecture using Computer Vision, and conducts a live, adaptive verbal interview.

At the end of the session, it acts as an automated judge, generating a **Final Scorecard** based on Technical Depth, Clarity, and Implementation quality.

## 🎯 Objective
To build an automated, unbiased, and technically capable AI interviewer that can:
1.  **See:** Understand code snippets, diagrams, and UI layouts.
2.  **Speak:** Ask context-aware questions using Text-to-Speech.
3.  **Evaluate:** Grade the candidate's answers in real-time.

## 🛠️ Tech Stack
* **AI Model:** Google Gemini 3 Pro (Multimodal Vision + Text)
* **Frontend:** Streamlit (Python)
* **Audio:** gTTS (Google Text-to-Speech)
* **Deployment:** Cloudflare Tunnel (for instant public access)
* **Language:** Python 3.10+

## ⚙️ How It Works
1.  **Upload:** The user uploads a screenshot of their code or project slide.
2.  **Analysis:** The AI analyzes the visual content to identify the tech stack and potential flaws.
3.  **Interview Loop:**
    * **Q1:** The AI asks a specific technical question about the uploaded code.
    * **Response:** The student answers via text or voice.
    * **Follow-up:** The AI evaluates the answer and asks a deeper follow-up question.
4.  **Scoring:** After 3 rounds of questions, the system generates a **Final Report Card** with a Pass/Fail verdict.

## 📦 Installation & Usage
This project is designed to run in a cloud environment (Google Colab) for ease of demonstration.

1.  Open the `Challenge_1.ipynb` notebook.
2.  Run the installation cell to install dependencies (`streamlit`, `requests`, `gTTS`).
3.  Run the main app cell.
4.  Click the public **Cloudflare Link** (e.g., `https://xxxx.trycloudflare.com`) generated in the output.
5.  Upload your project image and click **"Begin Defense"**.

## 📊 Evaluation Metrics
The AI scores candidates on a scale of 1-10 for:
* **Technical Depth:** Understanding of the underlying logic and architecture.
* **Clarity:** Ability to explain complex concepts simply.
* **Originality/Implementation:** Quality of the solution presented.

## 📝 License
This project is submitted for the Hackathon Challenge 1.
