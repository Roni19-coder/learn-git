# Git & GitHub Quick Guide

## What is Git?
Git is a Version Control System that helps track changes in your code and collaborate with others.

## What is GitHub?
GitHub is a cloud platform for hosting Git repositories and collaborating on projects.

---

## Configure Git

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

Check configuration:

```bash
git config --list
```

---

## Create a Repository

```bash
mkdir my-project
cd my-project
git init
```

---

## Basic Workflow

Check status:

```bash
git status
```

Stage files:

```bash
git add .
```

Commit changes:

```bash
git commit -m "Initial commit"
```

View commit history:

```bash
git log --oneline
```

---

## Connect to GitHub

Add a remote repository:

```bash
git remote add origin https://github.com/username/repository.git
```

Push your code:

```bash
git branch -M main
git push -u origin main
```

After the first push, simply use:

```bash
git push
```

---

## Clone a Repository

```bash
git clone https://github.com/username/repository.git
```

---

## Branching

Create a new branch:

```bash
git switch -c feature
```

Switch branches:

```bash
git switch main
```

Merge a branch:

```bash
git merge feature
```

---

## Useful Commands

```bash
git status
git add .
git commit -m "message"
git push
git pull
git clone <url>
git branch
git switch <branch>
git log --oneline
git remote -v
```

---

## Typical Git Workflow

```text
Edit Files
    ↓
git status
    ↓
git add .
    ↓
git commit -m "message"
    ↓
git push
```

---

## Best Practices

- Commit frequently with meaningful messages.
- Pull before pushing to avoid conflicts.
- Use separate branches for new features.
- Never commit passwords or API keys.
- Add unnecessary files to `.gitignore`.

Happy Coding! 🚀