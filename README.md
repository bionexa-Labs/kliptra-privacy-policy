# Kliptra Privacy Policy — GitHub Pages

This folder contains the GitHub Pages website for Kliptra's Android Privacy Policy.

## Publish using your chosen GitHub account

1. Sign in to the GitHub account you want to use.
2. Create a new **public** repository named `kliptra-privacy-policy`.
3. Upload `index.html` and `kliptra-icon.png` to the repository root on the `main` branch. The README is optional.
4. Open **Settings → Pages → Build and deployment**.
5. Set **Source** to **Deploy from a branch**, **Branch** to `main`, **Folder** to `/(root)`, then **Save**.
6. Once published, the public link should look like `https://YOUR-USERNAME.github.io/kliptra-privacy-policy/`.
7. Test the link in a private/incognito window before pasting it into Google Play Console's Privacy policy URL field.

## Release verification

This policy describes behavior based on the developer-supplied Kliptra technical description, **not a source-code audit**. Before publishing, confirm that:

- AdMob and ML Kit SDK disclosures match the release build and Google Play Data safety declarations.
- Any AdMob consent form and `Settings → Legal → Privacy choices` are implemented and working in the relevant regions.
- Camera/microphone, local media processing, crash reports, exports and feedback really behave as stated.
- Market assets come from GitHub, fonts from Google Fonts and models from Hugging Face in the exact release being published.
- If any cloud storage, crash analytics, remote service or other data flow exists, update this policy before launch.
- The GitHub Pages URL is public without authentication; the privacy-policy link is also accessible in the app.
