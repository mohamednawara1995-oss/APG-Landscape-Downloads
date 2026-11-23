APG Landscape 1.8.7 — Revit 2024 and 2025

Updates since 1.8.2:
- Streetscape Ramp: improved native curved-edge height checks, preservation of the surrounding shaped surface, and handling of exact pre-existing floor/toposolid warnings. New overlaps and unrelated errors still roll back.
- Complex floors: removed the 15,000 preservation-sample limit without splitting floors; spatial lookup reduces unnecessary native face queries while retaining whole-floor checks and existing tolerances.
- Separate Floors: preserves interior slab-shape points, their elevations, and non-boundary creases when separating disconnected regions. Native curved boundaries, floor data, and grouped/dependent-object safeguards remain.

Validation: 13 separation integration cases, 35 ramp/walkway/warning regressions, 2,500 boundary grid checks and 20 earthwork assertions passed in Revit 2024. The complex-floor stress case checked 17,940 samples; the source preparation captured 17,595. Actual packaged DLL preview, rollback, commit and separate verification passed on isolated copies. All 17 combined-installer assertions passed. Revit 2025 plugin/test builds passed; live 2025 testing has not been performed for these fixes.

Existing tagging tools, embedded families, other landscape tools and update controls are retained. The separator splits disconnected regions; it does not cut continuous floors.

Save work and close Revit before installing APGLandscapeSetup.exe. Choose 2024, 2025 or both. Existing public-feed users can use Check for Updates, then restart Revit. Older loader or local-trial installations should run this combined setup once. If Revit shows an already-existing site warning, review it and choose OK to continue or Cancel to roll back.

Copyright © 2026 Mohamed Nawara. All rights reserved.
Compiled downloads are public; source and family archives remain private.