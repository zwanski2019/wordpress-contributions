# Performance Review Template

Use this checklist before shipping a WordPress feature.

## PageSpeed Targets
- Largest Contentful Paint (LCP) < 2.5s
- Cumulative Layout Shift (CLS) < 0.1
- First Input Delay (FID) < 100ms

## Audit Steps
- Run `wp option get permalink_structure` to ensure pretty permalinks are enabled.
- Check database queries with Query Monitor; flag anything over 100ms.
- Validate `rel=preload` links for fonts to prevent layout jumps.

## Notes
- Document hosting environment and PHP version.
- Record baseline metrics in `/reports/performance-<date>.md`.
