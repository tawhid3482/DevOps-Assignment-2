# 🛠️ DevOps Assignment 2 – Git Branching & Workflow

## 📌 Project Overview
This project demonstrates real-world Git workflow practices including branching strategy, merging, rebasing, commit history management, and professional version control techniques. The goal is to simulate a collaborative software development environment using Git.

---

## 📁 Repository Structure

main
├── develop
│ ├── feature/login
│ ├── feature/payment
│ ├── feature/profile
│ └── bugfix/login-error

---

## 🚀 Git Workflow Implementation

### 🔹 1. Repository Initialization
The repository was initialized and configured with remote GitHub origin.

### Commands Used:
```bash
git init
git branch -M main
git remote add origin <repository-url>
git push -u origin main
🔹 2. Branching Strategy

Multiple branches were created following feature-based development:

Feature Branches:
feature/login
feature/payment
feature/profile
Bugfix Branch:
bugfix/login-error
Commands Used:
git checkout -b develop
git checkout -b feature/login
git checkout -b feature/payment
git checkout -b feature/profile
git checkout -b bugfix/login-error
🔹 3. Merge & Rebase Strategy
✔ Merge Strategy

A feature branch was merged into develop using standard merge:

git checkout develop
git merge feature/login
✔ Rebase Strategy

A feature branch was rebased onto develop to maintain linear history:

git checkout feature/payment
git rebase develop
🔹 4. Commit History Management

A feature branch was used to demonstrate advanced commit history manipulation.

Steps Performed:
Created at least 5 commits
Performed interactive rebase
Squashed multiple commits into a single commit
Reworded commit messages for clarity
Commands Used:
git rebase -i HEAD~5

During interactive rebase:

pick → keep commit
squash → combine commits
reword → modify commit message

---

## 📊 Key Git Concepts Used

### 🔀 Merge vs Rebase
- **Merge:** Combines branches and preserves full history
- **Rebase:** Rewrites commit history for a clean linear structure

### 🧹 Squash
Combines multiple commits into a single meaningful commit to keep history clean.

### ✏️ Reword
Allows modification of commit messages during interactive rebase.

---

## 📸 Screenshots
> Add your screenshots here:
<img width="960" height="509" alt="Screenshot 2026-04-12 154219" src="https://github.com/user-attachments/assets/ca6906f9-7c36-42ca-909e-2f6aed959447" />
<img width="597" height="174" alt="Screenshot 2026-04-13 134153" src="https://github.com/user-attachments/assets/7a584eec-bea3-4c11-b4b7-215cbe946c74" />
<img width="694" height="417" alt="Screenshot 2026-04-12 160514" src="https://github.com/user-attachments/assets/3cb22f6e-ca9c-4a50-94c5-9f3621f4a757" />
<img width="929" height="490" alt="Screenshot 2026-04-12 154658" src="https://github.com/user-attachments/assets/b933e465-ef50-43a2-8c26-0355148f57c3" />
<img width="626" height="407" alt="Screenshot 2026-04-12 155428" src="https://github.com/user-attachments/assets/bc401233-1cec-46ff-9301-2b2ab2840f39" />
<img width="638" height="214" alt="Screenshot 2026-04-12 155527" src="https://github.com/user-attachments/assets/c35b4393-de75-4966-839a-5498a8827308" />
<img width="946" height="487" alt="Screenshot 2026-04-13 130014" src="https://github.com/user-attachments/assets/78468e9d-a774-4706-a0b8-98758a8b98e3" />
<img width="960" height="506" alt="Screenshot 2026-04-13 131144" src="https://github.com/user-attachments/assets/73a091df-a158-4baf-a11f-178b2fdb5b24" />
<img width="743" height="209" alt="Screenshot 2026-04-13 131535" src="https://github.com/user-attachments/assets/d7808a25-be8c-42f1-8532-6d6fe3af6c0a" />
<img width="953" height="505" alt="Screenshot 2026-04-13 124925" src="https://github.com/user-attachments/assets/db914c11-eb04-460a-8540-48a388acb5be" />


---

## 🧠 Learning Outcomes
- Understanding Git branching workflow
- Practical experience with merge and rebase strategies
- Commit history management using interactive rebase
- Professional repository organization

---

## 📌 Submission Info
- Repository: https://github.com/tawhid3482/DevOps-Assignment-2
- Author: Tawhidul Islam
