# HyperMatch
**Right Creator Right Brand Right Hype.**

A React + Vite front-end prototype for the AI-native creator marketplace challenge.

## Included
- AI creator portfolio cards with specialties, creative tools/models, formats, and sample workflow/verification signals
- Search plus filters for skills, content type, tools, verified profiles, and workflow proof
- Structured campaign brief builder with format, aspect ratio, creative direction, commercial usage rights, budget, and deadline
- Creator shortlisting saved in browser localStorage
- Briefs saved in browser localStorage and exported as JSON
- Responsive light pastel, deep navy, and electric teal interface

## Run locally
Install Node.js LTS from https://nodejs.org, then in this folder run:

```bash
npm install
npm run dev
```

For a production build, run `npm run build` (output folder: `dist`).

## Deploy free
Push the project to GitHub and import the repository at https://vercel.com/new. Vercel normally detects Vite automatically. Build command: `npm run build`; output directory: `dist`.

## Demo transparency
All creator names, portfolio content, prices, match scores, and verification indicators are sample data. Verification signals are illustrative, not real endorsements. Matching is deterministic front-end logic; no paid API or external AI model is connected. Saved data stays in the current browser.
