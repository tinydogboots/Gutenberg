# Gutenberg

A book mockup renderer that runs in the browser. Design a book, light it, and export high-resolution PNGs.
Everything lives in one `index.html` (three.js from a CDN); open it in a browser, no build step.

- **Book:** hardcover or paperback, trim-size presets or custom size in mm, page count and paper caliper (spine width is calculated).
- **Case:** board thickness, overhang, rounded or square spine, hinge groove, headbands, ribbon marker.
- **Open:** opening angle from 0 to 180°, which page it falls open at, and the curve of the pages.
- **Cover art:** front, spine and back images, or one full cover spread with bleed. A matching SVG print template is generated from the current measurements.
- **Typography:** title, subtitle, author, spine lettering, back-cover text and a barcode, set in 10 typefaces.
- **Finish:** matte, gloss, soft-touch, uncoated, linen, book cloth or leather. Lettering can be ink, gold, silver or copper foil, or spot UV.
- **Pages:** paper colour, plain, sprayed or gilded edges, placeholder text or your own spread image, and endpapers.
- **Light and camera:** sun height and direction, ambient light, shadow softness and strength, exposure, focal length, and preset views.
- **Styles:** realistic rendering, 1-bit dithered bitmap, or line drawing.
- **Export:** PNG from 2K up to 8K in several aspect ratios, with a transparent or coloured background. Designs save and open as `.json` files, pictures included.
