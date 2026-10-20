# LDT Weekly Plan

The website is the standalone `index.html` at the repository root.

Live site: https://jiayili6812.github.io/LDT/

## Edit, preview, then publish once

1. Check `git status` before starting. When the working tree is clean, run
   `git pull --ff-only` to get any newer GitHub changes. If local edits are
   pending, compare and reconcile them first; do not overwrite or discard them.
2. Edit `index.html` and preview it locally in a browser. Repeat as often as
   needed. Editing, saving, and previewing do not publish anything.
3. Wait for an explicit request to **publish**. Do not push after each small edit.
4. Review the final diff and check the page. Stage only the intended website
   files, commit the finished batch, and push to `main`.
5. Confirm the GitHub Pages deployment succeeds, then check the live site.

## Past weeks

Completed weeks are hidden by default after their Sunday end date, using Pacific
time. Uncheck **Hide past weeks** to show them again; all assignments remain in
the document. The checkbox choice is remembered in the current browser.

## GitHub Pages settings

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/ (root)**

The local folder can be named `output`; it is still the repository root.
Do not change Pages to an `output` folder or upload an extra `output` directory.
Renaming or moving the local checkout does not change the Pages source.

## Files and history

The `.gitignore` allowlist keeps unrelated course documents out of this repository.
If the site later needs image, CSS, or other asset files, explicitly allow and
review those files before publishing.

Git keeps committed versions available to restore. Browser-saved preferences are
local to that browser and are not part of Git history.
