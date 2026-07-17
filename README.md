# Tianyi Wang — Personal Website Starter

A minimal, responsive Astro portfolio prepared for deployment to GitHub Pages at:

`https://twang736.github.io`

## 1. Install prerequisites

Install a currently supported Node.js LTS release, Git, and a code editor such as VS Code.

Verify:

```bash
node --version
npm --version
git --version
```

## 2. Run locally

```bash
npm install
npm run dev
```

Open the local URL printed in the terminal, usually `http://localhost:4321`.

## 3. Edit the content

Most text is in:

- `src/pages/index.astro`

Most appearance settings are in:

- `src/styles/global.css`

Site-wide metadata is in:

- `src/layouts/Layout.astro`
- `astro.config.mjs`

## 4. Test a production build

```bash
npm run build
npm run preview
```

## 5. Publish to GitHub Pages

Create a **public** GitHub repository named exactly:

`twang736.github.io`

Then run inside this folder:

```bash
git init
git add .
git commit -m "Build personal website"
git branch -M main
git remote add origin https://github.com/twang736/twang736.github.io.git
git push -u origin main
```

On GitHub, open:

`Settings → Pages → Build and deployment → Source → GitHub Actions`

The included workflow at `.github/workflows/deploy.yml` will build and deploy the site on every push to `main`.

## 6. Update the site later

After editing files:

```bash
git add .
git commit -m "Update portfolio content"
git push
```

GitHub Actions will redeploy automatically.

## Suggested next edits

1. Replace the “Next Project” placeholder.
2. Add verified project links.
3. Add a PDF resume to `public/resume.pdf`, then add a link to `/resume.pdf`.
4. Add LinkedIn only after confirming the exact public profile URL.
5. Consider a custom domain after the GitHub Pages URL is working.
