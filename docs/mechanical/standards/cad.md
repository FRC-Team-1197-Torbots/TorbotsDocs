# CAD

How we model robots today.

## Integration ("CAD Hell")

- **Get the whole robot fully integrated in CAD early,** before fabrication starts.
  *Why:* once CAD was finished and parts arrived, the robot came together fast. *([2026 Off-Season](../../seasons/2026/off-season.md))*
- How CAD hell fits into the build schedule each year is in that season's plan. See [2027 Season Plan](../../seasons/2027/plan.md#alpha-bot-and-cad-hell).

## Parametric Design

- **Drive the design with variables and constraints** so dimensions can change without rebuilding parts.
  *Why:* made the CAD dynamic and fast to iterate. *([2026 Off-Season](../../seasons/2026/off-season.md))*

## Model What Sticks Out

- **Model connectors and leave clearance for them,** especially RJ45 and USB.
  *Why:* they stick out from the device and need clearance. *([2026 Off-Season](../../seasons/2026/off-season.md))*

## Weight Estimation

- **When every part has a material and fasteners are modeled, expect the real robot to come in under the CAD weight.** Don't make parts weaker to cut weight until the estimate says you have to.
  *Why:* in past years low-detail CAD meant we came in overweight. In 2026 the detailed CAD turned out conservative, and early weight cutting made parts weaker than they needed to be. *([2026 Off-Season](../../seasons/2026/off-season.md))*
- See [Structure & Materials: Pocketing](structure-materials.md#pocketing).
