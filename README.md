

# 🎓 EduSchemes India – Find Scholarships & Prepare for Exams

EduSchemes India is a web-based platform designed to help students in India discover relevant government educational schemes, scholarships, and prepare for competitive exams through AI-generated mock tests.

---

## 🚀 Features

### 🔎 Personalized Scheme Finder

* Users enter details such as:

  * Education level
  * Category (General, SC, ST, OBC, EWS, Minority)
  * Gender
  * Disability status
  * State of residence
  * Annual family income
* AI generates relevant government schemes and scholarships
* Includes eligibility details and official application links
* Displays verified sources

---

### 🎓 Major Scholarship Portals Included

* **National Scholarship Portal (NSP)**
  One-stop platform for multiple central & state scholarships.

* **University Grants Commission (UGC)**
  Scholarships for university and college students.

* **All India Council for Technical Education (AICTE)**
  Student development schemes for technical education.

---

### 📝 AI-Powered Mock Test Generator

* Subjects available:

  * General Knowledge
  * Quantitative Aptitude
  * Logical Reasoning
  * Indian History
  * Basic Computer Science
* Generates 5-question MCQ quizzes
* Instant scoring
* Retake option available

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, Tailwind CSS
* **JavaScript:** Vanilla JS
* **Icons:** Lucide Icons
* **Font:** Google Fonts (Inter)
* **AI Integration:** Google Gemini API (`gemini-2.5-flash-preview`)
* **Search Grounding:** Google Search tool via Gemini

---

## ⚙️ How It Works

### Scheme Finder

1. User fills in profile details.
2. A structured prompt is sent to the Gemini API.
3. Gemini:

   * Searches relevant government schemes
   * Returns structured JSON response
4. Results are displayed dynamically in card format.

### Mock Test

1. User selects a subject.
2. Gemini generates a JSON-based quiz.
3. Questions are rendered dynamically.
4. Score calculated on submission.

---

## 🔐 API Setup

To run the project locally:

1. Get your Google Gemini API key.
2. Replace the API key in the script section:

```javascript
const API_KEY = "YOUR_API_KEY_HERE";
```

3. Open `index.html` in your browser.

⚠️ **Important:**
Do NOT expose your API key in production. Use a backend server to securely handle API requests.

---

## 📂 Project Structure

```
Edu-Scheme-Finder/
│
├── index.html
└── README.md
```

---

## 🎯 Target Users

* School students (10th & 12th)
* Undergraduate & Postgraduate students
* Competitive exam aspirants
* Students from reserved categories
* Students seeking financial assistance

---

## 🌟 Future Improvements

* Backend integration for secure API handling
* User authentication system
* Save & track applied schemes
* Scheme filtering by state database
* Full-length mock tests
* Progress analytics dashboard

---

## 📜 License

This project is for educational and conceptual demonstration purposes.

---

## 💡 About the Project

EduSchemes India is a conceptual educational empowerment platform built to bridge the information gap between students and government support schemes.

It combines AI with structured student profiling to provide:

* Relevant financial assistance options
* Centralized scholarship access
* Exam preparation support

