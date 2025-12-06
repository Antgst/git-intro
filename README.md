# Git Intro Project

# 🧰 Git Intro — Versioning Like a Pro

## 📝 Description
Version control is a core skill in modern software development. Git allows developers to record every change, return to stable versions, and experiment safely. GitHub adds a collaborative layer with remote hosting, Pull Requests, code review, and team workflows.

This beginner-friendly project introduces Git and GitHub through a progressive, hands-on path. Across guided tasks, you will learn how to set up Git, track changes, collaborate with a remote repository, work with branches, resolve conflicts, and recover safely using rollback strategies.

## 🎯 Learning Objectives
By the end of this project, you will be able to:
- Install and configure Git with a user identity.
- Create and manage a repository locally and remotely on GitHub.
- Track changes using commits, understanding the working directory, staging area, and history.
- Use `.gitignore` to exclude unnecessary files.
- Push and pull changes between local and remote repositories using secure authentication (Personal Access Token).
- Work with branches to isolate development.
- Merge branches and resolve conflicts effectively.
- Perform rollbacks using both `git reset` and `git revert`.
- Apply a complete professional workflow:
  **branch → commit → push → Pull Request → merge → conflict resolution → rollback**

## 🧠 Competences Developed

### 🛠️ Technical Competences
- Practical command usage:
  `init`, `add`, `commit`, `status`, `log`, `branch`, `checkout`, `switch`,
  `merge`, `push`, `pull`, `reset`, `revert`, `tag`, `remote`.
- Remote configuration and upstream setup.
- Secure authentication with Personal Access Tokens.
- Hands-on experience with GitHub Pull Requests and conflict resolution.

### 💼 Professional Competences
- Writing clear, descriptive commit messages.
- Using branching strategies for clean collaboration.
- Resolving conflicts methodically and safely.
- Choosing the right rollback strategy depending on context.

### 🔁 Transferable Competences
- Readiness for teamwork in professional environments.
- Adaptability to other platforms (GitLab, Bitbucket).
- Strong problem-solving reflexes for real workflows.

## ✅ Requirements / Prerequisites
- A Git-enabled environment (Linux/macOS/Windows + WSL recommended).
- A GitHub account.
- Basic command-line navigation.

## 🔄 Suggested Workflow (GitHub Flow)
1. Create a new branch:

   ```bash
   git switch -c feature/my-change
   
2. Make changes and commit:

	```bash
	git add .
	git commit -m "Add feature X"
   
4. Push the branch:

   	```bash
	git push -u origin feature/my-change
   
5. Open a Pull Request on GitHub.

6. Resolve feedback and conflicts if needed.
   
7. Merge to main.
    
8. If something goes wrong, rollback safely:

  	```bash
	git revert <commit_sha>

## 🧾 Useful Commands Cheat Sheet:
# ⚙️ Setup
- git config --global user.name "Your Name"
- git config --global user.email "you@email.com"

# 🗂️ Start a repo
- git init

# ✅ Track & commit
- git status
- git add <file>
- git add .
- git commit -m "Your message"
- git log --oneline --graph --decorate

# 🌍 Remotes
- git remote add origin <repo_url>
- git push -u origin main
- git pull

# 🌿 Branching
- git branch
- git switch -c new-branch
- git merge new-branch

# 🚫 Ignore files
- touch .gitignore

# ⏪ Rollbacks
- git reset --hard <commit_sha>   # destructive, local history rewrite
- git revert <commit_sha>         # safe, creates a new commit

## 🧩 Notes
- Prefer small, frequent commits with clear messages.
- Use `git revert` for shared histories when working with others.
- Use `git reset` cautiously (especially if commits were pushed).

## 📚 Resources
- Pro Git Book
- Git Command Reference
- GitHub: Getting Started
- GitHub Flow
- Managing Merge Conflicts

## 👤 Author
Antoine Gousset — Holberton student & future fullstack dev
- GitHub: https://github.com/Antgst

