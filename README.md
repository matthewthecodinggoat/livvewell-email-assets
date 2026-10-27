# Livvewell email assets

Public home for images used in Livvewell emails. Everything here ends up in customers' inboxes, so nothing private belongs in this repo.

## How images get into Klaviyo
1. Add the image under a folder for the campaign or flow (for example `rhythm/`) and push to `main`.
2. Import it into Klaviyo from its raw address:
   `https://raw.githubusercontent.com/matthewthecodinggoat/livvewell-email-assets/main/<folder>/<file>`
   (Klaviyo copies it to its own CDN, so the email never depends on GitHub.)
3. Use the Klaviyo CDN address in the template.

Keep images under about 200 KB (JPEG, 2x width) so emails load fast.
