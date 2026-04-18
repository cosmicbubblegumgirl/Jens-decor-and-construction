# Jens Decor and Construction

A sleek React + Express website for Jens Decor and Construction.

## Stack
- Frontend: React + Vite + Framer Motion
- Backend: Express + Nodemailer

## Run locally
```bash
npm install
cp server/.env.example server/.env
npm run dev
```

Frontend: `http://localhost:5173`
Backend: `http://localhost:8787`

## Notes on images
The `client/public/images/projects/*` folders are already created. In this zip, I included tasteful branded SVG placeholders because the chat-uploaded images were not directly accessible as downloadable files inside the workspace. Replace each `placeholder.svg` with your actual project photos using the same paths, or duplicate and update the paths inside `client/src/data/projects.js`.

## Branding
Included in `client/public/branding`:
- `logo-mark.svg`
- `logo-wordmark.svg`
- `favicon.svg`
- `brand-scene.svg`

## Suggested caption
**From concept to completion, thoughtfully built for the way you live.**
