# Apex Demolition & Excavation

Marketing site for **Apex Demolition & Excavation** — Building the future. Clearing the way.

A pure static site, no build step. Just HTML, CSS, fonts from Google, and brand assets.

## Local preview

```powershell
python -m http.server 8765 --directory .
# then open http://localhost:8765
```

## Deploy

Hosted on **Vercel**. Push to `main` → auto-deploy. Caching headers for static assets are configured in [vercel.json](vercel.json).

## Project structure

| File | Purpose |
| --- | --- |
| `index.html` | Page structure + mailto-based quote-form JS |
| `styles.css` | All styling (industrial-brutalist, black + orange) |
| `apex-logo-mark.png` | Header wordmark (no phone number) |
| `apex-logo.png` | Full logo, transparent background |
| `apex-logo-source.pdf` | Original logo banner |
| `vercel.json` | Cache + security headers |

## Quote form

Submitting the quote form opens the user's default email client with a prefilled message to **iearthworx@outlook.com**. No backend required.

To upgrade to a no-redirect submission later, point the `<form>` `action` at Formspree, Web3Forms, or Vercel Forms.

## Contact

- **Phone:** 0499 921 002
- **Email:** iearthworx@outlook.com
- **Instagram:** [@apex_demos](https://www.instagram.com/apex_demos/)
