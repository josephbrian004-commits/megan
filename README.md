# Megan Films

A static world cinema catalog. Visitors can search films by title, country, and language, then follow official watch links.

## Preview locally

Run `python3 -m http.server 8000` in this folder and open http://localhost:8000.

## Add a film

Add a record to `movies.json` using the example in `movies.example.json`. Use official or otherwise authorized watch links. Only add a direct `videoUrl` when you have permission to stream that video.

## Deploy to Vercel

Import this GitHub repository. Select **Other**, leave the build command empty, and set output directory to `.`.

## Before publishing

Replace `hello@example.com` in `contact.html` and `legal.html`, and update the placeholder domain in `robots.txt` and `sitemap.xml`. The optional TMDB key in `config.js` is public to site visitors if configured.
