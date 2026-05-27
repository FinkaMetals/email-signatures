# FinkaMetals email signatures

Hosted email signatures for the FinkaMetals team.

## Live URL

Once GitHub Pages is enabled, signatures are served at:

```
https://finkametals.github.io/email-signatures/signatures/{person}.html
```

## Structure

```
email-signatures/
├── README.md
├── assets/
│   ├── finkametals-logo-color.png   Light mode logo
│   ├── finkametals-logo-dark.png    Dark mode logo (red preserved, FINKA white)
│   ├── finkametals-logo-white.png   Pure white monochrome (alternate use)
│   ├── social-linkedin.png          LinkedIn icon
│   └── social-x.png                 X icon
└── signatures/
    └── carlos-francisco.html        One file per team member
```

## Adding a new signature

1. Copy `signatures/carlos-francisco.html` to `signatures/{name}.html`.
2. Replace name, title, email, phone, address, LinkedIn URL, X URL.
3. Commit and push. GitHub Pages auto-deploys.

## Design notes

- Layout: V4 stacked logo on the left, vertical red separator, contact details on the right.
- Font stack: Manrope first (brand), falls back to Helvetica then Arial then system sans-serif. Most recipients see the fallback, since email clients don't load Google Fonts.
- Colors: red `#e62d19` for accents and logo elements, dark gray `#414042` for body text.
- Dark mode: Apple Mail swaps the logo automatically via a `prefers-color-scheme` media query. Gmail strips the style block and shows the color logo on dark backgrounds (functional, no regression).

## Installing the signature

### Apple Mail (macOS)

The signature editor in macOS Mail strips HTML when pasted directly. The workaround:

1. Open the signature file in Safari (e.g. `https://finkametals.github.io/email-signatures/signatures/carlos.html`).
2. Select all (Cmd+A) and copy (Cmd+C).
3. Mail → Settings → Signatures. Create a new signature placeholder (any name).
4. Paste (Cmd+V) into the signature editor.
5. Quit Mail completely.
6. In Finder, open `~/Library/Mail/V10/MailData/Signatures/` (the V number may vary).
7. Find the `.mailsignature` file matching the signature you just created (sort by date, newest is yours).
8. Open it in TextEdit. Replace the body with the contents of the `.html` file (keeping the headers at the top).
9. Right-click the file → Get Info → Locked. This prevents Mail from rewriting it on next launch.
10. Reopen Mail. The signature now renders correctly.

### Apple Mail (iOS)

1. Open the signature file in Safari on iOS.
2. Long press → Select All → Copy.
3. Settings → Mail → Signature.
4. Paste. Done.

iOS Mail handles this more smoothly than macOS.

### Gmail (web)

1. Open the signature file in any browser.
2. Select all (Ctrl/Cmd+A) and copy.
3. Gmail → Settings (gear) → See all settings → General → Signature.
4. Create a new signature, paste the content.
5. Set defaults (which signature appears for new mail and replies).
6. Save changes.
