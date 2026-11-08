# Summit Agility Website

This repository contains the public homepage and brand assets for [Summit Agility](https://www.summit-agility.com/).

## Website purpose

Summit Agility helps owner-led small businesses build the systems, processes, and teams they need to grow beyond the owner.

The homepage focuses on:

- Small business operations consulting
- Growth and operations assessments
- Standard operating procedures (SOPs)
- Hiring and delegation systems
- Business process improvement
- Microsoft 365 business systems
- Fractional operations advisory support

## Main files

| File | Purpose |
| --- | --- |
| `index.html` | Main Summit Agility homepage |
| `Summit Agility Color.css` | Official Summit Agility color variables and color classes |
| `Summit Agility Fonts.css` | Official Summit Agility typography system |
| `ProtectProve.jpg` | Homepage banner and social sharing image |
| `SAlogo.png` | Summit Agility logo |
| `SABWlogo.ico` | Browser favicon |
| `BannerSA.png` | Video poster image |
| `PortfolioVideo.mp4` | Summit Agility introduction video |
| `vCard QR Code.png` | QR code for the Summit Agility contact card |
| `Privacy Policy.html` | Website privacy policy |

The homepage also references credential badge images already stored in the repository.

## Brand system

### Colors

The website loads colors from `Summit Agility Color.css`:

- Primary charcoal: `#1A1A1A`
- Secondary gray: `#444444`
- Accent rust: `#C94F2D`
- Body text: `#111111`
- Background: `#FFFFFF`

### Fonts

The website loads typography from `Summit Agility Fonts.css`:

- Molle for the Summit Agility title treatment
- League Gothic for primary headings and subtitles
- Tw Cen MT with web-safe fallbacks for body text

Google Fonts provides Molle and League Gothic in the website header. Tw Cen MT displays when available on the visitor's device and otherwise uses the fallbacks defined in the font stylesheet.

## Updating the site with GitHub Desktop

1. Put the updated files inside the local `SA_Assets` repository folder.
2. Open GitHub Desktop.
3. Select the `SA_Assets` repository.
4. Review the files listed under **Changes**.
5. Confirm that the intended files are checked.
6. Enter a commit summary, such as:

   `Update homepage and add Summit Agility brand styles`

7. Select **Commit to main**.
8. Select **Push origin**.
9. Open the repository on GitHub.com and confirm that the files appear in the repository.
10. Open the live Summit Agility website and refresh the page.

## Recommended first commit

The first homepage update should include these four files in one commit:

- `index.html`
- `README.md`
- `Summit Agility Color.css`
- `Summit Agility Fonts.css`

Suggested commit message:

`Update homepage and add Summit Agility brand styles`

## Important notes

- File names are case-sensitive on GitHub Pages.
- Do not rename image, video, CSS, or privacy-policy files unless the matching references in `index.html` are also updated.
- Spaces in file names are supported, but keeping the names unchanged prevents broken links.
- The Microsoft consultation form currently loaded by the homepage is `https://forms.office.com/r/Lz3TP0R37S`.
- After pushing, use a hard refresh if the old page remains visible: `Ctrl + F5` on Windows.

## Local preview

To preview the website before committing:

1. Open the local `SA_Assets` folder.
2. Double-click `index.html`.
3. Confirm that the page opens in a browser.
4. Check the banner, logo, video, QR code, credential badges, consultation form, and Privacy Policy link.

Some browser security settings may limit an embedded Microsoft Form during a local preview. The form should be checked again after the page is published.

## Ownership

Copyright 2026 Summit Agility LLC. All rights reserved.
