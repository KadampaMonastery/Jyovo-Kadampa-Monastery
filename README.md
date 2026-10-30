# Kadampa Monastery website starter

This is the first static website draft for Kadampa Monastery. It is designed for GitHub Pages and does not require a paid hosting plan.

## Included
- Responsive homepage for phones, tablets and desktops
- Supplied monastery logo and two supplied monastery photographs
- Language selector: English, Nepali, Tibetan and Simplified Chinese
- Sections for About, Events, Prayer, Dharma Library, Donations and Contact
- No invented event dates, bank details, contact information or payment links

## Before publishing
Please review and replace the placeholder text in `index.html` and translations in `script.js`:
1. Confirm the monastery's official name and approved description.
2. Add the official address, phone number, email and visiting arrangements.
3. Add only confirmed monthly event dates and times.
4. Add books/PDFs only when the monastery has permission to share them.
5. Confirm donation bank details and payment methods directly with the monastery.
6. Have a fluent speaker review Nepali, Tibetan and Chinese religious terminology before public launch.

The prayer and donation areas currently direct visitors to contact the monastery. This is intentional: GitHub Pages is static hosting and does not securely process form submissions or payments by itself.

## Publish using GitHub Pages (free)
1. Sign in to GitHub.
2. Click **New repository**.
3. Name it `kadampa-monastery`.
4. Choose **Public**, then create the repository.
5. On the repository page, choose **Add file → Upload files**.
6. Upload the contents of this folder (the `index.html`, `styles.css`, `script.js`, and `assets` folder). Upload the files themselves, not the ZIP archive.
7. Click **Commit changes**.
8. Open **Settings → Pages**.
9. Under **Build and deployment**, choose **Deploy from a branch**.
10. Choose branch **main** and folder **/(root)**, then click **Save**.
11. Wait a few minutes. GitHub will show the published address in Settings → Pages. It will usually look like `https://YOUR-USERNAME.github.io/kadampa-monastery/`.

## Updating the website
Edit `index.html` for page content and `script.js` for translated wording. Upload the changed files to the same repository and commit the changes. GitHub Pages republishes the site automatically.

## Important technical notes
- This starter uses Google Fonts when internet access is available; system fonts are used as fallbacks.
- The language selector translates the main interface and page copy. It is not a complete translation of future event listings, uploaded books or documents; those need translated content too.
- No analytics, tracking scripts, login system, database, payment gateway or prayer-request storage are included.
- Keep private information and payment credentials out of this public repository.
