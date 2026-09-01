# FinkaMetals Email Signatures

HTML email signatures for the FinkaMetals team. One signature per person, and it renders in every mail client: Apple Mail (Mac and iPhone), Gmail, Outlook, and the rest.

The logo is hosted (referenced by URL, `assets/finka-logo.png`) rather than embedded in the file. That is what lets it show for recipients regardless of which client the sender used, including mail sent from Apple Mail, where an embedded image would otherwise be stripped on the way out.

Part of the FinkaMetals team assets hub: https://finkametals.github.io/

## Files per person

- `<name>-web.html`: the signature. Open it, select all, and paste into Gmail, Outlook, or iPhone Mail.
- `<name>-web.mailsignature`: the same signature as a macOS Mail file, for installing on Mac Apple Mail by replacing the signature file on disk.

The older `<name>.html` and `<name>.mailsignature` files are a previous SVG version, kept for reference but no longer used.

## Live signatures

- Carlos Francisco Fernandez (CEO): https://finkametals.github.io/email-signatures/carlos-francisco/carlos-francisco-web.html
- Jose Daniel Fernandez Navarro (Operations Lead): https://finkametals.github.io/email-signatures/jose-daniel/jose-daniel-web.html
- Santiago Herrera (Financial Lead): https://finkametals.github.io/email-signatures/santiago-herrera/santiago-herrera-web.html
- Daniela Ceballos Ruelas (Commercial Lead): https://finkametals.github.io/email-signatures/daniela-ceballos/daniela-ceballos-web.html
- Camila Arrien (Finance & Operations Associate): https://finkametals.github.io/email-signatures/camila-arrien/camila-arrien-web.html
- Carlos H. Fernandez Mazzi (Advisory Board Member): https://finkametals.github.io/email-signatures/carlos-h-fernandez/carlos-h-fernandez-web.html

The landing page at https://finkametals.github.io/email-signatures/ has each person's signature with a copy button and step-by-step install instructions for Apple Mail (Mac and iPhone), Gmail, and Outlook.

## Design spec

- Brand red `#e62d19`, dark gray `#414042`, Manrope (Helvetica/Arial fallback)
- Logo 78x126px, hosted at `assets/finka-logo.png`; contact text at 90% scale (name 12.6px, body 10.8px)
- Stacked name/title; vertical red divider; LinkedIn-only social row
- Dark-mode legibility via a white halo baked into the logo
