# Blank Website

This is a minimal static site (single `index.html`).

Run locally (Python 3):

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

Alternative (Node):

```bash
npx http-server -p 8000
```

Publish to GitHub Pages (one-time setup):

1. Create a GitHub repository (on github.com) named `msaf00` (or any name).
2. From the project folder run:

```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
# replace <your-remote-repo> with the repository URL you created
git remote add origin <your-remote-repo>
git push -u origin main
```

After the push completes, GitHub Actions will run the workflow and publish the site to GitHub Pages. The site will be available at:

`https://<your-github-username>.github.io/<repo>`

If you want, I can create the repo and push for you — you'll need to provide a GitHub access token with repo permissions. Alternatively, run the commands above and share the repo URL and I'll confirm the deployment.

