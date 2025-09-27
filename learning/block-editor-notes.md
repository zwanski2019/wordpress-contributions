# WordPress Block Editor Study Notes

## Block Theme Essentials
- `theme.json` controls global styles; priority is presets < defaults < user.
- Template parts live in `parts/`; use semantic HTML to improve accessibility.
- Use `wp:template-part` tags to reference reusable sections.

## Performance Checklist
1. Enable full-page caching via hosting platform.
2. Use `wp_enqueue_script` with `in_footer` to defer non-critical JS.
3. Compress images with `webp` or AVIF and provide fallbacks.

## Useful CLI Commands
```bash
wp theme list
wp option get permalink_structure
wp plugin install query-monitor --activate
```

## Resources
- https://developer.wordpress.org/block-editor/reference-guides/
- https://web.dev/learn/design/
