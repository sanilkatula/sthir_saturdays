# Sthir Saturdays — GitHub Pages package

A dependency-free static recreation of the Sthir Saturdays Notion page.

## Deploy on GitHub Pages

1. Create a new GitHub repository.
2. Upload the contents of this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your main branch and `/ (root)`, then save.

The site requires no build command, npm install, framework, or server.

## Add your header background

The attached brand header has already been added as:

`assets/header-bg.png`

The site is already configured to use it.

If you want to swap it later, open `index.html` and change this line near the top of the CSS:

`--hero-bg-image: url('./assets/header-bg.png');`

to another asset path of your choice.

## Main CTA

The **JOIN IN!** button uses the Google Form linked from the source Notion page:

`https://forms.gle/jkNnp8aySgCaUSRY9`

## Files

- `index.html` — complete website (HTML + CSS; no build step)
- `.nojekyll` — tells GitHub Pages to serve the site directly
- `assets/` — put your header image and any future media here
