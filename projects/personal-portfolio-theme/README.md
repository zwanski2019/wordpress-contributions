# Personal Portfolio Theme

Custom WordPress theme built to showcase freelance projects.

## Goal
Create a performant, accessible portfolio theme that is easy for non-technical clients to maintain.

## Highlights
- Block-based templates with theme.json customization.
- Lazy-loaded hero images via `wp_get_attachment_image()`.
- Reusable `Portfolio Item` custom post type with taxonomy filters.

## Lessons learned
1. Define color palette in theme.json early so the editor palette stays consistent.
2. Use `add_theme_support( 'responsive-embeds' )` to keep YouTube blocks responsive.
3. Run Lighthouse audits in incognito mode to avoid cached assets while testing.

## Next steps
- Package the theme as a ZIP for upload.
- Write documentation on how to add new projects.
