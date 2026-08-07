# pierre-bonami.github.io

Personal website for Pierre Bonami — Principal Developer at Gurobi Optimization.

Built with [Jekyll](https://jekyllrb.com/) and hosted on
[GitHub Pages](https://pages.github.com/) using the **Minima** theme.

## Local development

```bash
gem install bundler jekyll
bundle install
bundle exec jekyll serve
# open http://localhost:4000
```

## Deployment to GitHub Pages

### 1. Create the GitHub repository

- For a **user site**: create a repo named `pobonomo.github.io`
- For a **project site**: create any repo name, then set `baseurl: "/repo-name"`
  in `_config.yml`

### 2. Enable GitHub Pages

1. Go to your repository on GitHub.
2. Click **Settings** → **Pages** (left sidebar).
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Set **Branch** to `main` (or `master`) and folder `/` (root).
5. Click **Save**.

GitHub Pages will build and publish your site automatically on every push.

### 3. Git commands

```bash
# Initialise
git init
git add .
git commit -m "Initial commit — Jekyll personal site"

# Connect and push (replace URL with your repo)
git remote add origin https://github.com/pobonomo/pobonomo.github.io.git
git branch -M main
git push -u origin main
```

Your site will be live at `https://pobonomo.github.io` within a minute or two.

## File structure

```
.
├── _config.yml       # Site configuration and theme settings
├── index.md          # Single page: bio, research, projects, and links
├── assets/           # Images and static files (e.g. profile.jpg)
├── README.md         # This file
└── .gitignore
```
