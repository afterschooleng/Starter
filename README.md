# After School Engineering

## Publish on GitHub Pages
1. Create a new public GitHub repository, such as `after-school-engineering`.
2. Unzip this package.
3. Upload `index.html`, `assets`, `.nojekyll`, and this README to the repository root.
4. Commit the files.
5. Open **Settings → Pages**.
6. Choose **Deploy from a branch**, then **main** and **/(root)**.
7. Save. Your URL will be `https://YOUR-USERNAME.github.io/after-school-engineering/`.

## Edit before publishing
Search `index.html` for:
- `hello@afterschoolengineering.org`
- `Coming soon`
- `Neighborhood venue`
- `10:00 AM–12:00 PM`
- `5–12`

## Countdown
Near the bottom of `index.html`, replace `const eventDate=null` with a date such as:
`const eventDate=new Date('2026-09-19T10:00:00')`

## Registration
The starter form opens an email. Replace it with a Google Form link or an email-list provider when ready.
