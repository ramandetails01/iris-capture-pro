# Iris Capture Pro — starter website

A static GitHub Pages setup assistant for Mantra MIS100V2 on Windows 11.

## Publish with GitHub Pages
1. Create a GitHub repository named `iris-capture-pro`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site.

## Important limitations
This starter site is a setup guide only. A normal GitHub Pages website cannot inspect Windows services or communicate with a locally installed RD Service by itself. It does not extract, display, save, or download raw iris images or Aadhaar PID data.

For Aadhaar Iris authentication, use an authorised AUA/KUA or approved service-provider application and the vendor-supported Mantra RD integration. Do not bypass RD Service protections or store residents' biometric data.
