# Homepage

Static source for `nurmemeti.com`, built as a Linktree-style personal homepage.

## Files

- `index.html`: static homepage template
- `styles.css`: site styling
- `assets/profile.png`: profile picture
- `CNAME`: GitHub Pages custom-domain marker for `nurmemeti.com`

## Publishing

The site is published through GitHub Pages from the `main` branch and `/` root directory.
The apex domain `nurmemeti.com` points to GitHub Pages through its four GitHub A records.

Hostpoint remains the domain registrar and DNS provider. The `www` host should be a CNAME
to `memetnur.github.io` after removing Hostpoint's existing `www` subdomain entry.
