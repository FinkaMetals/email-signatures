# FinkaMetals Email Signatures

Self-contained HTML email signatures for the FinkaMetals team. The logo and LinkedIn icon are embedded directly in each file as data URLs, so the signatures depend on no external image hosting: they render offline, will not break if a server goes down, and survive being pasted into mobile mail apps.

## Two versions per person

Email clients disagree on image formats, so each person has two signature versions that differ only in the logo:

| Version | Logo format | Use it for |
|---------|-------------|------------|
| `<name>.html` + `<name>.mailsignature` | SVG (vector, sharp, dark-mode adaptive) | **Apple Mail** on Mac and iPhone |
| `<name>-web.html` | PNG (baked-in white halo, universal) | **Gmail, Outlook**, and every other client |

Gmail (and most non-Apple clients) cannot render SVG images, so the Apple version's logo shows as a broken image there. The `-web.html` PNG version renders everywhere and stays legible on dark backgrounds via a halo baked into the pixels. On Mac Apple Mail the `.mailsignature` file is installed by editing the signature file on disk; everything else is copy-paste.

## Live signatures

- Carlos Francisco Fernandez (CEO) — https://finkametals.github.io/email-signatures/carlos-francisco/carlos-francisco.html
- Jose Daniel Fernandez Navarro (Operations Lead) — https://finkametals.github.io/email-signatures/jose-daniel/jose-daniel.html
- Santiago Herrera (Financial Lead) — https://finkametals.github.io/email-signatures/santiago-herrera/santiago-herrera.html
- Daniela Ceballos Ruelas (Commercial Lead) — https://finkametals.github.io/email-signatures/daniela-ceballos/daniela-ceballos.html
- Camila Arrien (Finance & Operations Associate) — https://finkametals.github.io/email-signatures/camila-arrien/camila-arrien.html

The landing page at https://finkametals.github.io/email-signatures/ has both versions per person with copy buttons and full install instructions.

## Design spec

- Brand red `#e62d19`, dark gray `#414042`, Manrope (Helvetica/Arial fallback)
- Logo 78x126px; contact text at 90% scale (name 12.6px, body 10.8px)
- Stacked name/title; vertical red divider; LinkedIn-only social row
- Dark-mode legibility via a white halo on the FINKA wordmark: SVG version uses classic stroke attributes plus a `prefers-color-scheme` fill swap where honored; PNG version has the halo baked into the pixels
