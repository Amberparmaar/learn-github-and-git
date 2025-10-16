# Learn Git and GitHub (Step by Step in Easy Words)

This README helps beginners learn **Git** and **GitHub** using **Git Bash**. It includes how to install Git, basic commands, remove old GitHub accounts, and update your projects.

---

## 1. Install Git

### 🪟 For Windows:
1. Go to [git-scm.com](https://git-scm.com/download/win)
2. Download **Git for Windows**
3. Install → Keep default settings → Finish
4. Open **Git Bash** from the Start Menu

✅ Check if Git is installed:

```bash
git --version
```

---

## 2. Set up Git (First Time)

Set your name and email:

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```
---

## 3. Basic Git Commands

### 🆕 Start a new Git project:

```bash
git init
```

### 🔍 Check status:

```bash
git status
```

### ➕ Add files:

```bash
git add file.txt   # add one file
git add .           # add all files
```

### 💾 Save changes (commit):

```bash
git commit -m "Your message here"
```
---

## 4. Connect with GitHub

### 📥 Clone a GitHub repo:

```bash
git clone https://github.com/username/repo.git
```

### 🔗 Add GitHub repo to your local project:

```bash
git remote add origin https://github.com/username/repo.git
```

### 🚀 Send (push) your code to GitHub:

```bash
git push -u origin main
```
---

## 5. Remove or Change GitHub Account

### 🪟 For Windows:

1. Open **Control Panel** → **Credential Manager** → **Windows Credentials**
2. Find `git:https://github.com` or similar entry
3. Click and **Remove** it
4. Next time you push, Git will ask for your new account details or token

---

## 6. Add GitHub Account Again

1. Try to `git push` again — Git will ask for login
2. Enter your **GitHub username**
3. Enter Password

---

## 7. Update Your Project (Step by Step)

1. Open your project folder in Git Bash:

   ```bash
   cd path/to/project
   ```
2. Get the latest code from GitHub:

   ```bash
   git pull origin main
   ```
3. Add your new or changed files:

   ```bash
   git add .
   ```
4. Save your changes:

   ```bash
   git commit -m "Updated project files"
   ```
5. Send updates to GitHub:

   ```bash
   git push origin main
   ```

---

## 8. Common Problems & Fixes

### ❌ Login failed:

* Remove old credentials and log in again with your token.

### ⚠️ Merge Conflict:

* If two people edit the same file, fix it and run:

  ```bash
  git add file
  git commit
  ```

---

## 9. Quick Commands Table

| Task              | Command                   |
| ----------------- | ------------------------- |
| Check Git version | `git --version`           |
| Start Git         | `git init`                |
| Add files         | `git add .`               |
| Save changes      | `git commit -m "message"` |
| See status        | `git status`              |
| Push to GitHub    | `git push origin main`    |

---

## ✅ Tips

* Always **pull before push** to avoid errors.
* Write **clear commit messages**.
* Practice Git commands daily.

---

**🎉 You now know how to install Git, use commands, connect GitHub, and update your projects easily!**

```
```
