ALHASSAN TAREK — PORTFOLIO WEBSITE
==================================

What it is: a plain static website (HTML + CSS + a little vanilla JavaScript).
No framework, no npm, no build step. The folder itself is the production build.

To preview: double-click index.html.

To deploy: upload the whole folder as-is to any static host, for example:
- Netlify Drop (app.netlify.com/drop): drag the folder in.
- Vercel / Cloudflare Pages / GitHub Pages: point them at this folder, framework
  "Other / None", no build command, output directory "." (the folder root).
index.html is the homepage, so the site works at the root URL.

Pages
- index.html ............ Homepage
- full-production.html .. Project 01 · Full production content
- ai-ads.html ........... Project 02 · AI Ads
- ttls.html ............. Project 03 · Post Production of TTLs
- ugcs.html ............. Project 04 · UGCs
- moodboard.html ........ Type + colour moodboard (not linked from the site, marked noindex;
                          leave it out of the upload if you don't want it public)

assets/
- logos/    brand logos for the "Worked with" strip
- frames/   hover flipbook frames and video-card covers
- thumbs/   extra video-card covers
- video/    the scroll-played showreel clip, its blurred background, and the poster
- favicon.svg

Notes
- Fonts (Archivo + Geist Mono) load from Google Fonts.
- The full showreel button and all video cards open YouTube / Vimeo.
