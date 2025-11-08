# makimsa.github.io

This repository now contains a minimal React + Vite starter for your personal site.

Quick start (on macOS / zsh):

1. Install dependencies

```bash
# with npm
npm install

# or with yarn
yarn
```

2. Run the dev server

```bash
npm run dev
# then open http://localhost:5173
```

3. Build for production

```bash
npm run build
npm run preview   # serve the built output locally
```

Files added:
- `package.json` — scripts and deps for Vite + React
- `vite.config.js` — Vite config
- `index.html` — app entry
- `src/main.jsx`, `src/App.jsx`, `src/index.css` — starter app
- `.gitignore`

## Deployed Site

🌐 **Live at: https://makimsa.github.io**

The site automatically deploys to GitHub Pages on every push to `main` via GitHub Actions.

## Troubleshooting

If you see a blank page or MIME type errors:
1. Ensure GitHub Pages source is set to "GitHub Actions" at: https://github.com/makimsa/makimsa.github.io/settings/pages
2. Check the workflow completed successfully: https://github.com/makimsa/makimsa.github.io/actions
3. Hard refresh your browser (Cmd+Shift+R on macOS, Ctrl+Shift+R on Windows)
4. Check browser console (F12) for specific errors

## Next steps (optional):
- Add a homepage or routing
- Add TypeScript, tests, or CI workflow
- Customize styling with Tailwind CSS or a component library

