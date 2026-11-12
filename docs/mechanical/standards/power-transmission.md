# Power Transmission

How we design belts, pulleys, shafts, and gearing today.

## Belts

- **Belt center-to-center: add about +0.005", not more.**
  *Why:* +0.010" was meant to reduce friction, but belts ran loose, derailed, and burned pulleys. *([2026 Off-Season](../../seasons/2026/off-season.md))*
- **Use common, existing belt sizes.**
  *Why:* avoids supply chain problems and makes spares interchangeable. *([2026 Off-Season](../../seasons/2026/off-season.md))*
- **Build belt mechanisms rigidly, so alignment doesn't depend on the bearings alone.** Center-to-center distance and bearing alignment both have to hold under load.
  *Why:* a flexible floor mechanism let load push the belts down, which raised friction until the floor was unusable. *([2026 Off-Season](../../seasons/2026/off-season.md))*
- **Leave room for the belt to clear itself.** Don't package a belt so tightly that it can bind on its own return run.
  *Why:* the 2026 floor didn't have the space, and the belt bound on itself. *([2026 Off-Season](../../seasons/2026/off-season.md))*

## Pulleys

- **Use metal pulleys in high shock-load areas** when weight allows. Small metal pulleys are especially robust.
  *Why:* they held up extremely well. *([2026 Off-Season](../../seasons/2026/off-season.md))*
- **Printed pulleys are fine, with print inserts, if they stay aligned.** Design for manufacturing and assembly tolerance, not only CAD alignment.
  *Why:* the printed pulleys weren't the problem; loose belts and poor real-world alignment derailed belts and burned them. *([2026 Off-Season](../../seasons/2026/off-season.md))*
- **Buy and design SplineXS pulleys and print inserts**, including the metal pulleys, so no adapter is needed.
  *Why:* simpler assembly and better torque transmission. *([2026 Off-Season](../../seasons/2026/off-season.md))*

## Shafts and Hubs

- **SplineXL / MAXSpline works, but avoid it where gear ratios on the hub need to change.**
  *Why:* the hubs have to be large, which limits ratio changes. *([2026 Off-Season](../../seasons/2026/off-season.md))*
- For printed hubs, see [3D Printing](3d-printing.md#hubs).

## Ratios and Layout

- **Calculate gear ratios ahead of time.** Don't pick them by feel.
  *([2026 Off-Season](../../seasons/2026/off-season.md))*
- **Use as few belt and chain stages as the mechanism allows.**
  *Why:* simplifying the stages cut friction noticeably compared to the original 2026 robot. *([2026 Off-Season](../../seasons/2026/off-season.md))*
