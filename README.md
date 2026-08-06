# TableApp - Wedding Table Arrangement Tool

**TableApp** is an interactive, single-page HTML application for planning and managing wedding table arrangements. It runs entirely in the browser — no server, no installation, no dependencies.

**[Try it live on GitHub Pages](https://marani-rd.github.io/TableApp/TableApp.html)**

---

## Features

### Table Types
- **Round tables** — 6, 8, 10, or 12 seats with configurable layout
- **Straight tables** — 4, 6, 8, or 10 seats with short-side seating options (both, one, none)
- **Arc tables** — curved seating with adjustable curvature sectors
- **Seating blocks** — rows and columns of seats with configurable spacing (side-by-side, compact, normal, expanded)

### Guest Management
- Full guest list with name, surname, category (Sposo, Sposa, Testimone, Invitato), and grouping fields
- **Friend group**, **relative group**, and **interest group** for smart auto-assignment
- Notes field for seating constraints ("vicino a...", "lontano da...")
- Excel import/export via drag & drop or file picker
- Drag & drop between chairs to swap guests
- Reserved numbering: seats 1-2 for bride/groom, 3-4 for witnesses (when assigned)

### Auto-Assign Seats
- Prioritizes bride and groom (bride always to the left of groom)
- Places witnesses flanking the couple
- Groups guests by matching attributes (friend/relative/interest groups)
- Respects "near" and "far" constraints from notes
- Spatial renumbering after assignment

### Furniture & Decorations
- Columns (configurable diameter 20-120 cm)
- Buffet table, DJ booth (with vinyl record icon), Stage lights
- Plants, Speakers, Walls, Fountains (with water animation)
- Signs (light gray with dark red text, word-wrap enabled)
- Floral arches (transparent background, purple label)
- Musicians (detailed violin icon)
- All scalable furniture can be freely stretched; labels stay proportional

### Background Image
- Upload any image as a floor plan or venue photo
- Adjustable opacity (20%, 40%, 60%, 80%, 100%)
- Rotation with 15-degree snap
- Lock to prevent accidental changes
- Reset to original size and position
- Context menu with full controls

### Canvas & Interaction
- Pan and zoom with mouse wheel or pinch gestures
- Snap-to-grid with configurable spacing
- Rulers with measurement display
- Lock individual tables or furniture to prevent accidental moves
- Right-click context menus (long-press on mobile)
- Undo/Redo support

### Export & Print
- Export canvas as high-resolution PNG image
- Print-optimized PDF generation with guest list summary
- Save/Load projects as JSON files

### Mobile Support
- Full touch support with gesture recognition
- Responsive sidebar with collapsible accordion sections
- Smart touch drag: vertical swipe scrolls the sidebar, horizontal swipe initiates drag & drop
- Long-press for context menus
- Compact person list with toggleable detail columns

---

## Getting Started

1. Open `TableApp.html` in any modern browser (Chrome, Firefox, Edge, Safari)
2. Drag tables from the left sidebar onto the canvas
3. Add guests in the person list (bottom panel) or import from Excel
4. Use "Assegna Posti" to auto-assign seats, or drag & drop manually
5. Save your project as JSON for later editing

No installation or server required. All data stays in your browser.

---

## Technology

- Pure HTML + CSS + JavaScript (single file, ~4500 lines)
- [Fabric.js 5.3.0](http://fabricjs.com/) for interactive canvas
- [SheetJS (xlsx)](https://sheetjs.com/) for Excel import/export
- No build tools, no frameworks, no backend

---

## Screenshots

*Coming soon*

---

## License

Copyright 2026 Paolo Marani — [marani@ruledesigner.com](mailto:marani@ruledesigner.com)
