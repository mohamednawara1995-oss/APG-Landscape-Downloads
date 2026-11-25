# Landscape Tools v1.8.9

Copyright © 2026 Mohamed Nawara. All rights reserved.

APG Landscape is now named Landscape Tools in the Revit ribbon, About dialog, setup and update windows. The combined setup supports Revit 2024 and 2025 and retains all existing landscape and tagging tools.

New: Floors > Floor to Filled Region. Select host-model floors in a horizontal plan to create view-specific filled regions. Region types are named "Floor Type Name region" and match the top material's surface foreground pattern and colour. Native curved boundaries, internal sketch openings, hosted openings and disconnected outlines are supported. Original floors remain unchanged. Existing region types are reused only when their settings match; conflicts roll the conversion back without overwriting existing types.

The conversion copies plan footprints and material foreground settings. View/filter overrides, manually adjusted hatch origins/rotations, material background patterns and 3D elevations are not copied. Multiple different top patterns on one floor are rejected. The project needs an existing Filled Region type as a starting type.

Installation: save work, close Revit, run LandscapeToolsSetup.exe, select 2024, 2025, or both, then reopen Revit. APGLandscapeSetup.exe is an identical compatibility download for existing links. Older installations must run this setup once: the renamed ribbon requires updater loader 2.0.1. Older loaders may report that a newer setup is required rather than offer an automatic payload update. Both update manifests explicitly require loader 2.0.1 to prevent an incompatible startup. Existing settings, add-in identifiers, family names and repository addresses are retained.

Validation: nine live Floor to Filled Region scenarios passed in isolated unsaved Revit 2024 documents, including shape-edited floors, curves, openings, pattern/type reuse, conflict rejection and rollback. Both 2024/2025 payloads, loaders and the combined installer compiled. Nineteen installer assertions and twenty-one updater checks passed. Revit 2025 has build/installer validation; live integration testing of the new tool in 2025 remains pending.

Compiled installers and update feeds are public. Source, bundled tag families and build/test scripts remain in the private development archive. No project models are included.
