# nori-site

Source of the public landing page and Datenschutzerklärung for the
**Nori – Baby Journal** iOS app. Served via GitHub Pages from the
`main` branch at
<https://mapl92.github.io/nori-site/>.

This repository is deliberately separate from the app repo so the iOS
source can stay private while the content users and App Store reviewers
need to reach stays public.

## What's in here

| File | Purpose |
|---|---|
| `index.md` | Landing page — short Nori intro plus a link to the privacy policy |
| `privacy-policy.de.md` | German privacy policy (DSGVO-compliant draft — placeholders in `{{…}}` must be filled in before public launch) |

## Publishing changes

Both files are rendered to HTML by GitHub Pages' default Jekyll
pipeline. Edit the markdown on `main`, push, wait ~1 minute for the
Pages build to finish, and the change is live. No local build step.
