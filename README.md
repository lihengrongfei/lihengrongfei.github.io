# Hengrongfei Li — Personal Portfolio

A lightweight, responsive academic portfolio for robotics, autonomous systems, and computer vision work.

Site URL (after the GitHub account and repository rename): <https://lihengrongfei.github.io/>

## GitHub Pages deployment

The intended site URL is `https://lihengrongfei.github.io/`. To activate it:

1. Rename the GitHub account from `LiHengRF` to `LiHengRongFei`.
2. Rename this repository to `LiHengRongFei.github.io`.
3. In **Settings → Pages**, publish from the `main` branch and the `/ (root)` folder.
4. Wait for the Pages deployment to finish and verify the new URL.

GitHub Pages assigns the default `github.io` hostname from the account name; changing this README alone does not change the live address. Do not configure `lihengrongfei.github.io` as a custom domain or add it to a `CNAME` file.

Pages and assets use relative links, so no base URL changes are needed. After the rename, update local clones with:

```sh
git remote set-url origin https://github.com/LiHengRongFei/LiHengRongFei.github.io.git
```

## Pages

- Home: short profile, selected projects, background, and contact
- Projects: five concise project summaries
- Project details: overview, selected highlights, demo where available, and GitHub link

## Preview locally

The site has no build step. Open `index.html` directly or serve the repository with any static HTTP server.

## Structure

```text
index.html
assets/
  css/styles.css
  js/main.js
projects/
  index.html
  legged-robots.html
  ami-robot-programming.html
  intelligent-machine-programming.html
  geovision.html
  drone-racing.html
resources/files/Hengrongfei_Li_CV.pdf
```
