# Bolt's Journal - The Little Prince Performance

## 2025-01-24 - Improving FCP with font-display: swap
**Learning:** In Tilda-exported static sites, custom fonts are often declared across multiple CSS files and even inlined in the HTML. Without `font-display: swap`, the browser waits for these fonts to download before rendering text, causing a Flash of Invisible Text (FOIT) and delaying First Contentful Paint (FCP).
**Action:** Always check all CSS files and the main HTML for `@font-face` declarations and ensure they use `font-display: swap` to allow immediate text rendering with system fallbacks.
