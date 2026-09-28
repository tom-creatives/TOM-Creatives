# TOM Creatives

> Ideas. Engineered for Impact.

Landing page for **TOM Creatives**: AI, data, digital solutions and strategy for businesses, professionals, organisations and public institutions.

## Structure

```
tom-creatives/
├── index.html      # the whole site (HTML + CSS + tiny JS)
├── images/         # photos used in the Portfolio section
└── README.md
```

## Add your photos

Drop images into `images/` using these exact names (JPG, ideally under 300 KB, 4:3 ratio):

| File | Used for |
|------|----------|
| `livestock.jpg` | Livestock tile |
| `agriculture.jpg` | Agriculture tile |
| `data-analytics.jpg` | Data & Analytics tile |
| `healthcare.jpg` | Healthcare tile |
| `public-sector.jpg` | Public Sector tile |

Until a photo is added, its tile shows a brand-colour gradient with the label.

## Edit content

- **Services:** the `#services` section in `index.html`. Copy a `.card` block to add one.
- **Sectors:** the `.chip` items in `#sectors`.
- **Phone / WhatsApp:** search for `2348133809167` and update both links.
- **Colours:** CSS variables at the top of `<style>` (`--blue`, `--green`, `--navy`).

## Deploy (GitHub Pages)

1. Settings → Pages → Deploy from a branch → `main` / root → Save.
2. Site goes live at `https://<username>.github.io/tom-creatives/`.
3. Generate your QR code from that URL. Add a custom domain later under Settings → Pages so the QR code never changes.

## Roadmap

- [ ] Add real photos
- [ ] Portfolio / case studies page
- [ ] Training page (AI & data)
- [ ] Contact form
- [ ] Custom domain
- [ ] Migrate to Next.js + Tailwind (deploy on Vercel) with content in separate data files

## License

© TOM Creatives. All rights reserved.
