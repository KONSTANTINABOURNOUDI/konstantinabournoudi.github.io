# konstantinabournoudi.github.io

Konstantina Bournoudi's link page, made for her NFC card: LinkedIn, email, and a contact card she can share with one tap.

Intended address: **https://konstantinabournoudi.github.io**

## What's here

| File | Purpose |
| --- | --- |
| `index.html` | The whole page. Styles, the animated signature, and the script are inline. |
| `konstantina-bournoudi.vcf` | Contact card behind "Save contact". Opens the native "add contact" sheet on iPhone and Android. |
| `assets/kb-signature.svg` | Her KB signature as a clean vector, free to reuse anywhere. |
| `assets/favicon.svg`, `assets/apple-touch-icon.png` | Browser tab and home-screen icons. |
| `assets/og.jpg` | Preview image shown when the link is shared in messages or social apps. |

Tap the signature on the page to watch it being written again.

## Preview locally

Open `index.html` in any browser. Everything works offline except the two web fonts, which fall back to Georgia and the system sans-serif.

## Publish on GitHub Pages

The address only works from the GitHub account `KONSTANTINABOURNOUDI` (it already exists).

1. Signed in as that account, create a **public** repository named `konstantinabournoudi.github.io`.
2. Upload the contents of this folder (not the folder itself) to the repository root, or push it with git.
3. Pages publishes it automatically within a minute or two at https://konstantinabournoudi.github.io.

## Editing

Links are the `<li>` rows inside `<ul class="links">` in `index.html`. If the email or LinkedIn changes, update `konstantina-bournoudi.vcf` too.
