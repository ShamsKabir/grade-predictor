# 🎓 Grade Predictor & CGPA Tracker

Transform your pre-exam anxiety into data-driven confidence! This is a sleek, academic-aesthetic web tool designed for students who want to calculate their grades with style. No more messy spreadsheets—just a clean, grid-paper interface that does the math for you.

---

<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExeTNpNTlod2s4Nm1ia2ZnZjNsc2NrdDRocXB4dTlzZXZqbTR0anNkYSZlcD12MV9naWZzX3NlYXJjaCZjdD1n/3orif1xSQnwOkYIRjO/giphy.gif">
</p>

## [👆🏼 Click Here](https://shamskabir.github.io/grade-predictor/)

---

## ✨ Features

* **Real-time Calculations**: Watch your grade point and letter grade update instantly as you type.
* **Intelligent Validation**: Built-in logic stops calculations and flags "ERR" if you enter marks above allowed limits (e.g., more than 40 in a Final Exam).
* **Session Summary**: Save multiple courses to a summary card to calculate your semester CGPA on the fly.
* **Premium UX**: Featuring a satisfying "Stamp" animation when your grade changes and a smooth "Slide-up" entrance for all cards.
* **Academic Aesthetic**: A beautiful "Drafting Paper" background with professional serif typography.
* **Responsive Layout**: Seamlessly switches from a vertical mobile view to a side-by-side desktop dashboard for larger screens.

---

## 🛠️ Built With

* **HTML5**: Semantic structure for the best accessibility.
* **CSS3**: Custom Flexbox layouts, complex gradients for the grid pattern, and `cubic-bezier` animations.
* **Vanilla JavaScript**: Lightweight logic for grading brackets and CGPA mathematics—no heavy frameworks required.



---

## 📝 How It Works

The app uses a specific grading bracket to determine your success:

| Total Score | Grade | GP |
| :--- | :--- | :--- |
| 80+ | A+ | 4.00 |
| 75-79 | A | 3.75 |
| 70-74 | A- | 3.50 |
| 65-69 | B+ | 3.25 |
| 60-64 | B | 3.00 |
| 55-59 | B- | 2.75 |
| 50-54 | C+ | 2.50 |
| 45-49 | C | 2.25 |
| 40-44 | D | 2.00 |
| < 40 | F | 0.00 |

*Note: Calculations include a `0.001` buffer to ensure fair rounding at the bracket edges.*

---

