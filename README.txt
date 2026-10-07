BidForge v1.1.1 Hotfix
========================

HOTFIX CHANGES
- Visible app version: v1.1.1
- Settings > Update App control
- New versioned service worker cache
- Network-first app updates to reduce stale GitHub Pages / iPhone PWA caching
- Item Database sorting by Category or Item Name
- Category filter and search
- Category headings in the item database
- Takeoff item choices grouped by category
- Assembly component choices grouped by category
- Preserves existing localStorage key (bidforge.v1) so existing bids/settings should remain on the same hosted URL

DEPLOY TO GITHUB PAGES
1. Back up BidForge from Settings > Export All Data before any update.
2. Extract this ZIP.
3. Replace the files at the ROOT of your existing GitHub repository with these files:
   index.html, sw.js, manifest.json, icon-192.png, icon-512.png
4. Commit the changes.
5. Wait for GitHub Pages deployment to finish.
6. Open BidForge. If the old screen is still shown, go to Settings > Update App.

NOTE
The Update App control clears only BidForge web caches. It does NOT intentionally clear localStorage, where your projects/database are stored. Export backups regularly anyway.
