# Bill Split — HTML and CSS Prototype

This repository contains a standalone HTML/CSS version of the **Bill Split** interface. The design helps friends document shared expenses, distinguish payers from participants, and understand a final settlement.

## Assignment focus

- Semantic HTML provides the structure for the homepage, bills list, bill form, expense list, receipt area, settlement, and expense form.
- CSS provides the scrapbook layout, physical notebook composition, typography, spacing, colors, responsive behavior, and interaction states.
- CSS-only navigation makes the different page layouts reviewable without JavaScript.
- Form fields, buttons, links, the receipt upload field, and the expense settings disclosure communicate the interactions that can be implemented with JavaScript later.

## Open the project

Open `index.html` in a browser, or run any simple local web server from this folder.

## Current prototype behavior

The navigation links, example bill sticker, saved bill stickers, expense form, split settings, editable fields, and file picker can be explored. Adding or removing people, saving expenses, calculating new settlements, and storing bills are intentionally reserved for a later JavaScript version.

## Example data

The prefilled Lisbon Weekend bill contains four people and four expenses totaling **$428.40**. Its example settlement is:

- Sam pays Maya $80.10
- Leo pays Maya $22.20
- Leo pays Qilin $1.90

## Project files

- `index.html` — semantic structure and content
- `styles.css` — layout, visual design, and CSS-only interactions
- `assets/` — notebook layers, collage images, graph-paper background, and font

## Design reference and font note

The layout studies the physical notebook proportions and collage treatment of the provided reference site and adapts them to the student's original Bill Split sketches and content. PAGKAKI Regular is included for the course prototype. Confirm that the font license and reference assets permit public redistribution before using them in a commercial or broadly distributed project.
