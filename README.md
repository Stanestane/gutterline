# Gutterline

A comic page layout editor that runs in the browser. Start from a standard page layout, drag the borders between panels to reshape them, and drop images into the panels.

Open `index.html` in any modern browser. There is nothing to install or build. Everything is in that one file; it only loads two fonts from Google Fonts and falls back to system fonts when offline.

## What it does

- Starting layouts: Tiers, Six, Nine, Splash, Action, Manga, Wide and Single.
- Drag a gutter to move it. Drag near either end to angle it, and double-click it to straighten it. Gutters snap to common positions; hold Alt to turn snapping off.
- Split a panel side by side or top and bottom, or delete it and let its neighbour take the space.
- Overlapping panels: lift a panel out of the grid so it can be enlarged over its neighbours, or add a new one anywhere. Drag its edge to move it and its corners to reshape it. A paper-coloured outline with a border along the cut separates it from the panels underneath.
- Images: double-click a panel or drop image files onto the page. Drag inside a panel to pan and scroll to zoom. Images can be larger than the panel and of any aspect ratio; anything outside the frame is hidden.
- Page settings: US comic, A4, manga B6, landscape A4 and square formats at 300 dpi, plus gutter width, outer margin, border weight, border colour and paper colour.
- Export the page as a full-resolution PNG. Save and open projects as `.json` files with the images embedded. Undo and redo, and an autosave in the browser.

## Controls

| Where | Action |
| --- | --- |
| Gutter | Drag to move, drag near an end to angle, double-click to straighten |
| Panel | Click to select, double-click or drop a file to load an image |
| Overlapping panel | Drag the edge to move, drag a corner to reshape |
| Image | Drag to pan, scroll to zoom |
| Keys | Ctrl+Z undo, Ctrl+Shift+Z redo, Delete removes the image, Esc deselects |
