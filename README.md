# Invite site (playcollectopus.github.io)

Source of the public GitHub Pages site that friend invite links point to:
`https://playcollectopus.github.io/i/CODE`.

- `.well-known/assetlinks.json` — lets Android open these links straight in
  the app (App Links). Holds the app id and the SHA-256 of every key that
  signs the app: now only the debug key; add the upload key and the Play
  App Signing key before the Play release.
- `404.html` — GitHub Pages serves it for `/i/CODE` (no such file): shows
  the code and an "Open Collectopus" button.
- `.nojekyll` — without it GitHub Pages hides the `.well-known` folder.

No mention of the company behind the app on this site.
