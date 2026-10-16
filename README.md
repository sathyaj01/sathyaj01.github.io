# Scale Local information site

This repository contains only a public static application homepage and privacy
policy for the self-hosted Scale Local Ubuntu monitor and its optional Google
Health integration. It does not contain a live dashboard, measurements,
credentials, OAuth callback or the private application repository.

Intended GitHub Pages URLs:

- Homepage: `https://sathyaj01.github.io/scale/`
- Privacy policy: `https://sathyaj01.github.io/scale/privacy.html`

Publish the `main` branch root using GitHub Pages. `.nojekyll` keeps deployment
limited to the supplied static files without Jekyll processing. There are no
JavaScript dependencies, external fonts, analytics or tracking integrations.

Google ownership verification is separate from GitHub Pages deployment.
Configure Google's homepage and privacy links only after both URLs are live.
Use Google Search Console with the Google Account that owns/edits the OAuth
project to verify control of the hosted site. If Google requires an HTML file
or meta tag, use the exact verification artifact generated for that account
and property; do not invent one. A verification artifact is meant to be public,
unlike OAuth client secrets, refresh tokens or authorization codes.

Do not claim ownership of `github.com` or `github.io`. The Pages namespace is
`sathyaj01.github.io`; acceptance/verification of that namespace is determined by
Google, not by publishing this repository. If Google requires additional domain
proof, resolve that requirement before re-submitting.

Google branding and restricted-scope review are not automatically completed by
publishing these pages. Do not submit "issues fixed" until the actual ownership
and policy requirements have been satisfied. Google may ask for up to 24 hours
after ownership verification before retrying.

For policy/support questions use this repository's issues, without posting
measurements, device identifiers, tokens, client JSON or private diagnostic logs.
