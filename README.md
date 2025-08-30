<img width="1384" height="613" alt="image" src="https://github.com/user-attachments/assets/ae48ba33-62fd-41b0-be7f-a8be076a6ac1" />

# 🚀 How to Push Code to GitHub

This guide explains step by step how to push your local project code to a GitHub repository.

---

## 📌 Steps

### 1️⃣ Initialize Git
Open a terminal in your project folder and initialize Git:

git init


### 2️⃣ Add Remote Repository

Create a new repository on GitHub
, copy the repo URL, and link it:

git remote add origin https://github.com/username/repo-name.git

⚠️ Replace username with your GitHub username and repo-name with your repository name.


### 3️⃣ Add Files

Stage all files for commit:

git add .


### 4️⃣ Commit Changes

Save your work with a meaningful commit message:

git commit -m "Initial commit"


### 5️⃣ Push to GitHub

Push the code to the main branch:

git branch -M main
git push -u origin main


### 🔄 Next Time (For Updates)

Whenever you make new changes, run:

git add .
git commit -m "Updated feature X"
git push

---

## ✅ Done!

🎉 Your project is now on GitHub!
Refresh your repository page to see your code.
