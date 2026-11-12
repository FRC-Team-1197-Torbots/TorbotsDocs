# 2026 Off-Season Retro

What the 2026 off-season taught us. Each lesson links to the standard where the rule now lives. ✅ Keep · ❌ Fix · ⚖️ Mixed. See [Seasons](../index.md#how-a-retro-works) for what each mark means.

## Top Takeaways

- **Constrain anything that moves side to side.** Loose belts, rack and pinion drives, and intake arms all failed because nothing held them in line.
- **Tighten belt center-to-center** from +0.010" to about +0.005".
- **Don't over-pocket.** Detailed CAD overestimated weight, so we cut material we didn't need to and took damage because of it.
- **Get to a fully integrated CAD early.** Once CAD was done and parts arrived, the robot came together fast.
- **Prototype before committing**, especially for shooter compression.
- **Retain bearings positively** with bearing hats or shear pins, not press fit or print tolerance.

## Lessons by Standard

### [Power Transmission](../../mechanical/standards/power-transmission.md)

- ❌ Belt center-to-center +0.010" was too loose; now +0.005".
- ✅ Metal pulleys in high shock-load areas, and small pulleys, were very robust.
- ⚖️ Printed pulleys with inserts were fine; loose belts and misalignment burned them.
- ❌ Switch to SplineXS pulleys and inserts to drop the adapter.
- ⚖️ SplineXL / MAXSpline worked, but hubs are too large for adjustable ratios.
- ✅ Fewer belt and chain stages cut friction.
- ✅ Gear ratios calculated ahead of time.
- ✅ Common belt sizes.
- ❌ Floor belt friction: non-rigid mechanism, belt binding on itself.

### [Structure & Materials](../../mechanical/standards/structure-materials.md)

- ✅ 1/4" aluminum plate for rigidity and bearing retention.
- ✅ McMaster oversized 1/4" plate.
- ✅ Tapped holes in 1/4" plate.
- ❌ Over-pocketing in high-stress and contact areas.
- ⚖️ Wide robot: great throughput, but long lever arm caused flex and damage.
- ✅ Metal standoffs for motors.
- ✅ UHMW tape for friction.
- ❌ Thick polycarb doesn't hold a curve; use 1/32".

### [Bearings & Retention](../../mechanical/standards/bearings.md)

- ❌ Print tolerance didn't retain bearings; needed epoxy and spacers.
- ❌ Add bearing hats / positive bearing retention going forward.

### [Linear Motion](../../mechanical/standards/linear-motion.md)

- ❌ Rack and pinion needed both sides guided; slider blocks added too late.
- ❌ Don't go smaller on linear guide bearings.
- ❌ Restrict side-to-side movement on all moving parts.

### [Intakes](../../mechanical/standards/intakes.md)

- ⚖️ Original intake tried to be both compliant and rigid; polycarb split-motor redesign worked.
- ✅ Stacked 1/4" polycarb leaf spring.
- ✅ Big acquisition: cross bar and 3" roller, motor held by metal plates.

### [Shooters](../../mechanical/standards/shooters.md)

- ❌ No prototype; hood compression copied from teams without full-contact hoods was far too high.

### [3D Printing](../../mechanical/standards/3d-printing.md)

- ⚖️ Hubs: tapered ceiling helped; put nut access outside; use Onyx for high torque or RPM.

### [CAD](../../mechanical/standards/cad.md)

- ✅ Fully integrated CAD made the build fast.
- ✅ Parametric design.
- ⚖️ Detailed CAD came in heavy vs. the real robot, which led to premature weight cutting.
- ❌ Account for connectors that stick out (RJ45, USB).

### [Connectors](../../electrical/standards/connectors.md)

- ✅ Molex SL with TPA/CPA held up very well.

### [Power & CAN](../../electrical/standards/power-can.md)

- ❌ Mount the PDH-side SB120 to the frame.
- ❌ Replace breakers after any pop; keep more spares.
- ❌ Consider the PDH on the CAN loop for current logging.

## Original Notes

??? note "Original notes, as written"

    - [-] Belt center to center distance too loose, 0.01 is too much should probably do something like 0.005 going forward, intent was to keep it loose for friction reduction but this definitely backfired
    - [+] 1/4 inch aluminum for improved overall robot rigidity and beating retention, works much better than 1/8" if weight allows
    - [+] Mcmaster oversized 1/4" aluminum plate works just fine despite significant cost reduction (no longer as cheap as it used to be but still good savings)
    - [-] Attention to over pocketing on areas of high stress or external contact, we took a lot of damage both internally and externally. Driven by weight worries but we ended up under weight so this was unnecessary pocketing or the ribs were too small
    - [+/-] Came in way under weight vs CAD, given all parts were assigned materials and fasteners CAD'd it is good that we came in under but also not great because we ended up doing some premature weight optimization that caused parts to be less structurally sound. If we continue to have this fidelity of CAD, consider that the weight tended to come under. Often times we would be overweight because the CAD didn't have enough fidelity, but when it does, it seems like there were some conservatims baked in
    - [+] Metal pulleys in high shock load area and small pulleys proved to be extremely robust, we'll probably opt into should weight allow
    - [+/-] printed pulleys worked fine especially with the print inserts, however due to the loose belts + poor alignment, it would derail and burn the pulleys. I don't think the pulleys themselves were necessary bad but we need to do a better job aligning them (in CAD they were aligned but manufacturing and assembly tolerances exist)
    - [+/-] long robot width was great for throughput for intake and shooter, awful from defense, robot CG, and damage given the long lever arm. Shafts tended to flex when un supported and long cross bars took a lot of damage. Consider more normal to length supports to ensure damage is minimized if we go for a design like this again
    - [-] Linear actuation with rack and pinion, especially with it being exposed outside need to be tightly controlled side to side to stay on the rack. We should have added slider blocks that guide the intake arms way earlier. And you can't assume one side of it is enough, but sides need to be constrained. The trade off for the added friction is 100% worth it
    - [+/-] intake either needs to flex and give, or rigid enough to stow back on impact. Initial design took both concepts and poorly implemented both. A jack shaft that synchronized the movement would have helped for the rigid design, though replacing with polycarb arms with the split motor design ended up being a great adaption. For cost the replaceability, I'd probably bias towards polycarb compliant design in the future instead of full metal
    - [+] Big acquisition + rigid intake, having the cross bar and 3" diameter roller was a good design, additionally the metal plates actually holding the motor ensured that the pulleys and belts stayed aligned
    - [-] bearing retention need something more than just print tolerance, we ended up doing a combination of expoy + spaces for the dead axle setup but it would have been better if we had some shear pins in the print to make sure that the bearings stay in
    - [+/-] hub design with the tapered ceiling helped printing, definitely put the nut access holes to be on the outside of the tube if possible. Almost always use onyx or high grade engineering prints to ensure that the hub survives if used in high torque or high rpm setup
    - [-] potentially consider using bigger bearings for guiding the linear rail, I would probably not go any smaller than what we used this year
    - [+] Leaf spring effect of the stacked quarter inch polycarb is really good for flex, we should continue using this in future intake designs
    - [+] Simplified mechanisms for reduced friction from belt chains, definitely better than the original 2026 bot I'm this instance
    - [-] relying on rigidity from polycarb for curved pieces is not great if you actually need the curvature to exist, go for very thin (1/32") if you need something curved
    - [+] When CAD is finished and parts are here, the robot was completed relatively fast. We should bring back CAD hell and have a completely integrated system in CAD early
    - [-] no prototype/misinformed from the season ended up completely harming shooter performance, too much compression the hood, informed from other teams but given them most teams didn't do a full contact good, our compression ended up being significantly more than what was needed
    - [+] Uhwm tape is great for reducing friction, recommend for all future friction reduction usage
    - [-] we should use the spline xs pulley/print inserts so we don't have to use an adapter. Simplifies assembly and better torque transmission, along with metal pulleys we should buy the spline xs version as well
    - [+] Parametric design utilizing variables and contrains allowed for dynamic CAD and fast iteration, we should continue doing this
    - [-] friction in the floor made it unusable, two factors, one of which was already known but if the belts are pushed down by load then the friction increases, especially since we actually had not enough space to remove binding of the belt on top of itself, the mechanical design implementation lacked rigidy at the end and the alignment of the mechanisms relied on the bearing alignment but next time we should ensure that the mechanism are rigidly constructed with minimal flex to ensure belt center to center distance and bearing are all aligned correctly
    - [+/-] spline xl/max spline was overall successful though given how big the hubs need to be, I won't really suggest using this if we need to adjust gear ratios on the hub
    - [+] Actual calculation of gear ratios ahead of time definitely something we should be doing
    - [+] Using common or existing belt sizes to reduce supply chain issues
    - [+] Incorpating tapped holes in quarter inch plates to remove fasteners and integration
    - [+] Metal standoffs, they come in standard size and work great for motors, we should use these instead of printed ones since they don't creep
    - [-] account for connectors, especially things like rj45 and USB where they stick out
    - [+] TPA/CPA molec SL has held up incredibly well
    - [-] mount PDH side SB120 onto the frame somewhere
    - [-] breaker needs to replaced after any pop, we should also have many more of those
    - [-] consider adding PDH in the CAN loop for current  logging
    - [-] in general if there are any moving parts, restrict side to side movement
    - [-] bearing hat/bearing retention, need to do in the future
