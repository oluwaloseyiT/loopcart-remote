# 🛒 LoopCart
 
LoopCart is a small Python application that prints a personalized welcome message. The app itself is intentionally simple — the real focus of this repo is the **Git/GitHub collaboration workflow** built around it: branching, committing, opening a Pull Request, responding to review feedback, merging, and triggering CI/CD.
 
```python
def greet(name):
    return f"Welcome to LoopCart v1.0, {name}!"
```
 
## 📖 Project Purpose
 
This lab walks through a realistic, end-to-end contribution workflow:
 
1. Clone the repository
2. Create a feature branch
3. Write and test code
4. Commit with meaningful messages
5. Push the branch and open a Pull Request
6. Apply code review feedback
7. Merge to `main`
8. Trigger a CI/CD pipeline
## ✅ Prerequisites
 
- Git installed and configured
- Python 3 installed
- Terminal access (Windows users: use Git Bash)
## 🚀 Getting Started
 
Clone the repository:
 
```bash
git clone https://github.com/oluwaloseyiT/loopcart-remote.git
```
 
Enter the project folder:
 
```bash
cd loopcart-remote
```
 
Run the app:
 
```bash
python3 app.py
```
 
**Expected output:**
 
```
Welcome to LoopCart v1.0, Engineer!
```
 
## 🌱 Contributing
 
1. **Create a feature branch**
```bash
   git checkout -b feat/your-feature
```
 
2. **Make your changes, then commit with a clear, conventional message**
```bash
   git add .
   git commit -m "feat: describe your change"
```
 
3. **Push the branch to GitHub**
```bash
   git push -u origin feat/your-feature
```
 
4. **Open a Pull Request** against `main` and request a review.
5. **Apply review feedback**, push any follow-up commits, then merge once approved.
## 📁 Repository Structure
 
| File | Purpose |
|---|---|
| `app.py` | The LoopCart application — defines and calls `greet()` |
| `README.md` | Project documentation (this file) |
| `PR_DESCRIPTION.md` | Template/example for writing a clear Pull Request description |
| `REVIEW_COMMENT.md` | Template/example for leaving constructive code review feedback |
 
## 📜 License
 
This project is licensed under the [MIT License](LICENSE).
 
