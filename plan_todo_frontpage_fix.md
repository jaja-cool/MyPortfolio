# TODO: Fix frontpage not running

## Information gathered

- `frontpage.html` is only a `<section>...</section>` fragment; it lacks full HTML structure and does not load `style.css`.
- `style.css` references `background.jpg`, which is not present in the project folder (likely causes missing/blank background).

## Plan

1. Update `frontpage.html` to be a complete HTML document and link to `style.css`.
2. Update `style.css` to use an existing image for `.bg-image` (or add the missing background image if you have one).
3. Verify by opening `frontpage.html` in a browser.

## Dependent files to edit

- `frontpage.html`
- `style.css`

## Follow-up steps

- Double-check that image filenames match exactly (Windows filenames are case-insensitive, but spaces like `sec img.png` must be handled correctly in URLs).
- Open `frontpage.html` in the browser to confirm layout renders.
