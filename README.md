# The Old Grog website concept

Created for Lumodus, November 2, 2026. A standalone responsive HTML/CSS/JavaScript concept, with no build or external script dependencies.

## Hosting
Upload the contents of `dist/` into a website directory. `index.html` and `assets/` must stay together. The downloadable website ZIP contains these files at its root, ready for a subdirectory such as `/old-grog/`. All local assets use relative paths. The site can also be opened locally by opening index.html.

## Included
- Responsive desktop and mobile layouts; collapsible mobile navigation and persistent call/menu buttons.
- All 75 published regular, Friday fish and kids menu entries, in HTML with category filtering and live search.
- Seven daily food and drink specials; default day uses America/Chicago, with accessible keyboard navigation.
- Authentic restaurant interior, exterior and fish fry photographs.
- History, contact links, directions, hours, search metadata and Restaurant structured data.
- Visible Lumodus concept attribution and original-site photo attribution.

## Source and verification
Facts, menu prices, descriptions, daily specials, photographs and hours were taken from:
- https://www.theoldgrog.com/
- https://www.theoldgrog.com/menu
- https://www.theoldgrog.com/menu?menu=friday-fish-1
- https://www.theoldgrog.com/menu?menu=kids-menu
- https://www.theoldgrog.com/specials
- https://www.theoldgrog.com/about-us

Published hours are daily 10am–10pm for bar and kitchen; Friday fish service is listed separately as 10am–9:30pm. Third-party listings differ, so verify hours with the owner before adopting the design as the official website. Menu pricing is a published snapshot, not confirmation of current availability. The original to-go fee notation is ambiguous, so no amount is asserted in this concept.

Photographs remain the property of their respective owners. This is an independently prepared demonstration for review. Confirm the restaurant's approval and photo permissions before official commercial adoption. No testimonials, review counts, awards, booking system or online ordering have been invented.

## Local editing
Edit `template.html` for layout, styles and interactions, and `build.py` for menu data. Run `python3 build.py` to regenerate `dist/index.html`. The website ZIP only needs editing directly if source tooling is not used.

## Validation
Desktop browser rendering and a 390px embedded mobile viewport inspected. Friday special switch, Friday menu filter, cross-category search, empty search state and mobile navigation open/close verified in browser. Assets are local. Phone, email and directions use direct links; no forms or backend are included.

## Logo update
The header, footer and favicon use a shirt-inspired crowned-eagle and blackletter logo recreation. Exact wording: “The Old Grog” and “Menasha, WI.” The “Block From The Fox” line is deliberately omitted from the logo per request, while the existing website copy is retained. The bar photograph is unchanged. The supplied shirt photograph is the reference; the asset is a generated recreation rather than an original vector master.

## Horizontal white logo revision
The active header and footer logo now uses a transparent PNG: white crowned eagle on the left and white blackletter “The Old Grog” on the right. No circular border, location text, or slogan is included. The previous gold graphic is retained as an unused prior asset. The bar photo and existing website copy remain unchanged.
