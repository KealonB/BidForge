BIDFORGE v1.1 PWA
=================

New in v1.1
- Reusable assemblies built from itemized database components
- Assembly pricing breakdown: component material, material markup, labor hours and direct price
- Frozen takeoff pricing snapshots so later database edits do not rewrite historical bids
- Added Division 27 items: Coax Run, 24-Port Patch Panel, 4-Post Rack, 2-inch and 4-inch Speed Sleeves, 2-inch and 4-inch EZ-Path
- Editable background color in addition to accent color
- Item editing and searching
- Duplicate project
- Labor-hour total in bid summary
- Improved backup/export and service-worker updates

GITHUB PAGES UPDATE
Replace the files in your existing GitHub Pages repository with the files from this package and commit the changes. Keep index.html, manifest.json, sw.js and the icon files at the repository root.

After GitHub Pages finishes deploying, open the site once in Safari. The new service worker uses a new cache and will update the installed Home Screen app. If the Home Screen app still shows the previous interface, fully close it and reopen it; if necessary, visit the site once in Safari first.

DATA
BidForge stores project/database data in browser localStorage. The v1.1 app migrates the original v1 project data automatically and retains the same storage key. Export All Data regularly as a backup.
