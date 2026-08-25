# Feng Xiao — Academic Website

Source files for the personal academic website of Feng Xiao.

## Repository name

Create a public GitHub repository named exactly:

`Cellphonexf.github.io`

## Easiest deployment route

1. Upload all files in this folder to the repository root, including the hidden `.github` folder.
2. Commit and push to the `main` branch.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment → Source**, select **GitHub Actions**.
5. Open the repository **Actions** tab and wait for the `Publish Quarto website` workflow to finish.
6. The site should then be available at `https://cellphonexf.github.io`.

You do **not** need to install Quarto locally for this workflow; GitHub Actions installs it automatically.

## Editing the website

- Home: `index.qmd`
- Research: `research.qmd`
- Publications: `publications.qmd`
- CV: `cv.qmd`
- Contact: `contact.qmd`
- Design: `styles.css`
- Navigation/site settings: `_quarto.yml`
- Profile image: `assets/profile.jpg`

After editing, commit and push. GitHub Actions will rebuild the website automatically.

## Recommended next additions

- Add your Google Scholar profile once you decide on the public URL.
- Replace the placeholder Google Search Console verification code in `_quarto.yml` after registering the site with Google Search Console.
- Add a downloadable English academic CV PDF to `files/` and link it from `cv.qmd`.
- Optionally connect a custom domain later.
