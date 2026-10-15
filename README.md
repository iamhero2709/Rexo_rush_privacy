# Rexo Rush policy website

Publisher: ZERO SHOT LAB  
Contact: randhir2709vns@gmail.com  
Updated: 16 October 2026

These static files match the current in-app Privacy Policy and Terms of Service for `com.rexo.rush`.

## Upload to the existing GitHub repository

1. Open `iamhero2709/Rexo_rush_privacy` on GitHub.
2. Use **Add file → Upload files**.
3. Upload/replace `index.html`, `privacy.html`, `terms.html`, `styles.css` and `policies.json` in the repository root. Upload the files themselves, not a containing folder or ZIP.
4. Commit the changes to the branch used by GitHub Pages (normally `main`). Existing Pages settings can remain as they are.
5. After deployment completes, open both URLs below and confirm the date **16 October 2026** and the updated RevenueCat/cloud-save sections.

- Privacy: https://iamhero2709.github.io/Rexo_rush_privacy/privacy.html
- Terms: https://iamhero2709.github.io/Rexo_rush_privacy/terms.html
- Existing policy home: https://iamhero2709.github.io/Rexo_rush_privacy/

The separate `iamhero2709.github.io/app-ads.txt` file remains in the user-site repository. These policy files do not replace that file or its repository.

## Included changes

- Optional Google Play Games player profile, explicit choice of saved progress, cloud backup and deletion controls.
- Google Play / RevenueCat one-time non-consumable lifetime ad-free purchase, localized price, restore, pending payments and refunds.
- All in-game ads disabled for verified lifetime ad-free owners, including rewarded videos; one video-free revive per run.
- AdMob / Google consent choices and third-party processing.
- Optional local daily streak reminders and Google Play ratings/reviews.
- Local coins/items have no cash value; no real-money coin packs in this version.
- Local deletion, separate cloud/purchase records, support contact and data-deletion requests.

The in-app source is `frontend-noiap/src/legal/policies.ts`; both app screens read its shared update date. To regenerate these website files from that source, run `node scripts/export-policy-site.cjs <absolute-path-to-this-folder>` from the app folder. Keep `styles.css` in the destination.

References checked for SDK disclosures:
- https://developers.google.com/admob/android/privacy/play-data-disclosure
- https://www.revenuecat.com/docs/platform-resources/google-platform-resources/google-plays-data-safety

Updating the policy does not automatically update Play Console Data Safety declarations; review them against the shipped SDKs and configuration. GitHub Pages publishes these files from the configured branch after a successful push and deployment.
