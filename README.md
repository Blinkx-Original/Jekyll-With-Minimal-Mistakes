# Jekyll SEO Starter — Minimal Mistakes Edition (v2)

This starter bundles **Minimal Mistakes** via `remote_theme` + SEO (`jekyll-seo-tag`, `jekyll-sitemap`) and a custom **landing-by-blocks** system for “fake e‑commerce”/lead pages.

## Quick start
1. Edit `_config.yml` (`url`, `baseurl`, skin).
2. Keep homepage at `index.md` (layout `splash`) or switch to `layout: landing` + `blocks:`.
3. Posts go in `_posts/` and list at `/blog/`.
4. Landing pages: create Markdown with `layout: landing` and compose blocks from Front Matter.
5. Push to GitHub → Settings → Pages → build from `main` (root). Add your custom domain & HTTPS.

## Blocks
Located under `_includes/blocks/`: `hero`, `features-grid`, `pricing-table`, `cta`, `faq`.
Render order is defined by a `blocks:` array in the page Front Matter.

## Customize
- CSS overrides in `assets/css/_overrides.scss` (loaded after the theme).
- Navigation in `_data/navigation.yml`.
- Search at `/search/`.
