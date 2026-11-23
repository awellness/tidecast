# Tidecast Media (front end)

Screens only. No data, keys or passwords live here: every call goes to each clinic's Apps Script web app, and each user signs in with their Tidecast login.

- `jersey/` — Jersey Wellness Clinic. Set `window.TIDECAST_API_URL` in `jersey/index.html` to the clinic's Apps Script `/exec` URL.
- New clinic: copy the `jersey/` folder, rename it, change the URL, the name in `manifest.json`, and the icons if needed.

After editing Index.html in Apps Script, copy it here too and add back the 9 head lines at the top of `<head>` (API URL, manifest, icons, meta tags).
