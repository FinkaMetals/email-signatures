# FinkaMetals Email Signatures

Self-contained HTML email signatures for the FinkaMetals team.

The logo and LinkedIn icon are embedded directly in each file (SVG and PNG as data URLs), so the signatures depend on no external image hosting. They render identically offline, will not break if a link or server goes down, and survive being pasted into mobile mail apps. This replaces the earlier hosted-image version of this repo.

## Live signatures

- Carlos Francisco Fernandez (CEO) — https://finkametals.github.io/email-signatures/carlos-francisco/carlos-francisco.html
- Jose Daniel Fernandez Navarro (Operations Lead) — https://finkametals.github.io/email-signatures/jose-daniel/jose-daniel.html
- Santiago Herrera (Financial Lead) — https://finkametals.github.io/email-signatures/santiago-herrera/santiago-herrera.html
- Daniela Ceballos Ruelas (Commercial Lead) — https://finkametals.github.io/email-signatures/daniela-ceballos/daniela-ceballos.html
- Camila Arrien (Senior Finance & Operations Associate) — https://finkametals.github.io/email-signatures/camila-arrien/camila-arrien.html

## Files

Each person has a folder with two files:

| File | Use it for |
|------|------------|
| `<name>.mailsignature` | **Mac Apple Mail** — installed by editing the signature file directly |
| `<name>.html` | **iPhone Apple Mail, Gmail, Outlook**, and everything else — installed by copy-paste |

## Design spec

- Brand red `#e62d19`, dark gray `#414042`, Manrope (Helvetica/Arial fallback)
- Logo 78x126px; contact text at 90% scale (name 12.6px, body 10.8px)
- Stacked name/title; vertical red divider; LinkedIn-only social row
- Dark-mode legibility via a white halo on the FINKA wordmark (classic SVG stroke attributes, no `rgba`) plus a `prefers-color-scheme` fill swap where the client honors it

## Install instructions

Per-client step-by-step instructions (Mac Apple Mail, iPhone Apple Mail, Gmail, Outlook) to be added here.
