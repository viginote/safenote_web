# SafeNote Website — Netlify Frontend

This repo hosts the public SafeNote.co.za landing page.

## Files

- `index.html` — public homepage
- `privacy.html` — privacy principles page
- `netlify.toml` — routes `/app`, `/nhw`, and `/api` to the Render backend

## One-domain architecture

Recommended public routes:

- `/` — public landing page
- `/app` — SafeNote public reporting map
- `/nhw` — NHW / CPF portal
- `/admin` — admin backend later
- `/api/*` — proxied backend API

## Setup

1. Replace `https://YOUR-RENDER-SERVICE.onrender.com` inside `netlify.toml`
2. Push this folder to a new GitHub repo
3. Connect the repo to Netlify
4. Set the custom domain: `safenote.co.za`

## Security note

Do not rely on hidden URLs for security. Protect admin/NHW routes with server-side authentication and strong secrets.
