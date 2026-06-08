# Em Allen — Portfolio Site (External)

Static site. No build step. Deploy directly to GitHub Pages.

## Deploy steps (after June 12)

```bash
cd ~/Desktop/em-profile/github-pages
git init
git add .
git commit -m "Initial portfolio deploy"
gh repo create em-allen-portfolio --public --source=. --remote=origin --push
```

Then in GitHub: Settings > Pages > Branch: main > folder: / (root) > Save.

Your site will be live at: https://[your-github-username].github.io/em-allen-portfolio

## Files
- index.html — portfolio site (external-clean version)
- resume.html — resume page (external-clean version)
- photo.jpg — headshot
