# Fix the two broken README images

The `focus.svg` and `toolkit.svg` section files contained unescaped ampersands (`&`), which made the SVG XML invalid. GitHub therefore showed broken-image icons with the alt text instead of the graphics.

## Replace these exact files in your profile repository

- `assets/focus.svg`
- `assets/toolkit.svg`

Upload the corrected files from this package to those exact paths and commit the changes. Keep the README image references as `./assets/focus.svg` and `./assets/toolkit.svg`; no README edit is needed.

All SVG files in this package have been checked for valid XML, and the two corrected files were rendered locally to verify that they parse successfully.
