# Connect this project to GitHub

Your local Git repo is ready. Follow these steps to save your changes to GitHub.

## 1. Create a new repository on GitHub

1. Go to **https://github.com/new**
2. **Repository name:** `propbotix` (or any name you like)
3. Leave it **empty** (no README, no .gitignore — we already have them)
4. Click **Create repository**

## 2. Connect and push from your machine

In a terminal, from the `propbotix` folder, run (replace `YOUR_USERNAME` with your GitHub username):

```powershell
cd c:\Users\kamal\my-projects\propbotix

git remote add origin https://github.com/YOUR_USERNAME/propbotix.git
git branch -M main
git push -u origin main
```

If GitHub asks for login, use your GitHub username and a **Personal Access Token** (not your password). Create one at: **https://github.com/settings/tokens** — enable the `repo` scope.

## 3. Save future changes

Whenever you make changes:

```powershell
cd c:\Users\kamal\my-projects\propbotix
git add .
git commit -m "Describe your changes"
git push
```

You can also use **Cursor’s Source Control** (Ctrl+Shift+G): stage, commit, and push from the UI if the GitHub extension is set up.
