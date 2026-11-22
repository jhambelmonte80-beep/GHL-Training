# Beginner GHL Academy — Workspace Rendering Fix

This build fixes blank CRM workspace panels reported in the training screenshots.

## What changed
- Hardened loading of saved browser practice data so older or incomplete local saves do not break newer workspace pages.
- Added safe defaults for contacts, form fields, pipeline stages, opportunities, workflows, tasks, logs, calendar settings and integration settings.
- Added an error boundary to workspace navigation. If a page encounters a rendering problem, it now displays a visible recovery message instead of a blank panel.
- Kept the editable local training workspaces and client missions.

## Update GitHub Pages
1. Extract this ZIP.
2. Replace `index.html` and `README.md` in your existing repository.
3. Commit the changes and refresh GitHub Pages.
4. If a previous broken state is still cached in your browser, use **Reset training data** in the GHL workspace once, then reload the page.

## Important
This is a local GHL-inspired training simulator, not a connected HighLevel account. Practice records and configuration changes are stored in the browser and do not send real email/SMS or modify a live account.
