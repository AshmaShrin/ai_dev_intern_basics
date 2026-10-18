# 🚀 AI Dev Basics: A 4-Week Hands-On Roadmap

**Python → OOP → Git → NumPy → Machine Learning from scratch.**

Want to learn AI but don't know where to start? Start here. This repository is a beginner-friendly, **learn-by-doing** path. In four weeks you go from your first `print("Hello")` to training your own machine learning models on a real Kaggle dataset, using only Python and NumPy.

No previous coding experience needed. You only need a computer, curiosity, and about **1–2 hours a day**.

---

## 🗺️ The 4-Week Roadmap

| Week | Topic | Notebook | You will be able to... |
|---|---|---|---|
| **1** | Python basics | [`week1_python_basics.ipynb`](notebooks/week1_python_basics.ipynb) | write programs with variables, loops, functions, dicts, files and error handling |
| **2** | Python OOP | [`week2_python_oop.ipynb`](notebooks/week2_python_oop.ipynb) | design your own classes, use inheritance, and read other people's class-based code |
| **3** (first half) | Git fundamentals | [`week3_git_and_numpy.ipynb`](notebooks/week3_git_and_numpy.ipynb) (Part A) | save versions of your work, use branches, push to GitHub |
| **3** (second half) | NumPy data handling | [`week3_git_and_numpy.ipynb`](notebooks/week3_git_and_numpy.ipynb) (Part B) | create, slice, filter, clean and analyse arrays without loops |
| **4** | Supervised ML with NumPy | [`week4_numpy_supervised_ml.ipynb`](notebooks/week4_numpy_supervised_ml.ipynb) | build linear regression, logistic regression and k-NN from scratch on a Kaggle dataset |

Each notebook is split into **5 study days** so you always know what to do today.

---

## 📁 What is in this repository?

```
ai_dev_intern_basics/
├── README.md              <- you are here
├── requirements.txt       <- the Python packages you need
├── notebooks/
│   ├── week1_python_basics.ipynb
│   ├── week2_python_oop.ipynb
│   ├── week3_git_and_numpy.ipynb
│   └── week4_numpy_supervised_ml.ipynb
└── data/
    └── README.md          <- how to download the Kaggle dataset for week 4
```

---

## 🛠️ Setup: step by step

### Step 1: Clone or fork this repository
This gives you your own copy of all the notebooks on your computer. You need Git for this: install it from [git-scm.com/downloads](https://git-scm.com/downloads) and check it with `git --version`.

**Option A (recommended): fork, then clone.** Click **Fork** at the top right of the GitHub page to create your own copy under your account, then clone *your* copy. This lets you save and push your own progress.
```bash
git clone https://github.com/<your-username>/ai_dev_intern_basics.git
cd ai_dev_intern_basics
```

**Option B: clone directly.** Quicker, but you won't be able to push your changes to the original.
```bash
git clone https://github.com/<original-owner>/ai_dev_intern_basics.git
cd ai_dev_intern_basics
```

> No Git yet? Use the green **Code → Download ZIP** button on GitHub and unzip it. You can set up Git later in Week 3.

All the next commands are run **inside this `ai_dev_intern_basics` folder**.

### Step 2: Install Python
Download Python 3.10 or newer from [python.org/downloads](https://www.python.org/downloads/). On Windows, tick **"Add Python to PATH"** during installation.

Check it worked by opening a terminal (Windows: *PowerShell*, Mac/Linux: *Terminal*):
```bash
python --version
```
(On some Mac/Linux machines the command is `python3`.)

### Step 3: Create a virtual environment (recommended)
A virtual environment is a private box of packages for this project, so it can't mess up other projects.

**Windows (PowerShell):**
```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```
**Mac / Linux:**
```bash
python3 -m venv .venv
source .venv/bin/activate
```
You should now see `(.venv)` at the start of your terminal line.

### Step 4: Install the packages
```bash
pip install -r requirements.txt
```

### Step 5: Start Jupyter
```bash
jupyter notebook
```
Your browser opens. Click the `notebooks` folder and open **`week1_python_basics.ipynb`**. 🎉

**Other ways to run notebooks**
- **VS Code:** install the *Python* and *Jupyter* extensions, open the folder, open a `.ipynb` file and pick the `.venv` kernel.
- **Google Colab (no install):** upload a notebook to [colab.research.google.com](https://colab.research.google.com). Note: the Git section in Week 3 and the data file in Week 4 are easier on your own computer.

---

## 📓 How to use a notebook

A notebook is a document made of **cells**. Text cells explain; code cells run Python.

| Action | How |
|---|---|
| Run a cell and go to the next | `Shift + Enter` |
| Run a cell and stay | `Ctrl + Enter` |
| Add a cell below | press `B` (when the cell is selected, not editing) |
| Restart everything | menu **Kernel → Restart** (then run the cells again from the top) |

### The study loop for every topic

1. **Read** the short explanation.
2. **Run** the example code and watch the output.
3. **Change it.** Edit numbers, names and conditions. Break it on purpose. Run again.
4. **Do the 🏋️ exercise.** Replace `None` or `# YOUR CODE HERE` with your code and run the cell.
5. **Read the result.** The self-check prints `✅ Correct!` or `❌ Not yet` with a hint.
6. **Stuck?** Follow the *stuck routine* below. Open the 💡 solution only as the last step.
7. **Read the official docs link** at the end of the section, even if you got it right.

> 💡 **Type the code yourself.** Don't copy-paste. Your fingers need to learn too.

### 🆘 The stuck routine (try these in order)
1. Read the error message from the **bottom up**. The last line says what went wrong; the line above says where.
2. Add `print(...)` to look at your variables. Use `type(x)`, `len(x)` or `x.shape`.
3. Re-read the explanation and the example above the exercise.
4. Search the **official docs** (links below) or paste the error message into a search engine.
5. Ask a mentor or classmate. Show them what you tried.
6. Open the 💡 solution. Understand it, close it, then **write it again from memory**.

### ⏱️ Suggested daily rhythm (1–2 hours)
| Time | What |
|---|---|
| 10 min | Re-run yesterday's last exercise from memory |
| 40–60 min | Read and run today's section, do the exercises |
| 15 min | Read one page of the official docs on today's topic |
| 5 min | Commit your work with Git (`git add .`, `git commit -m "Day 3 done"`) |

---

## ✅ Weekly goals

**Week 1: Python basics**
- [ ] Variables, types, strings, f-strings
- [ ] `if / elif / else`, `for` and `while` loops
- [ ] Lists, tuples, dicts, sets, comprehensions
- [ ] Functions, `try / except`, reading and writing files
- [ ] Finish the **Grade Tracker** mini project

**Week 2: Python OOP**
- [ ] Classes, objects, `__init__`, `self`, methods
- [ ] `__str__`, `__repr__`, `@property`
- [ ] Inheritance, `super()`, polymorphism, composition
- [ ] Dunder methods, `@classmethod`, `@staticmethod`, dataclasses
- [ ] Finish the **Library System** mini project

**Week 3: Git (days 1–2.5) and NumPy (days 2.5–5)**
- [ ] `init`, `add`, `commit`, `status`, `log`, `diff`, `.gitignore`
- [ ] Branches, merging, merge conflicts, GitHub push/pull, pull request
- [ ] NumPy arrays, indexing, slicing, masks, broadcasting, `axis`
- [ ] Missing values (`nan`) and loading CSV files
- [ ] Finish the **Marks analyser** mini project

**Week 4: Supervised ML with NumPy**
- [ ] Features vs labels, regression vs classification
- [ ] Clean real data, train/test split, scaling
- [ ] Linear regression, logistic regression, k-NN from scratch
- [ ] Accuracy, precision, recall, F1, overfitting
- [ ] Wrap your model in a class and finish the **Final project** and challenges

---

## 📖 Official docs: your best teachers

Reading official documentation is one of the most valuable skills a developer can build. At first it feels dense; keep going and it becomes your superpower. Every notebook links the exact pages to read.

| Topic | Official resource |
|---|---|
| Python | [Python Tutorial](https://docs.python.org/3/tutorial/index.html) · [Standard Library](https://docs.python.org/3/library/index.html) |
| OOP | [Classes tutorial](https://docs.python.org/3/tutorial/classes.html) · [dataclasses](https://docs.python.org/3/library/dataclasses.html) |
| Git | [Pro Git book (free)](https://git-scm.com/book/en/v2) · [Git reference](https://git-scm.com/docs) |
| GitHub | [GitHub Docs](https://docs.github.com/en/get-started) |
| NumPy | [Absolute beginners guide](https://numpy.org/doc/stable/user/absolute_beginners.html) · [Quickstart](https://numpy.org/doc/stable/user/quickstart.html) · [API reference](https://numpy.org/doc/stable/reference/index.html) |
| Jupyter | [Jupyter Notebook docs](https://jupyter-notebook.readthedocs.io/en/stable/) |
| Machine learning | [Kaggle Learn](https://www.kaggle.com/learn) · [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html) |

---

## 📊 Week 4 dataset

Week 4 uses the **Pima Indians Diabetes Database** from Kaggle. Download steps are in [`data/README.md`](data/README.md) and again at the top of the Week 4 notebook. The notebook tells you clearly if the file is missing.

---

## ❓ FAQ

**I get `ModuleNotFoundError: No module named 'numpy'`.**
Your virtual environment is probably not active. Activate it (Step 3) and run `pip install -r requirements.txt` again. In Jupyter, make sure the notebook uses the same Python (Kernel → Change kernel).

**PowerShell says running scripts is disabled.**
Run `Set-ExecutionPolicy -Scope CurrentUser RemoteSigned` once, then activate the environment again.

**A ❌ shows even though I think my code is right.**
Read the hint after "Not yet." It tells you what was expected. Print your variable and compare.

**My notebook is messy or broken.**
Use **Kernel → Restart & Run All**. If it is really broken, re-download the notebook from GitHub (`git restore notebooks/<file>.ipynb` brings back the original, but removes your edits!).

**Can I skip a week?**
Weeks build on each other. If you already know Python basics, skim Week 1 and do only the exercises as a test.

**Can I do it faster or slower?**
Yes! The 4 weeks is a guide. It is better to understand fully than to finish quickly.

---

## 🧭 After the 4 weeks

1. Rebuild the same models with **scikit-learn** and compare results.
2. Learn **pandas** for table data and **matplotlib** for charts.
3. Try the [Titanic competition](https://www.kaggle.com/competitions/titanic) on Kaggle.
4. Start a small project of your own and put it on GitHub.

Happy learning! 🌱
