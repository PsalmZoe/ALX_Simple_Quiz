# ALX_Simple_Quiz

A simple, interactive quiz application built using **HTML**, **CSS**, and **JavaScript**.  
This project was created as part of the ALX learning program to demonstrate basic DOM manipulation, event handling, and conditional logic in JavaScript.

---

## 🚀 Features

- **Single multiple-choice question** with three answer options.
- **Radio button selection** ensures only one answer can be chosen at a time.
- **Instant feedback** after submitting:
  - ✅ "Correct! Well done." for the right answer.
  - ❌ "That's incorrect. Try again!" for the wrong answer.
  - ⚠ "Please select an answer before submitting." if no option is chosen.
- **Clean and responsive design** using CSS.

---

## 📂 Project Structure

ALX_Simple_Quiz/
│
├── index.html # HTML structure for the quiz
├── styles.css # Styling for the quiz interface
└── quiz.js # JavaScript functionality for checking answers

yaml
Copy
Edit

---

## 🛠 Technologies Used

- **HTML5** – for structuring the quiz content.
- **CSS3** – for styling and layout.
- **JavaScript (ES6)** – for quiz logic and interactivity.

---

## 📋 How It Works

1. The user selects an answer from the provided radio buttons.
2. When the **Submit Answer** button is clicked:
   - The `checkAnswer` function runs.
   - The function compares the user's choice with the `correctAnswer` variable.
   - Feedback is displayed in the `#feedback` paragraph element.
3. If no answer is selected, the user is prompted to choose one before submitting.

---

## ▶️ How to Run Locally

1. **Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/ALX_Simple_Quiz.git