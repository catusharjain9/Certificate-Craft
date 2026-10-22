# Certificate Craft — Web Workspace

Certificate Craft is a browser-based workspace for preparing and reviewing CA certificate drafts.

## Open the application

- Live app: https://certificate-craft-web.vercel.app
- Repository entry point: [index.html](./index.html)

The repository's `index.html` is a lightweight web entry point that embeds the currently hosted application. The application itself is deployed separately on Vercel. This repository does **not yet contain the complete standalone application source code**.

## Current functionality

The deployed first version includes a dashboard, certificate templates, certificate data form with live A4 preview, Indian currency formatting and net-worth calculation, firm and signing-CA profiles, local draft management, browser backup/restore, and print/PDF output.

## Known limitations

- The DOC download is currently a Word-compatible `.doc` file, not a true `.docx`.
- Drafts and profiles are stored in the current browser's local storage; there is no cloud database, authentication, or multi-user synchronization.
- Letterhead integration, robust multi-page annexures, pagination, and export formatting need further testing and improvement.
- Sample certificate wording must be reviewed and approved for the relevant engagement before professional use.

## Data and privacy

The local browser workspace does not automatically sync between devices. Avoid using sensitive client information on shared devices. Do not commit client data, generated certificates, credentials, or backups to this repository.
