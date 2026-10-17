# README artwork

## Dashboard illustration

The README uses `dashboard-demo.png`, rendered from `dashboard-demo.html`.
It is an original static HTML/CSS illustration of a smart-home dashboard, not
a capture of a connected Onyx Liquid installation.

- All room names, devices, temperatures, weather, lighting states, scene names,
  and media are fictional. Do not substitute private household information.
- The icon is the existing public add-on icon at `addons/navet/icon.png`.
  The control icons, abstract album artwork, and background are drawn in the
  HTML/CSS source; no household photographs or external assets are used.
- The render is labelled **Illustrative render · Fictional data**. Keep that
  label, the README caption, and the descriptive Markdown alt text.
- The source has no scripts, application connections, external fonts, or
  remote resources. It uses system fonts and the local add-on icon.

To export, serve this repository over loopback, open
`/docs/readme/dashboard-demo.html` in Chromium, wait for fonts and the icon
to load, and capture the `.artwork` element at a 1200 CSS pixel viewport
width and 1.5 device scale. Save the result as `dashboard-demo.png`.
The source also adapts to a 390 CSS pixel viewport for visual review.

Embed the saved PNG using native Markdown image syntax and a relative path.
Browser phone-width checks do not establish native GitHub Mobile acceptance.

## Earlier brochure compositions

The earlier artwork below remains available as editable source and exports.
The current README uses the dashboard illustration above.

- `poster.html` is the editable cover composition.
- `hero.png` is exported at 900 CSS pixels wide; `hero-mobile.png` at 380 CSS pixels wide.
- Where present, `workflow.html` is the editable workflow panel, exported at the same two widths.
- Exports use a 1.5 device scale. Wait for document fonts and images to finish loading before capture.
- Use Chromium to capture the `.poster` or `.workflow` element. Only the saved images are embedded in the README.

The compositions retain product-specific colors, artwork, and existing attribution.

Fonts are loaded from Google Fonts in the editable source; the exports contain no runtime font or network dependency.

## Visual chapters

The previous README used a cover, a showcase, three illustrated feature chapters,
a workflow, and an ending panel.

- `showcase.html`, `feature-1.html`, `feature-2.html`, `feature-3.html`, and `next.html` are editable compositions; the matching PNGs are exported at 900 CSS pixels wide and a 1.5 device scale.
- Wait for document fonts and embedded images, then capture the `.chapter` element with Chromium. The exported PNGs have no network or font dependency.
- Illustrations describe the documented experience. They are editorial compositions, not independent evidence of runtime acceptance or release availability.
- Illustrated experiences use the documented product story and existing project artwork.
- Embed saved PNGs using native Markdown image syntax and relative repository paths. GitHub Mobile has limitations with HTML `picture` / `source` markup; desktop viewport tests do not verify the native mobile app.

Existing artwork and photography retain their original provenance and licensing. Product status is carried in each visual chapter; current behavior and availability remain in the maintained source and linked product guides.
