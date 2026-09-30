# Textball — Sit. Stay. Site. Simplified.

A text-first beginner HTML/CSS editor for classroom use.

## Files
- `index.html` — app and JavaScript
- `studio.css` — interface styling
- `textball-logo.png` — Textball logo
- `dog.png` — image used by the example page

## Deploy to GitHub Pages
Upload all four files to the same repository folder, then enable GitHub Pages from the branch root.

## What changed from HTMeatbaL
- No block editor mode. HTML, CSS, and JavaScript are real text editors.
- The left library inserts literal HTML/CSS code.
- Color Guide optionally matches source code colors to the library categories.
- Each HTML/CSS library item has a `?` explainer with a live visual example.
- HTML and CSS can be formatted/indented with the Format button; library inserts auto-format.
- Inspect mode lets a student click an element in the live preview and jump to the HTML tag that created it.
- CSS and JavaScript can still be turned on/off without deleting their code.
- Import/export, example project, mobile preview, undo/redo, and dark mode remain.

JavaScript inspection is intentionally not part of this version. Inspect is aimed at connecting rendered page elements back to their HTML source for CSS work.


## Leaving the page
Textball asks for confirmation before a back, refresh, or close action when the current project has unsaved changes. Modern browsers control the exact wording of this warning.
