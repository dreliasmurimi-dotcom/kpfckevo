# KPFC Builders Hardware website

This folder contains the complete static website, ready for GitHub Pages or standard static hosting.

## Website files
- `index.html` — homepage, business information and SEO metadata.
- `styles.css` — responsive layout and visual styling.
- `script.js` — product search, category filters, sorting, enquiry cart and WhatsApp enquiries.
- `products.js` — all 117 product records.
- `assets/` — all website images, split into three upload-friendly folders.
- `favicon.ico` and `robots.txt` — browser icon and crawler instructions.

## Image folders (GitHub upload-friendly)
The original image collection has been reorganized without removing images:

| Folder | Contents | Files |
|---|---|---:|
| `site/` | Logo, favicons and site/background images | 7 |
| `products/` | Numbered product images | 42 |
| `catalogue/` | Catalogue product images | 75 |

Each image folder contains fewer than 100 files, so you can upload the folders separately using GitHub's web uploader. Keep the folder names and structure unchanged; all image paths in `index.html`, `styles.css` and `products.js` have been updated to match.

## Upload to GitHub
1. Create or open your repository.
2. Upload the seven website files in this folder to the repository root.
3. Upload `site/`, `products/` and `catalogue/` separately, preserving the folder structure.
4. Enable GitHub Pages in the repository settings if you want GitHub to host the site.

## Before launch
1. Confirm the business phone (`+254 704 277 257`), WhatsApp number, email (`info@kpfc.co.ke`), location and opening hours.
2. Add the final canonical domain, absolute social-sharing image URL and `sitemap.xml` after the live domain is known.
3. Test the live site on desktop and mobile, and verify product availability and prices.

The site is a product catalogue and WhatsApp enquiry website. It does not currently include online payment processing or live stock management.
