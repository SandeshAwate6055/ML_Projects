# ML_Project (workspace)

This repository stores multiple machine-learning projects as separate folders.

Structure:

- `Insurance_EDA/` — Insurance dataset EDA and model starter
- Add new projects as subfolders at the root, e.g. `My_New_Project/`.

How to add a new project:

1. Create a new folder in the repo root.
2. Add code, data (or reference data via README), and a per-project `README.md`.
3. Commit and push.

Initial setup (local):

```bash
cd "d:/ML _Projects"
git init
git add .
git commit -m "Initial commit: add Insurance_EDA project"
```

Push to GitHub (create a remote repo first):

```bash
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

Or using GitHub CLI (if authenticated):

```bash
gh repo create <repo-name> --public --source=. --remote=origin --push
```
