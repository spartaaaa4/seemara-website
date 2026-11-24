# Seemara Website

Public marketing website for Seemara, an AI company founded by Mamta Mor. Seemara builds custom AI systems for Indian small and medium businesses and runs Aha Frames (animation and e-learning, https://ahaframes.com) and Kaizen (AI ad creatives).

## Pages

- `index.html` - Homepage: offerings (custom AI systems, Aha Frames, Kaizen), founder, FAQ
- `about.html` - Company facts and founder (the canonical "about" page for search and AI assistants)
- `kaizen.html` - Kaizen product page
- `blog/` - Blog index and articles by Mamta Mor

## Search and AI-assistant readiness

- `llms.txt` - plain-markdown summary of Seemara for AI assistants
- `robots.txt` - welcomes search engines and AI crawlers, points to the sitemap
- `sitemap.xml` - every public page; update it when you add an article
- Every page carries schema.org JSON-LD: Organization (founder Mamta Mor), Aha Frames as a sub-organization, Person, BlogPosting and FAQPage

Contact on every page: mamta@seemara.com

## Features

- Static HTML/CSS/JS
- English/Hindi language toggle
- Buyer-focused solution sections for Indian SMEs
- Dedicated Kaizen page
- Blog with structured data
- Vercel-ready with no build step

## Local Preview

The site is static and can be opened directly or served with any static server.

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deployment

The repository is ready to deploy directly on Vercel with no build command.
