# Bacotan Workers — CV ATS Generator

AI-powered ATS CV Generator by [@bacotanworkers](https://instagram.com/bacotanworkers)

## Tech Stack
- **Frontend**: Vanilla HTML/CSS/JS (Rubik font, Bacotan Workers brand)
- **Backend**: Vercel Serverless Function (Node.js)
- **AI**: Google Gemini 1.5 Flash API

## Deploy to Vercel

1. Fork or clone this repo to your GitHub
2. Go to [vercel.com](https://vercel.com) → Import your GitHub repo
3. Add environment variable: `GEMINI_API_KEY` = your Gemini key
4. Deploy — done!

## Project Structure

```
bacotanworkers-cv/
├── api/
│   └── generate.js      ← Serverless backend (hides your API key)
├── public/
│   └── index.html       ← Frontend UI
├── vercel.json          ← Vercel routing config
└── package.json
```

## Environment Variables

| Variable | Description |
|---|---|
| `GEMINI_API_KEY` | Your Google Gemini API key from aistudio.google.com |

## Follow Us
Instagram: [@bacotanworkers](https://instagram.com/bacotanworkers)
