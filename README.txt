BIDFORGE v1.2.0
================

New in v1.2:
- Named takeoff sections for systems, phases, buildings, floors, alternates, etc.
- Per-project Lost Time tab with customizable daily labor-loss items.
- Lost time is converted to a labor factor and automatically increases estimated labor hours/cost.
- Seed lost-time labels: TRA, Morning Break, Restroom, Lunch, Afternoon Break.
- Custom Expenses tab for rentals, freight, parking, permits, travel, per diem, subcontractors, disposal, and other job costs.
- Expenses are added to direct cost; each can optionally be included in the taxable base.
- Section-by-section summary on Takeoff and Summary screens.
- CSV export now includes section names, adjusted labor, expenses, and lost-time percentage.
- Existing v1/v1.1 projects are migrated automatically into a Base Takeoff section.
- Existing local data key remains bidforge.v1 so prior bids/settings can carry forward.
- App version/update control remains in Settings.

UPDATE YOUR GITHUB PAGES SITE
1. Back up BidForge from Settings > Export All Data.
2. Unzip this package.
3. Replace index.html, sw.js, manifest.json, icon-192.png, and icon-512.png at the root of the existing GitHub repository.
4. Commit the changes and wait for GitHub Pages to deploy.
5. Open BidForge and use Settings > Update App if the version does not immediately show v1.2.0.

LOST TIME FORMULA
Paid workday minutes / productive workday minutes = labor factor.
Example: 8-hour day (480 min) with 60 min lost = 480 / 420 = 1.142857, or +14.29% labor.
This factor applies to takeoff labor hours/cost only.
