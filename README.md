# Ahmed Elbossily — GitHub Pages Portfolio

A lightweight academic/research website inspired by the structure of maawad.github.io.

## 1. Replace the placeholders

Edit `index.html` and replace:

- `YOUR_EMAIL`
- `YOUR_GITHUB_USERNAME`
- `YOUR_LINKEDIN_URL`
- `YOUR_GOOGLE_SCHOLAR_URL`
- `YOUR_PROJECT_URL`
- `YOUR_CODE_URL`

Update the Publications section with your actual papers.

## 2. Add your profile photo

Replace:

`assets/profile.svg`

with your own image, for example:

`assets/profile.jpg`

Then change this line in `index.html`:

```html
<img class="profile-photo" src="assets/profile.jpg" alt="Ahmed Elbossily" />
```

## 3. Add your CV

Place your CV at:

`assets/Ahmed_Elbossily_CV.pdf`

## 4. Publish with GitHub Pages

Create a repository named:

`YOUR_GITHUB_USERNAME.github.io`

Then from this folder:

```bash
git init
git add .
git commit -m "Initial personal website"
git branch -M main
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME.github.io.git
git push -u origin main
```

Your site will be available at:

`https://YOUR_GITHUB_USERNAME.github.io/`

If needed, go to:

GitHub repository → Settings → Pages → Deploy from branch → `main` → `/ (root)`
