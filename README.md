# Gaurav's Developer Portfolio

A single-page portfolio built with plain HTML, CSS and JavaScript. No build step or dependencies.

## Run locally (VS Code)
1. Open this folder in VS Code (`File > Open Folder`).
2. Install the **Live Server** extension, right-click `index.html` and choose **Open with Live Server**.
   Or just double-click `index.html` to open it in your browser.

## Edit your details
Open `index.html` and find the `CONFIG` object near the bottom. Projects, links, skills, education and achievements are all there.

## Push to GitHub
```bash
git init
git add .
git commit -m "Add portfolio"
git branch -M main
git remote add origin https://github.com/gauravch09/<your-repo-name>.git
git push -u origin main
```
Create the empty repo on GitHub first (without a README).

## Deploy
- **GitHub Pages:** repo Settings > Pages > Deploy from branch `main` / root.
- **Netlify:** drag and drop this folder at app.netlify.com/drop.
- **Vercel:** import the GitHub repo; no settings needed.
