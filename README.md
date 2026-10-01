# seokinseo.github.io

Personal academic homepage of Seokin Seo. Static HTML, no build step.

## Deploy
1. Repo: github.com/seokinseo/seokinseo.github.io (organization site).
2. First push (git repo and remote are already set up):
   git add . && git commit -m "Initial homepage"
   git push -u origin main
   Later updates: git add . && git commit -m "..." && git push
3. Settings > Pages > Source: "Deploy from a branch", Branch: main / (root).
4. Site is live at https://seokinseo.github.io within a few minutes.

## Customize
- Profile photo: save as `assets/profile.jpg` (square, >= 400x400).
- CV: optionally place `assets/cv.pdf` and point the CV button to it.
- New paper: copy one `<article class="pub">` block; `data-k` controls filters
  (il, rl, nlp, robust, causal, mv, diff, safety, sel = Selected).
