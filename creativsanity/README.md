# creativsanity

Static website ready for GitHub Pages.

## Deploy on GitHub

1. Create a new GitHub repository named `creativsanity`.
2. Add the remote and push your code from your local machine:

```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/<your-username>/creativsanity.git
git push -u origin main
```

3. GitHub Actions will automatically build and deploy the site to Pages on every push to `main`.
4. After the first push, enable GitHub Pages in repo settings if needed.

## Notes

- `index.html` is already in the repository root.
- The preloader logo is `logo.png`.
