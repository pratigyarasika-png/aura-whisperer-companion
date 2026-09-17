# Mobile orbit symmetry fix

## Changes
- Give all four mobile action nodes identical fixed dimensions, padding, border radius, icon sizing, and single-line labels.
- Position each node at the exact top, right, bottom, and left midpoint of the orbit.
- Scale the complete mobile orbit assembly uniformly so side pills remain inside a 390px viewport without distortion or overlap.
- Keep the existing expanded desktop cards and desktop orbit spacing unchanged at 768px and above.

## Validation
- Check 390px mobile and 1280px desktop views.
- Measure node dimensions and center coordinates to confirm equal sizing, 90-degree symmetry, no central-dial collisions, and no horizontal overflow.
