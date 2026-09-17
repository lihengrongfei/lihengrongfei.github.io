# Hengrongfei Li — Personal Portfolio

A lightweight, responsive academic portfolio for robotics, autonomous systems, and computer vision work.

Live site: <https://lihengrongfei.github.io/>

## GitHub Pages deployment

Repository: <https://github.com/lihengrongfei/lihengrongfei.github.io>

GitHub Pages publishes from the `main` branch and the `/ (root)` folder. The account and repository names match the default site address, so no custom domain or `CNAME` file is needed.

Pages and assets use relative links. To update an existing local clone after the rename:

```sh
git remote set-url origin https://github.com/lihengrongfei/lihengrongfei.github.io.git
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
