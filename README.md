# Ultimate Quiz

#### Video Demo: https://www.youtube.com/watch?v=WLQCR-6msEQ

#### Description:

"Ultimate Quiz" is my final project for CS50x — a terminal-based Python quiz game that tests your knowledge across all topics covered in the course, from C to SQL.

---

### ✨ Features:

- 🤓 50+ handpicked questions from CS50 topics
- 🏆 Persistent leaderboard using a local text file (or JSON)
- 🌈 Colorful terminal interface using `termcolor`
- 💡 Dynamic feedback based on user performance
- 🔄 Play-again loop and input validation

---

### 📁 Project Files:

- `quiz.py` – main game logic, handles question flow, scoring, and feedback
- `questions.py` – contains the pool of questions categorized by topic
- `leaderboard.py` – manages loading and saving high scores
- `utils.py` – handles coloring, formatting, and user input functions
- `requirements.txt` – specifies required Python packages (`termcolor`)
- `README.md` – this file!

---

### 🧠 Design Decisions:

I chose a terminal interface to focus on logic and structure without needing front-end design. I implemented:

- Object-oriented approach for questions and scoring
- Separation of concerns with multiple modules
- Simple file-based leaderboard (JSON) instead of database, for portability

I considered using a GUI library like `tkinter` but stuck with CLI for better cross-platform compatibility and simplicity.

---

### 🛠️ How to Run:

#### Prerequisites:
- Python 3.8+
- `termcolor` module

#### Steps:
```bash
pip install termcolor
python quiz.py
