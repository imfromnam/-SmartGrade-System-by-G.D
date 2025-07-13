 📚 SmartGrade System by G.D my week 2 project.

SmartGrade is a simple and powerful student grade manager built with Python. It allows teachers or tutors to:

✅ Add multiple subjects  
✅ Enter students and their marks per subject  
✅ Automatically calculate grades  
✅ See averages and rankings  
✅ Save and load data from a file  
✅ Fully modular — cleanly separated into files (`student.py`, `utils.py`, and `main.py`)  

---

## 🚀 Features

- 💬 Interactive menu system  
- 📘 Handles multiple subjects with student data  
- 🧮 Calculates grades (A+ to F based on marks)  
- 📈 Calculates subject averages and class average  
- 🏆 Sorts students by marks  
- 💾 Saves and loads grade data from `gradebook.txt`  
- 🧠 Clean structure using functions and classes  
- 📦 All logic split into reusable modules

---

## 📁 File Structure

SmartGrade/ ├── main.py         # Main app — handles user input and flow ├── student.py      # Student class with grading logic ├── utils.py        # Helper functions for file saving, loading, sorting, etc. └── gradebook.txt   # Auto-created data file storing saved grades

---

## 🧠 How It Works

1. You enter a subject (e.g. "Math")  
2. Then enter students and their marks for that subject  
3. Program calculates grades and shows average  
4. All students are sorted by marks  
5. Grades can be saved to or loaded from a text file  

---

## 💡 Example Usage

```text
📘 Enter subject name: math

Enter student name: Michael  
Enter marks: 87

Enter student name: Sandy  
Enter marks: 70

📘 Subject: Math  
 - Michael got 87.0 → Grade: A  
 - Sandy got 70.0 → Grade: B  
📈 Average for Math: 78.5


---

📌 Requirements

Python 3.x

No external libraries required

Can be run fully on mobile using Pydroid 3



---

✅ To Run (On Pydroid or Desktop)

1. Save the 3 files:

student.py

utils.py

main.py



2. Run main.py


3. Follow prompts to add students and subjects


4. Save your data or load existing grades anytime




---

✨ Future Ideas (optional upgrades)

🔐 Add login for different teachers

📊 Export to CSV or Excel

🌐 Web-based version (Flask or Django)

📈 Graphs of student performance

🗂 Organize by term or year



---

👨‍💻 Built By

Geraldo Dieterle (imfromnam)
🛠 Built in Pydroid 3 — Fully mobile
🌍 Namibia
