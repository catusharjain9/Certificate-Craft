# Certificate Craft

Certificate Craft is a standalone, browser-based workspace for preparing and organizing financial certificate drafts. The complete application source is in `index.html`; it does not embed or depend on Vercel or another hosted application.

## Run the website

- **Open locally:** download or clone this repository and open `index.html` in a modern browser.
- **Host from GitHub:** enable GitHub Pages in the repository settings and select the `main` branch with the root folder as the publishing source. The app is static and does not require a build step or server.
- **Use the live source:** [index.html](https://github.com/catusharjain9/Certificate-Craft/blob/main/index.html)

## Current features

- Dashboard with saved certificate counts and recent records
- Certificate drafting form with a live A4 print preview
- Indian rupee formatting and totals for assets, liabilities and net worth
- Reusable firm and signatory profiles
- Certificate starting points for net worth, turnover, income, balance confirmation and general financial certificates
- Draft/final status, search, edit and save
- Browser print dialog for printing or saving a PDF
- JSON backup and restore for locally stored records
- Responsive layout for desktop and mobile screens

## Data and privacy

The app stores records in the browser's local storage on the current device. It has no login, server database, cloud synchronization or multi-user access. Export backups regularly. Clearing browser storage may permanently remove locally saved records.

## Important limitations

This is a standalone drafting aid, not a compliance or legal validation system. Review every certificate's wording, calculations, source documents and applicable professional requirements before issuing it. The current version uses a general financial certificate structure; it does not yet provide verified, certificate-specific prescribed formats, true DOCX export, firm letterhead rendering, robust multi-page annexures, or cloud storage.

## Repository structure

```
.
├── index.html   # Complete standalone website (HTML, CSS and JavaScript)
└── README.md    # Project documentation
```
