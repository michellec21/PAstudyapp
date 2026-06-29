# PA Study App

A personal PA school study dashboard. Works as a Progressive Web App (PWA) — install it on your phone home screen for a native app feel.

## Features
- **Exam tracker** — add test dates with countdowns and urgency colors
- **Study schedule** — daily tasks with streak tracking
- **Notes** — built-in quick-reference notes + AI-generated from your uploads
- **Quiz** — built-in question bank + questions generated from your files
- **Upload** — drop PDFs and get AI-extracted notes and quiz questions
- **Patient cases** — clinical case simulator

## Deploy to Vercel (free, 2 minutes)

1. Go to [vercel.com](https://vercel.com) and sign up (free)
2. Click **Add New → Project**
3. Click **Upload** (or connect GitHub — see below)
4. Drag this entire folder in
5. Click **Deploy**
6. You'll get a URL like `pa-study.vercel.app`

## Deploy via GitHub (recommended for updates)

1. Create a free account at [github.com](https://github.com)
2. Create a new repository called `pa-study`
3. Upload these files to it
4. Go to [vercel.com](https://vercel.com) → New Project → Import from GitHub
5. Select your repo → Deploy
6. Any future file changes you push will auto-redeploy

## Add to iPhone home screen

1. Open your Vercel URL in **Safari**
2. Tap the **Share** button (box with arrow)
3. Tap **Add to Home Screen**
4. Name it **PA Study** → tap **Add**

It will open full-screen like a native app, with no browser bars.

## AI-powered uploads

To use the file upload feature (AI note extraction + quiz generation):
1. Get a free API key at [console.anthropic.com](https://console.anthropic.com)
2. In the app, tap **Upload** → enter your API key
3. Your key is stored only on your device (never sent anywhere except Anthropic)

## Data storage

All your data (exams, tasks, notes, uploaded file results) is saved to your browser's localStorage — it persists across sessions on the same device.

## Files

- `index.html` — the entire app (single file)
- `manifest.json` — enables "Add to Home Screen" as a PWA
