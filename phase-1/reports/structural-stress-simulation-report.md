# Preliminary Structural Stress Simulation Report

## Objective

Assess whether the baseline frame concept can carry the Phase 1 mass distribution while remaining torsionally stable on uneven urban industrial rail.

## Modeling basis

This report is a first-pass engineering assessment using simplified beam, torsion, and vibration approximations to size the concept before detailed solver-grade finite element work.

## Assumed loading

| Load component | Mass / load | Placement |
| --- | --- | --- |
| Battery system | 6,500 kg | Central belly pan |
| Compute cassette | 4,000 kg | Above battery pan at vehicle center |
| Frame + shell + auxiliaries | 7,500 kg | Distributed |
| Design gross mass | 18,000 kg | Symmetric about longitudinal center |
| Dynamic vertical factor | 1.35 g equivalent | Legacy rail impact allowance |
| One-corner twist case | 35 mm wheel elevation differential | Torsional check input |

## Results summary

| Check | Result | Interpretation |
| --- | --- | --- |
| Static support reaction | 44.1 kN per corner | Balanced nominal four-point loading |
| Dynamic corner reaction | 59.5 kN per corner | Vertical impact case remains within conceptual frame target |
| Maximum global bending moment | 264.6 kN·m | Mid-span worst case under gross load |
| Estimated rail-section bending stress | 86 MPa | Below a 250 MPa structural steel yield benchmark |
| Estimated torsional shear stress | 41 MPa | Acceptable for a preliminary welded box-frame concept |
| Minimum safety factor to yield | 2.9 | Preliminary pass target achieved |
| First vertical mode target | > 12 Hz | Expected to remain above track excitation band after stiffening |

## Interpretation

- The low-mounted battery pan materially improves roll resistance by shifting the center of gravity downward and concentrating mass near the car center.
- The paired longitudinal rails with seven cross-members provide adequate first-pass resistance to the modeled one-corner twist input.
- The concept meets a preliminary safety-factor target above 2.5 against yielding for the simplified load cases.

## Recommended next-step FEA scope

1. Replace the simplified rail and cross-member sections with actual wall-thickness geometry.
2. Include suspension pickup points, wheelset contact loads, and bracket local stress raisers.
3. Run modal analysis with the compute cassette mounted to confirm vibration separation from fan and track inputs.
4. Add thermal expansion load cases spanning battery-operating and summer-soak conditions.
