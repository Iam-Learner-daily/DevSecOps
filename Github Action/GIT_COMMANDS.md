# 📘 Git & GitHub Commands Reference

A quick reference guide for common Git commands used in DevSecOps workflows.

---

## ⚙️ 1. Initial Configuration

Set your identity before using Git:

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

Check your config:

```bash
git config --list
```

---

## 📁 2. Create & Clone Repository

Clone an existing GitHub repo to your local machine:

```bash
git clone https://github.com/username/repository.git
```

Navigate into the cloned folder:

```bash
cd repository
```

---

## 📂 3. Stage Files

Stage all files in the current folder:

```bash
git add .
```

Stage a specific file:

```bash
git add filename.txt
```

Check what is staged:

```bash
git status
```

---

## ✅ 4. Commit Changes

Commit staged files with a message:

```bash
git commit -m "Your commit message here"
```

---

## 🚀 5. Push to GitHub

First push — sets the upstream branch:

```bash
git push -u origin main
```

All future pushes after the first:

```bash
git push
```

---

## 🌿 6. Branch Management

List all branches:

```bash
git branch
```

Rename `master` to `main`:

```bash
git branch -m master main
```

Create and switch to a new branch:

```bash
git checkout -b new-branch-name
```

Switch between branches:

```bash
git checkout main
```

---

## 🔄 7. Pull Latest Changes

Pull updates from GitHub to your local machine:

```bash
git pull origin main
```

---

## 🔍 8. View Logs & History

View commit history (short format):

```bash
git log --oneline
```

View full commit history:

```bash
git log
```

---

## 🛠️ 9. Fix Common Errors

**Error: src refspec refs/heads/main does not match any**

Cause: No commits made yet. Fix:

```bash
git add .
git commit -m "Initial commit"
git push -u origin main
```

**Error: Branch is named `master` instead of `main`**

```bash
git branch -m master main
git push -u origin main
```

---

## 📌 Quick Reference Summary

| Action              | Command                          |
|---------------------|----------------------------------|
| Clone repo          | `git clone <url>`                |
| Stage all files     | `git add .`                      |
| Commit              | `git commit -m "message"`        |
| First push          | `git push -u origin main`        |
| Subsequent pushes   | `git push`                       |
| Pull latest         | `git pull origin main`           |
| Check status        | `git status`                     |
| View history        | `git log --oneline`              |
| List branches       | `git branch`                     |
| Create branch       | `git checkout -b branch-name`    |

---

*Maintained as part of the DevSecOps learning journey* 🚀
