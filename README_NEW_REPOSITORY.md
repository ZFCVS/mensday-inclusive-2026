# International Men's Day 2026 — Inclusive Appreciation Character Studio

**Complete static website source for a NEW GitHub Pages repository.**

This package combines the existing V22 website (homepage, modules, logos and vehicle images) with the inclusive appreciation release. It is **not** the older eight-file patch: this archive contains the actual deployable folder tree.

## Create a new GitHub repository (no commands needed)

1. Log in to GitHub and choose **New repository** (under your chosen GitHub account/organisation).
2. Choose a new repository name, for example `mensday-inclusive-2026`. Select **Public** if using ordinary free GitHub Pages, subject to your organisation's approval. Do not publish sensitive information.
3. Extract this ZIP locally. Open the folder named `V22_Inclusive_New_GitHub_Repository`.
4. On the new repository's GitHub Code tab, click **uploading an existing file** / **Add file → Upload files**.
5. Drag **all extracted CONTENTS** (`index.html`, `block-figure.html`, `src`, `assets`, `.nojekyll` etc.) into the upload area. Keep the paths and folders. Upload CONTENTS, not the outer folder or ZIP.
6. Commit to `main`.
7. Go to **Settings → Pages → Build and deployment**, choose **Deploy from a branch** → `main` → `/(root)` → Save.
8. After GitHub Pages reports success, visit `https://YOUR_ACCOUNT.github.io/REPOSITORY_NAME/` and open `block-figure.html` from the homepage.
9. Hard-refresh or test in a private browser window. Run the checks below before distributing.

**Important:** QR and share-link generation now derive their site address from the actual HTTPS GitHub Pages repository path. There is no old `mensday-2026-v22` path restriction. Existing old card links still point to the old repository and are not automatically migrated.

## What's inside

- `index.html` — inclusive homepage
- `block-figure.html` — studio and recipient preference selection
- `src/` — all necessary JS/CSS/MJS modules, including GIF/QR, character geometry, personality, sharing and Outlook workflow
- `assets/brand/` — existing ZF logo image assets
- `assets/vehicles/` — existing truck and bus images
- `.nojekyll` — publish directories unchanged on GitHub Pages

## Corporate font caveat

The ZF Prometo **font files are not included**. You may add your own appropriately licensed copies to `assets/brand/fonts/` as instructed there. Without the fonts, the site works with Arial/system fallbacks, but the branded typography will differ. All other required image assets and application code are included.

## Mandatory acceptance checks

1. Homepage opens, start button opens studio.
2. Man / Woman / Non-binary or gender-diverse / No preference each generate three starting looks.
3. Customize body proportions, hair and clothing; check both ZF polos and the chest logo position.
4. Hero/superhero variations render and keep their suit.
5. PNG and GIF export; compare their palette and view output files.
6. Check QR and Copy card link. Open it on a second phone; the URL MUST refer to your NEW repo.
7. Share Card → Copy my greeting → Open Outlook → Paste in Email Body; verify complete recipient greeting and both links.
8. Check mobile UI, downloads, and new recipient card view.
9. If relevant, open a previously issued card from the OLD repo to verify old links still work there.

## Known limits

- No server backend, database, global usage metrics or private access by default.
- GitHub Pages is public, and the interactive card's `#gms=` URL contains personal greeting data. Treat the link as shareable, not secret.
- Outlook subject-only compose opens a draft; it cannot verify that an email was sent or paste into Outlook for the user.
- The new inclusive release passed source/geometry/token QA previously, but browser-based visual and live Outlook acceptance tests were not completed in this environment.
- GitHub Pages deployments may take a little time to become available; check the Actions/Pages status rather than assuming success.

## Security and licensing

Do not put API keys, employee lists, analytics secrets, authentication credentials or confidential material into this public repository. Confirm corporate approval for publicly publishing ZF trademarks and imagery. This package makes **no backend calls for analytics**.
