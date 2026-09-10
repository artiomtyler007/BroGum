# BroGum — deployment & SEO instructions

Files included:
- index.html (main site)
- sitemap.xml
- robots.txt
- README.md

Quick options to publish:

A) GitHub Pages (already deployed in this repo)
1. If the site isn't visible, enable Pages: Settings → Code and automation → Pages → Build and deployment → Deploy from a branch → Choose branch `main` (root).
2. After a few minutes the site will be available at:
   https://<your-username>.github.io/BroGum/ (for this repo: https://artiomtyler007.github.io/BroGum/)
3. Update the <link rel="canonical"> and sitemap/robots URLs in index.html to the final URL if needed.
4. Submit the final URL and sitemap to Google Search Console and Bing Webmaster Tools.

B) Netlify (alternative)
1. Go to https://app.netlify.com/drop
2. Drag the site folder (or index.html) into the drop area — Netlify publishes instantly.
3. Set a custom domain or use the free netlify.app subdomain.
4. Update canonical + sitemap URLs to the published domain and submit to search engines.

SEO launch checklist
- Create an `og-image` at /og-image.png (1200x630 recommended) and add it to repo root.
- Register and verify the site in Google Search Console and Bing Webmaster Tools, then submit sitemap.
- Share links on social media and add backlinks to speed indexing.

If you want me to continue (create `og-image.png`, set up a GitHub Pages custom domain later, or submit sitemap to Google Search Console) tell me which next step to take.
