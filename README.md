# Nimblexio Tools

## Publish on GitHub Pages
1. Extract this ZIP.
2. Create a **public** repository on GitHub (for example `nimblexio-tools`).
3. Upload `index.html` and `privacy.html` to the repository root.
4. Open **Settings → Pages**. Choose **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
5. Wait for the published URL shown in Pages.

## Ads
The ad areas are placeholders. Replace them with the actual banner code supplied by your approved ad network. Do not ask visitors to click ads.

## Notes
The theme switch toggles between light and dark mode and attempts to remember the choice in browser storage. QR generation needs an external QR service; PDF merge/split loads PDF-Lib from a CDN, so those features require an internet connection.

## Privacy and copy deterrence
The Privacy Policy is a starter template; update it for the services and laws that apply to your site. A small script disables right-click and selected shortcuts outside form fields, but it cannot prevent copying, screenshots, or access to public website source.


## QA status
- JavaScript syntax was checked after patching.
- Calculator and percentage input validation were improved.
- Unit converter now rejects invalid values and temperatures below absolute zero.
- PDF tool is a single-page extractor (not a full arbitrary page-range splitter).
- Browser end-to-end testing could not be completed in the current environment; please test the site in Chrome after deployment.
- QR generation needs internet access and uses QR Server. PDF merge/extraction needs internet access to load PDF-Lib from cdnjs.
- Ad areas are placeholders, not live ads.
