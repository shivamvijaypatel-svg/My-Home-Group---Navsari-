# Village City 2 — My Home Group, Navsari

Editable source for the Village City 2 website exported on 19 October 2026.

## Files

- `public/index.html`: page content and layout.
- `public/styles.css`: desktop and mobile styling.
- `public/script.js`: navigation, gallery, image viewer and enquiry form.
- `public/assets/`: project illustrations and location map.
- `netlify.toml`: publishes the `public` directory; no build step or dependencies.

## Local preview

From the repository root run:

```sh
python3 -m http.server 8000 --directory public
```

Open http://localhost:8000. Edit the files in `public` and refresh the browser.

## Netlify

Connect this repository to the existing Netlify project, select the `main` branch, leave the build command blank and use `public` as the publish directory. The publish directory is also configured in `netlify.toml`. If deploying manually, upload the contents of `public`.

This import does not connect or change the existing Netlify deployment or domain settings.

## Enquiries

The form validates the visitor's details and opens a prepared WhatsApp message to the existing site office number. The visitor must press Send in WhatsApp. It does not save enquiries to a database or send them automatically.

The original ChatGPT-hosted site's database, private enquiry inbox and server APIs are not part of this static export. No credentials or customer records are included.

## Editing with Codex

Use this repository as the source for your Codex work. Ask for edits to the files in `public`, review the changes and commit them to GitHub. A Netlify deployment connected to the repository can then publish those changes according to its deployment settings.

## Verification

- Check JavaScript syntax with `node --check public/script.js`.
- Preview the mobile menu, gallery tabs, enlarged images and enquiry form.
- Preserve project disclaimers and verify factual changes with the developer.
