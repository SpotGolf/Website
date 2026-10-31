# Website

The [spot.golf](https://spot.golf/) website.

Built with [Hugo](https://gohugo.io/) (extended) and [Tailwind CSS v4](https://tailwindcss.com/).

## Requirements

* Hugo extended (`brew install hugo`)
* Node.js and npm

## Local development

Install the CSS toolchain once:

```bash
npm install
```

Then run the dev server:

```bash
hugo server
```

The site is served at http://localhost:1313/ with live reload.

## Production build

```bash
hugo --gc --minify
```

The generated site is written to `public/`. Pushing to `main` builds and deploys it to GitHub Pages.

## Layout

```
assets/css/main.css    Tailwind entry point and colour tokens
content/               Homepage intro and the privacy policy
data/projects.yaml     The projects listed on the homepage
layouts/               Templates and partials
static/                Images, favicons, CNAME, and other files copied as-is
```
