# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Deploy to GitHub Pages

This project is already configured for GitHub Pages.

Your live site URL is:

https://Mohitraj0031.github.io/portfolio-main

### Steps to publish

1. Make sure your project is pushed to GitHub in a repository named `portfolio-main`.
2. Confirm the `homepage` field in `package.json` matches your GitHub Pages URL.
3. Keep the Vite `base` value in `vite.config.js` set to your repository name, for example `/portfolio-main`.
4. Install dependencies:

```bash
npm install
```

5. Build and deploy with one command:

```bash
npm run gh
```

This command builds the app first, then publishes the `dist` folder to the `gh-pages` branch.

### If the link does not open

Go to your GitHub repository settings, open the Pages section, and confirm that the site is being served from the `gh-pages` branch.
