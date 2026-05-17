# Play Console Preparation Notes

Last updated: May 17, 2026

This file is a working checklist for the Google Play setup work tied to NoNet Translate.
It is not a substitute for reviewing the actual app build and Play policy requirements.

## Recommended public URLs from this repository

- Landing page: `https://modabayi.github.io/nonet-translate/`
- Privacy policy: `https://modabayi.github.io/nonet-translate/privacy-policy.html`
- Support page: `https://modabayi.github.io/nonet-translate/support.html`
- App access guidance: `https://modabayi.github.io/nonet-translate/app-access.html`

These URLs will work after GitHub Pages is enabled for the `main` branch and repository root.

## Sections to complete in Play Console

### 1. Privacy policy

- Use the public URL for `privacy-policy.html`.
- Make sure the final policy includes the same developer identity and contact email shown in the store listing.
- If the app collects or shares any user data, edit the policy before submission so it is exact.

### 2. App access

- If the app does not require login, declare that no login is required.
- If login is required, do not publish credentials in this repo. Enter reviewer credentials only in Play Console.

### 3. Ads

- If the app shows ads, declare ads in Play Console and update the privacy policy accordingly.
- If the app does not show ads, declare no ads.

### 4. Content rating

- Complete the IARC questionnaire based on the actual app experience.
- Keep the public store listing language suitable for a general audience.

### 5. Target audience

- If the app is not designed for children, select the appropriate non-child audience bands.
- If children are included, review Families Policy obligations before publishing.

### 6. Data safety

- Answer based on the shipped build, all SDKs, and all backend behavior.
- Keep the Data safety answers consistent with the privacy policy.

### 7. Official organizations

- Mark this only if the app represents a government or official public institution.

### 8. Finance-related features

- Mark this only if the app includes payments, lending, trading, wallets, or related financial behavior.

### 9. Health

- Mark this only if the app offers health, medical, wellness diagnosis, or related regulated functionality.

### 10. Category and contact details

- Pick the most accurate application category.
- Add a real support email.
- Use the GitHub Pages URL as the website after publishing.

### 11. Store listing

Prepare these separately in Play Console:

- app title
- short description
- full description
- app icon
- feature graphic
- phone screenshots
- tablet screenshots if applicable

## Suggested content direction for the public site

- Emphasize the product clearly without exposing private source code.
- Keep the privacy page stable and public.
- Keep contact information current.
- Add screenshots later if you want the site to become a fuller marketing page.
