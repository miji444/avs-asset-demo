# AVS asset tags: demo and label generator

- **Demo asset page** (sample data): `index.html`. Scan a tag on the home page, or open `#tags` to print demo tags.
- **Login demo**: `secure/`. Scan → sign in → asset record. Demo logins: `client`/`client123` (own company: sees it), `staff`/`avs2026` (AVS: sees all), `other`/`other123` (other company: no access). Demo only: in the real version the AVS server checks the password before sending any data.
- **Admin demo**: `admin/` (password `demo`). Groups (clusters) with one Cluster Engineer and Technician each; sites belong to a group and can override; open a demo asset page to see the change. Demo changes are kept in the browser only.
- **Demo asset page for any tag**: `asset/`. Tags made with the label generator's “Demo page” option open here: real asset ID and a link to its real Synchroteam record, with sample service data.
- **Label generator**: `label-generator/`. Load the Synchroteam equipment export (Excel/CSV), choose a design, and download print-ready PDFs with a unique QR code per asset. Files are processed in the browser and never uploaded.

Hosted with GitHub Pages from the `main` branch.
