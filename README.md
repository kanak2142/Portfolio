# Kanak Parnerkar — Portfolio

A responsive personal portfolio built with React, Vite, and plain CSS. This is a local preview package; **nothing has been deployed or hosted**.

## Requirements
- Node.js 18+ (Node.js 20+ recommended)
- npm

## Run locally
1. Extract the ZIP.
2. Open a terminal in the extracted `kanak-portfolio` folder.
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
5. Open the local URL Vite prints (usually `http://localhost:5173`).

## Make changes
- Main page and project data: `src/main.jsx`
- Visual styling and responsive layouts: `src/styles.css`
- Resume download: `public/resume.pdf`
- Page title and metadata: `index.html`

Projects are stored in the `projects` array near the top of `src/main.jsx`. To add or edit a project, update its name, description, technologies, category, type, and `url`. Use `url: ''` or remove the `url` property if a public repository is not available. Team project labels are intentionally explicit—adjust them if any attribution needs correction.

## Check a production build locally
```bash
npm run build
npm run preview
```

## Before hosting (later)
- Verify every project description and repository URL.
- Add repository links for academic projects currently marked as pending.
- Add certificate files or links if desired.
- Replace `public/resume.pdf` when your resume changes.
- Confirm phone/email and other contact details are correct.

No hosting/deployment steps have been run. We can deploy only when you explicitly say you're ready.
