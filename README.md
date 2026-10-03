# Study Check-in v7 — Fixed

Updated to the approved bottom-menu design.

Fixes:
- Removed dependency on the old hidden `saveState` element that caused save/checkbox actions to throw an error.
- Uses a v7 localStorage key while migrating existing v1 data when present.
- Corrected Aptitude planning to use the exact 7,511 remaining lecture minutes and 45-minute daily allocation.
- Corrected the Aptitude completion horizon to Day 170 (including the first 3 reactivation days); the final Aptitude segment is 41 minutes.
- Progress totals now use the exact 7,511-minute Aptitude workload.
- Updated the displayed app title to v7.
- Preserved the bottom hamburger menu and bottom-sheet navigation design.
