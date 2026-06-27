# 🎤 AI Interview Coach

An AI-powered mock interview application that analyzes your resume, generates personalized interview questions using Google Gemini AI, evaluates your responses, supports voice-based answers, and provides detailed feedback with a downloadable interview report.

---

## 🚀 Features

- 📄 Upload your resume in PDF format
- 🤖 AI-generated interview questions based on your resume
- 🎤 Voice recording for answering interview questions
- 📝 Automatic Speech-to-Text transcription
- 💬 Text-based answer editing
- 📊 AI evaluation with score and feedback
- 📈 Performance dashboard with question-wise scores
- 🟢 Strengths and 🔴 Areas for Improvement analysis
- 📄 Downloadable Interview Report (PDF)
- ⚡ Built with Streamlit for an interactive web interface

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Google Gemini API
- PyPDF
- SpeechRecognition
- Streamlit Mic Recorder
- Pydub
- Pandas
- FPDF

---

## 📂 Project Structure

```
AI-Interview-Coach/
│
├── interviewbot.py
├── requirements.txt
├── README.md
├── .gitignore
├── assets/
│   ├── home.png
│   ├── interview.png
│   └── dashboard.png
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/AI-Interview-Coach.git
```

Move into the project folder

```bash
cd AI-Interview-Coach
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run interviewbot.py
```

---

## 🔑 Gemini API Key

Generate your API key from:

https://ai.google.dev/

Enter the API key in the application sidebar before starting the interview.

---

## 📋 How It Works

1. Upload your resume (PDF).
2. Gemini AI analyzes the resume.
3. AI generates personalized interview questions.
4. Answer using text or voice.
5. Speech is converted into text.
6. Gemini evaluates each response.
7. Receive question-wise feedback and scores.
8. View the overall performance dashboard.
9. Download the final interview report as a PDF.


## 🔮 Future Improvements

- Multiple interview difficulty levels
- HR / Technical interview modes
- Webcam-based interview support
- Timer for each question
- AI confidence analysis
- Better PDF report formatting
- Streamlit Cloud deployment
- User authentication

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

Feel free to fork the repository and create a pull request.

---

## 📧 Contact

**Khushboo Singh**

LinkedIn: *(Add your LinkedIn profile)*

GitHub: *(Add your GitHub profile)*

---

⭐ If you found this project useful, consider giving it a star!
