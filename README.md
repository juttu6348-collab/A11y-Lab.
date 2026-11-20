# A11y Lab

An interactive accessibility learning lab built with HTML, CSS, and vanilla JavaScript. This student project demonstrates selected WCAG 2.1 A/AA concepts through practical exercises.

## Run locally

Open `index.html` in a modern browser. No installation or build is required. A local web server or HTTPS hosting can provide more consistent clipboard and browser-storage behavior.

## Modules

1. **Keyboard and screen reader:** tabs, accordion, modal, menu, validation, status messages, sortable table, focus log, and simplified ARIA inspector.
2. **Contrast and magnification:** contrast calculator, color suggestions, built-in sample scanner, zoom, text spacing, reflow, and color-vision simulations.
3. **Remediation workshop:** before/after ShopCo samples and 21 issues to find and fix.
4. **Audit:** a selected 20-item checklist with notes, report generation, copying, and printing.

Theme, issue progress, checklist answers, and notes are saved in this browser when storage is available. Demo form names and emails are not saved. Reset saved progress clears the learning records while retaining the theme.

## Manual test guide

- Navigate all four modules using Tab, Shift+Tab, arrows, Enter, Space, and Escape.
- Open the modal, verify focus stays inside, then close it and verify focus returns.
- Submit the empty demo form and follow the error-summary links.
- Check announcements with NVDA, VoiceOver, or another screen reader, including report copying in Module 4.
- Open Module 2 and check initial preview sizing. Resize the window; try browser zoom and text spacing.
- Save notes and issue progress, reload, confirm restoration, then try resetting progress.
- Compare Before and After. Before intentionally blocks Tab in the promo field; Escape releases focus.
- Check print preview and copied reports after editing checklist answers.

## Limitations

This is a teaching aid, not a full WCAG audit or certification. The checklist contains selected criteria. The scanner only checks text contrast in the built-in examples; it does not evaluate arbitrary websites, images, borders, or composited transparency. The ARIA inspector estimates names and roles rather than reading the browser accessibility tree. Simulations do not replace real assistive-technology testing. Sample store controls are demonstrations.

The beach-shoe SVG illustration is embedded, so no external assets are required. No data is sent to a server. Avoid sensitive information in notes on shared computers.

## Publish

Suggested repository name: `a11y-lab`. Upload this folder's contents to a separate GitHub repository. The entry point is `index.html`. Add screenshots of each module after reviewing the page in a browser.
