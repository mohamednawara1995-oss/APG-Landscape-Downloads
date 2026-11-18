# APG Landscape Downloads

[Download the latest setup](https://github.com/mohamednawara1995-oss/APG-Landscape-Downloads/releases/latest/download/APGLandscapeSetup.exe)

Compiled plugin for Revit 2024 and 2025. Setup downloads and update checks require no GitHub sign-in or token.

## Version 1.8.2
Adds **Elements Tag** with the approved furniture/light/tag icon. Choose model categories, tag family, sources, worksets and editable instance/type parameter filters. Each new tag has its own Free leader; identical codes are not consolidated. Independent presets, preview images, coordinate reports and unplaced-element IDs are included.

Existing Shrubs & Ground Covers and Hardscape Tag workflows are retained. Use their separate buttons for planting and hardscape.

## Install and update
Save your work and close Revit. Run APGLandscapeSetup.exe, select 2024, 2025 or both, then reopen Revit.
Existing public-feed users can choose APG Landscape > Updates > Check for Updates, download the new release, and restart Revit.
Older private-feed or local-trial installations should install this setup once to switch to the public feed.
Update repository: `mohamednawara1995-oss/APG-Landscape-Downloads`.

The chosen tag family must support the category and have valid label values. Existing tags are not duplicated. Review preview reports for incompatible or unplaced elements before applying.
Validation: six Elements checks passed live in isolated Revit 2024 documents, plus 11 Shrubs and six Hardscape regression checks. Both builds and 17 installer assertions passed. Revit 2025 tagging has build/installer validation only.

Plugin source files are not distributed here. GitHub's automatically labelled “Source code” archives contain this distribution repository's files, not plugin source.

Copyright © 2026 Mohamed Nawara. All rights reserved. Public downloading does not grant an open-source license.
