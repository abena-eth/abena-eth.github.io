# abenasplaining

A buildless static link page for Abena. Style based on the supplied Canva deck: lavender, black sans-serif typography, generous spacing and understated candlestick graphics. Original link destinations and portrait taken from https://linktr.ee/abenasplaining on 15 October 2026.

## Edit

Edit index.html. Colours are CSS variables near the top. All nine destinations are ordinary HTML links. No JavaScript, tracking, framework, remote fonts, or build step is required.

## GitHub Pages

1. Create a public GitHub repository, for example abenasplaining-links.
2. Upload the contents of this folder, including assets and .nojekyll, into the repository root.
3. Settings → Pages → Deploy from a branch → main → /(root) → Save.
4. Wait for the Pages deployment to finish. The address will be https://YOUR-USERNAME.github.io/abenasplaining-links/.
5. For your own domain, first configure and verify it in GitHub's Pages settings, then follow the DNS instructions below. Enable Enforce HTTPS when the certificate is ready.

https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

The domain was not supplied, so no CNAME file or canonical URL is set. Add these once the final domain is known. Hosting is free for public repositories; domain registration/renewal is separate.

## Cloudflare Pages alternative

Upload this folder as a Pages Direct Upload project, or connect a GitHub repository (no build command). Add your domain under Pages → Custom domains. An apex domain requires Cloudflare nameservers; a subdomain can use a CNAME at your existing DNS provider.

https://developers.cloudflare.com/pages/configuration/custom-domains/

## Preview

python3 -m http.server 8765

Then open http://localhost:8765. The page also opens directly as a local HTML file.
