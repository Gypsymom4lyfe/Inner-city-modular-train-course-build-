# Spatial Integration Blueprint

## Reference frame

- Origin: geometric center of the pod at top-of-frame datum.
- X-axis: longitudinal, positive toward either operational end (symmetric design).
- Y-axis: lateral, positive to the right when facing either end.
- Z-axis: vertical, positive upward.

## Mounting-point schedule

### Battery pan mounts

| ID | X (mm) | Y (mm) | Z (mm) | Purpose |
| --- | --- | --- | --- | --- |
| BP-1 | -2,100 | -720 | 500 | Battery cradle isolator |
| BP-2 | -2,100 | 720 | 500 | Battery cradle isolator |
| BP-3 | -700 | -720 | 500 | Battery cradle isolator |
| BP-4 | -700 | 720 | 500 | Battery cradle isolator |
| BP-5 | 700 | -720 | 500 | Battery cradle isolator |
| BP-6 | 700 | 720 | 500 | Battery cradle isolator |
| BP-7 | 2,100 | -720 | 500 | Battery cradle isolator |
| BP-8 | 2,100 | 720 | 500 | Battery cradle isolator |

### Compute cassette supports

| ID | X span (mm) | Y (mm) | Z (mm) | Purpose |
| --- | --- | --- | --- | --- |
| CC-R1 | -1,600 to 1,600 | -520 | 760 | Left cassette rail |
| CC-R2 | -1,600 to 1,600 | 520 | 760 | Right cassette rail |
| CC-B1 | -1,600 | 0 | 760 | Forward cassette bulkhead support |
| CC-B2 | 1,600 | 0 | 760 | Rear cassette bulkhead support |

## Integration envelope

- Compute cassette reserved volume: 3,200 × 1,700 × 1,850 mm.
- Battery pan reserved volume: 5,200 × 1,800 × 220 mm.
- Service routing zone: 250 mm lateral clearance outside cassette rails for power and coolant distribution.
- Under-floor louver zone: centered near X = ±1,700 mm and ±2,800 mm, above the obstruction-sensitive lower envelope.

## Assembly intent

- Heavy battery mass remains below the compute cassette centroid to preserve a pendulum-like restoring effect.
- The shell and frame use identical end geometry so either end can serve as the lead end without mechanical reconfiguration.
- Equipment mounts are centered to maintain balanced axle loading in both travel directions.
