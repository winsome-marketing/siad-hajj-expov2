# SIAD Hajj Expo 2026 — Landing Page

## Deploy on GitHub Pages
Upload `index.html` and the entire `assets/` folder to the root of your GitHub repository. Go to **Settings → Pages → Deploy from a branch → main / (root)**.

## Functionality
- Fully responsive, four main page sections.
- Six compact service rows with service-specific CTAs.
- Clicking a service CTA scrolls to the meeting form and preselects that service without removing other selections.
- Form offers multiple service choices and shows the associated brand.
- Meeting request currently opens the visitor's email client. **It does not collect/store leads**. Integrate a backend/CRM before an ad campaign.

## Image notes
- Main hero/background image (`assets/hero.webp`) is local and works when deployed with the assets folder.
- Brand logos are sourced from the provided public URLs with a text fallback when unavailable. For fully offline-safe logos, replace URLs with authorized locally stored logo files.
- `assets/madinah.webp` is a local fallback destination visual, not an official Hajj Expo promotional image. Replace it with an approved Expo asset if desired.
- Replace any provisional content or event venue details after SIAD's review.


## V6 changes
- All six service logos use locally bundled crops from the uploaded SIAD company profile, to avoid broken logos caused by blocked external image hosts. These are profile-era brand variants; replace them with approved current local logo assets before launch.
- Larger, high-contrast logo area.
- Clearer multi-service note and a new general Request a Meeting CTA that clears service pre-selection. Individual Discuss service buttons continue to select their associated service.


V7: logo overlap fix — all locally bundled logos now fit within strictly clipped 104×70 desktop and 82×57 mobile containers, uniform row spacing and no overflow.
