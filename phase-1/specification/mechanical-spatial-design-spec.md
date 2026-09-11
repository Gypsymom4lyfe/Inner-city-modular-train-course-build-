# Phase 1 Mechanical & Spatial Design Specification

## Scope

This package defines the initial geometric envelope, bidirectional operating symmetry, and core spatial interfaces for an inner-city modular rail pod intended to carry a modular compute cassette over standard North American rail.

## Governing constraints

| Parameter | Value | Notes |
| --- | --- | --- |
| Track gauge | 1,435 mm | Standard North American / standard gauge |
| Overall vehicle length | 12,000 mm | Selected to remain maneuverable on tight municipal alignments |
| Maximum body width | 2,900 mm | Leaves margin relative to restricted industrial clearances |
| Maximum shell height | 3,350 mm | Low-profile urban envelope target |
| Symmetry | Fully bidirectional | Identical fore/aft operating profile |
| Frame length | 11,000 mm | Leaves protected crush/transition zones at both ends |
| Primary battery pan | 5,200 × 1,800 × 220 mm | Centerline-mounted for low CG ballast |
| Compute cassette envelope | 3,200 × 1,700 × 1,850 mm | Centralized equipment module volume |

## Spatial layout decisions

- The outer shell uses matching end profiles to support bidirectional operation without turning loops or wyes.
- The floor structure reserves the lowest practical central bay for battery mass concentration to reduce roll and pitch response.
- The frame skeleton centers the compute cassette directly above the battery pan to keep vertical and longitudinal mass distribution balanced.
- Under-floor louver pockets are located above the assumed minimum obstruction band so that cooling airflow can be introduced without breaking the clearance envelope.

## Clearance strategy

- Body width and under-floor features are kept inside a restricted urban industrial profile rather than a full mainline freight plate.
- End transitions are flattened symmetrically to improve obstruction margin at curves and switch hardware.
- The shell, frame, and equipment bay all preserve a centered loading condition around the track gauge centerline.

## Phase 1 modeling output

The STEP files in `/phase-1/cad/` provide a simplified baseline CAD package suitable for import into downstream CAD, clearance-checking, and solver tools. They intentionally prioritize envelope control and mounting-space definition over detailed fabrication features.
