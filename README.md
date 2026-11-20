# Namma Web — Official Website (Vercel-Ready)

Karnataka's 1st Sovereign AI Company — single-page, fully self-contained website.
All images (including 14 gallery photos) are embedded as base64 data URIs inside
`index.html`, so there are no asset folders to deploy and nothing to break.

## What's inside

| File          | Purpose                                        |
|---------------|------------------------------------------------|
| `index.html`  | The complete website (markup + styles + scripts + all images) |
| `vercel.json` | Vercel config (clean URLs, security & cache headers)          |
| `robots.txt`  | Search-engine crawler rules                                   |
| `sitemap.xml` | SEO sitemap                                                   |
| `llms.txt`    | LLM-facing site summary                                       |

## Deploy to Vercel (2 minutes, no build step)

1. Go to https://vercel.com/new and sign in (GitHub/Google account).
2. Drag-and-drop this folder (or the zip) onto the dashboard — "Deploy"
   (or: New Project → Import → select the folder / upload the zip).
3. No build settings are needed — Vercel serves `index.html` as a static site.
4. Optional: add your domain in Settings → Domains.

## Features

- Fully responsive (desktop, tablet, mobile) with mobile hamburger menu
- New **Photo Gallery** section with category filters and zoom lightbox
- Working contact / application forms (Google Apps Script backend)
- SEO/AEO/GEO meta tags, Open Graph, Twitter cards, JSON-LD structured data
- Alpine.js interactivity: menus, FAQ, blog, reviews, modals — all verified
