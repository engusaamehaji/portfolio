# KoorTech Website

A modern, dark-themed portfolio website for KoorTech — Building Smart Solutions.

## Getting Started in VS Code

### Requirements
- Node.js 18+ — https://nodejs.org
- npm or pnpm

### Run locally

```bash
npm install
npm run dev
```

Then open http://localhost:5173 in your browser.

### Build for production

```bash
npm run build
```

Output goes to the `dist/` folder.

---

## Deploy to Vercel (Free)

1. Push this folder to a GitHub repository
2. Go to https://vercel.com and sign in
3. Click "New Project" and import your GitHub repo
4. Leave all settings as default — Vercel detects Vite automatically
5. Click Deploy

Your site will be live at `https://your-project.vercel.app`

---

## Deploy to Netlify (Free)

1. Go to https://netlify.com and sign in
2. Drag and drop the `dist/` folder onto the Netlify dashboard
   OR connect your GitHub repo for automatic deploys
3. Done — your site is live instantly

---

## Project Structure

```
koortech/
├── src/
│   ├── assets/          # Images (project images, profile photo, logo)
│   ├── components/ui/   # shadcn/ui components
│   ├── hooks/           # React hooks
│   ├── lib/             # Utility functions
│   ├── pages/
│   │   └── Home.tsx     # Main website page (all sections)
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css        # Global styles and theme
├── public/              # Static files
├── index.html
├── vite.config.ts
├── tsconfig.json
├── vercel.json          # Vercel deploy config
└── netlify.toml         # Netlify deploy config
```

---

Built with React, Vite, Tailwind CSS, Framer Motion, and shadcn/ui.
