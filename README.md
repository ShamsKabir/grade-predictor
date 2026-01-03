# 🎓 Grade Predictor & CGPA Tracker

A **minimal, elegant, and accurate Grade Predictor & CGPA Tracker** built using **HTML, CSS, and Vanilla JavaScript**, powered by the **DIU SWE Handbook 2025**.  

This tool helps Software Engineering students **predict grades**, **calculate grade points**, and **track CGPA in a single session** — all without any backend.

---

<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExeTNpNTlod2s4Nm1ia2ZnZjNsc2NrdDRocXB4dTlzZXZqbTR0anNkYSZlcD12MV9naWZzX3NlYXJjaCZjdD1n/3orif1xSQnwOkYIRjO/giphy.gif">
</p>

## [👆🏼 Click here to use the app](https://shamskabir.github.io/grade-predictor/)

---

## ✨ Features

- 📘 **Handbook-based course credits**
  - Automatically fetches course credits from `courses.json`
    
- 🧮 **Real-time grade calculation**
  - Attendance, Quiz, Assignment, Midterm, Presentation & Final
    
- 🎯 **Accurate grade & grade point mapping**
  - Follows DIU grading policy
    
- 📊 **Session-based CGPA tracking**
  - Add multiple courses and instantly see CGPA
    
- 🗑️ **Remove courses dynamically**
  
- ⌨️ **Keyboard-friendly input flow**
  - Press `Enter` to jump to the next field
    
- 🎨 **Clean retro academic UI**
  - Grid background, animations, splash screen
    
- 🚫 **Input validation**
  - Prevents invalid marks and credit errors

---

## 🛠️ Tech Stack

- **HTML5** – Structure  
- **CSS3** – Styling & animations  
- **JavaScript (Vanilla)** – Logic & interactivity  
- **JSON** – Course & credit data  

No frameworks. No dependencies. No backend.

---

## 📂 Project Structure

```
📦 Grade-Predictor
├── index.html
├── style.css
├── courses.json
└── README.md
```

---

## 🚀 How to Run the Project

> ⚠️ **Important:** This project requires **all three files** (`index.html`, `style.css`, and `courses.json`) to be present in the same directory.  
Removing or renaming any of them will break the application.


### Option 1: Using VS Code
1. Install **Live Server**
2. Right-click `index.html`
3. Click **Open with Live Server**

### Option 2: Using Python
```bash
python -m http.server
```

Then open:
```
http://localhost:8000
```

---

## 🧠 Grade Calculation Logic

### Total Marks Breakdown (100)

| Component       | Max Marks |
|-----------------|-----------|
| Attendance      | 7         |
| Quiz            | 15        |
| Assignment      | 5         |
| Midterm         | 25        |
| Presentation    | 8         |
| Final Exam      | 40        |
| **Total**       | **100**   |

---

### Grade Mapping

| Marks Range | Grade | GP   |
|------------|-------|------|
| 80+        | A+    | 4.00 |
| 75–79     | A     | 3.75 |
| 70–74     | A−    | 3.50 |
| 65–69     | B+    | 3.25 |
| 60–64     | B     | 3.00 |
| 55–59     | B−    | 2.75 |
| 50–54     | C+    | 2.50 |
| 45–49     | C     | 2.25 |
| 40–44     | D     | 2.00 |
| < 40      | F     | 0.00 |

---

## 📈 CGPA Formula Used

```
CGPA = Σ (Credit × Grade Point) / Σ Credits
```

---

## 🧪 Data Source

- **DIU SWE Handbook 2025**
- Stored locally in `courses.json`

---

## 👨‍💻 Developer

**Shams Kabir**  
Software Engineering, DIU
