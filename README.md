# cucina-povera.se

Static website (HTML/CSS/JS) prepared for Git and Vercel.

Structure:
- index.html, 404.html, 401.html
- css/, js/, images/, documents/
- vercel.json for cache headers on static assets

Git:
- Initialize: git init && git add -A && git commit -m "Initial commit"
- Add remote: git remote add origin https://github.com/<USER>/cucina-povera.se.git
- Push: git push -u origin main

Vercel deployment:
- Recommended: Connect the GitHub repo in Vercel Dashboard for auto-deploys
- CLI: export VERCEL_TOKEN=... && vercel --prod --confirm --token "$VERCEL_TOKEN"
