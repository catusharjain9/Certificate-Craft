# Certificate Craft

A local Windows application for preparing CA certificates with a page preview, firm-specific letterhead profiles, multiple CA signatories, editable asset/fund annexures, INR totals, foreign-currency conversion, DOCX export and browser print-to-PDF.

## Run locally

1. Install Python 3.10 or later.
2. Extract the supplied `Certificate_Craft_Ready_Windows.zip` package.
3. Run `run_windows.bat` from the extracted folder.
4. Keep the terminal open and use `http://127.0.0.1:5055`.

The app stores data in `data.json` locally. Back up the application folder. Review every certificate before issue; this software does not generate UDINs or authenticate signatures.

## Project status

The downloadable Windows package was syntax-checked and its DOCX ZIP/XML structure and calculation formatting were tested. Exact visual matching and pagination should still be checked in the target Word/browser environment before office use.

## Data and privacy

Do not commit client data, generated certificates, or `data.json` to this repository. The supplied reference certificate PDF is not included in the repository.