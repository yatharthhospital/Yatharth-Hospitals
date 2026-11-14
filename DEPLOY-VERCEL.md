# GitHub → Vercel deployment

1. Upload the **contents** of `yatharth-web2` to the root of a GitHub repository. `index.html`, `style.css`, `assets/`, and `vercel.json` must be at the repository root.
2. In Vercel, import the repository. Use the **Other** framework preset, no build command, and root directory `.`.
3. Deploy. `vercel.json` enables clean URLs (e.g. `/about` instead of `/about.html`); existing `.html` links redirect to clean paths.
4. **Before launch:** replace the old Netlify base URL in `sitemap-netlify-example.xml` with your actual Vercel/custom domain, remove `.html` suffixes from sitemap paths, save as `sitemap.xml`, and add `Sitemap: https://YOUR-LIVE-DOMAIN/sitemap.xml` to `robots.txt`. Do not publish a sitemap with an incorrect domain.
5. Add canonical URLs only after the final primary domain has been chosen. Do not set canonical URLs to an unconfirmed domain.
6. Verify all factual hospital details, review accuracy, image/logo use rights and links before publication. This is an independent guide, not an official hospital website.

No design or content inside the Home patient reviews, Reviews directory cards, or location testimonial/review sections was rewritten. Hospital location image asset files and image `src` references were preserved.
