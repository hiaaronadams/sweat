# Mr. Sweat

Landing page for **Mr. Sweat** — a fictional Japanese ion energy drink. Slogan: disrespectful to dehydration.

## Brand

- Pink: `#ff0073`
- White: `#fbfbf4`

## Stack

Plain static HTML/CSS, deployed via GitHub Pages.

## Domain setup (GoDaddy → GitHub Pages)

1. In this repo: **Settings → Pages** → set source to the `main` branch (root).
2. In GoDaddy DNS for `drinksweat.club`, add:
   - `A` records for `@` pointing to GitHub Pages IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - `CNAME` record for `www` pointing to `<github-username>.github.io`
3. The `CNAME` file in this repo is already set to `drinksweat.club` — GitHub Pages will pick it up automatically once DNS resolves.
4. Enable "Enforce HTTPS" in repo Pages settings once the certificate is issued.

## Next steps

- Drop the mascot graphic into `index.html` (`#mascot-slot`) and/or as `og-image.png` for social previews.
- Verify the Japanese tagline with a native speaker before launch — current copy is a placeholder translation.
