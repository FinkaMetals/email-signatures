# FinkaMetals Email Signatures

Self-contained HTML email signatures for the FinkaMetals team.

The logo and LinkedIn icon are embedded directly in each file (SVG and PNG as data URLs), so the signatures do not depend on any external image hosting. They render the same offline, will not break if a link or server goes down, and survive being pasted into mobile mail apps.

## Contents

Each person has a folder with two files:

| File | Use it for |
|------|------------|
| `<name>.mailsignature` | **Mac Apple Mail** — installed by directly editing the signature file |
| `<name>.html` | **iPhone Apple Mail, Gmail, Outlook**, and everything else — installed by copy-paste |

| Person | Title |
|--------|-------|
| Carlos Francisco Fernandez | CEO |
| Jose Daniel Fernandez Navarro | Operations Lead |
| Santiago Herrera | Financial Lead |
| Daniela Ceballos Ruelas | Commercial Lead |
| Camila Arrien | Senior Finance & Operations Associate |

## Design spec (for future edits)

- Brand red `#e62d19`, dark gray `#414042`, Manrope (Helvetica/Arial fallback)
- Logo 78x126px; contact text at 90% scale (name 12.6px, body 10.8px)
- Stacked name/title; vertical red divider; LinkedIn-only social row
- Dark-mode legibility via a white halo on the FINKA wordmark (classic SVG stroke attributes, no `rgba`) plus a `prefers-color-scheme` fill swap when the client honors it

## Install instructions

Step-by-step instructions per client (Mac Apple Mail, iPhone Apple Mail, Gmail, Outlook) to be added here.
