# Commera website

Launch page for [Commera](https://github.com/bwhtech/commera), the open-source storefront and merchant dashboard for ERPNext.

Static HTML with Tailwind CSS v4 and Alpine.js. `dist/site.css` is committed so GitHub Pages can serve the repo as is.

## Build the CSS

```sh
npm install
npx @tailwindcss/cli -i src/input.css -o dist/site.css --minify
```

Preview with any static server, for example `python3 -m http.server`.
