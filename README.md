# JHOELSOFT — Android Pop-up Ads Cleaner

Static GitHub Pages build of JHOELSOFT.

## Deploy

1. Create a GitHub repository (for example `jhoelsoft`).
2. Upload the contents of this folder to the repository root, including `.github/workflows/deploy.yml` and `.nojekyll`.
3. Use the `main` branch.
4. Open **Settings → Pages** and set **Source** to **GitHub Actions**.
5. Push/commit the files. The included workflow deploys the site automatically.
6. Open the published HTTPS URL directly in Chrome on the USB-host Android phone.

GitHub Pages should publish the root `index.html` as the site entry page.

## USB / ADB requirements

- Use Chrome/Chromium on the host Android phone.
- Open the published page directly as a top-level HTTPS page; do not use an app preview or iframe.
- Enable Developer Options → USB debugging on the target Android phone.
- Keep the target phone unlocked and accept the Android RSA “Allow USB debugging?” prompt.
- Use a USB data cable/OTG connection, not a charge-only cable.

WebUSB access is browser/device dependent. Firefox/Safari do not provide the direct WebUSB path used by this page.

## Safety

The scanner uses heuristic signals and does not prove that an app is malicious. Review each result before uninstalling. Uninstall actions are explicit and intended for the connected target device.
