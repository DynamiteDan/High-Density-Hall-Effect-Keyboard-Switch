# High-Density Hall Effect Switch


# THIS PROJECT IS CURRENTLY IN THE CONCEPT STAGE, ONLY WHEN A CAD MODEL IS FINISHED WILL ANY PROTYPING BEGIN. I AM STILL CURRENTLY WORKING OUT THE EXACT SPECIFICATIONS AND TOLERANCES TO REDUCE PRICE.

The objective of this project is to design the deepest-sounding (“thockiest”) hall effect switch possible. This design is primarily exploratory and may never enter production. It is highly likely that not even a single switch will be manufactured to the exact specifications outlined here, but bench prototypes might be made as a proof of concept.

From cost estimates, each switch would cost approximately $1.50 to produce at a scale of 10,000 units. This estimate excludes the mold, which could cost upwards of $20,000. The cost is mainly due to the liner, which requires an overmold, and the materials involved.
I think that if this were to actually be thought of as a real concept, and put into production, the liner would probably only be put in spots that have contact with the stem. Although this would reduce the effectiveness of the damping, it would still probably have the deepest sound profile of any known switch.

A bench prototype would probably be made by 3d printing the top and bottom housing of a switch with grooves for places to place TPU strips, then comparing the acoustics, feel, and consistency of the switch. This step will probably be the tipping point on whether a manufactured version is viable.

The design will aim to create a switch that:
1. Possesses high density, shifting the resonant frequency downwards.
2. Has high intrinsic damping.
3. Is electrically insulating and non-magnetic.
4. Is manufacturable at a normal scale.

## Stem

**Material**

* POM
* Alternate: PBT (PTFE-modified) for a drier tone.

**Geometry**

* Overall height: 14.2 mm; cross-section compatible with MX-style keycaps.
* Rails: two longitudinal bearing lands, width 1.00 mm, surface finish Ra 1.2 µm.
* Magnet pocket: Ø2.50 ± 0.03 mm × depth 1.20 ± 0.02 mm (disc magnet), concentric with stem axis ±0.05 mm; 0.10 mm fillet base.
* Travel stops: micro-chamfers of 0.10 mm at all impact lips to distribute impulse time.

**Tolerances**

* Lateral clearance to guides: 10 ± 5 µm per side.
* Axial play at slider cap shoulder: ≤ 0.03 mm.

**Notes**
Maintain magnet pocket and guide tolerances unchanged if substituting PBT.

## Upper Housing

**Material**

* Glass-filled PA12 (\~15% GF), dry-as-molded.
* Alternative: PC/ABS, high-flow.

**Construction**

* Thin rigid shell with overmolded liner on the inner walls.

**Geometry**

* Wall thickness: 1.00 mm; draft angle 1.5°.
* Guide bores/slots: stem engagement length ≥ 3.0 mm; straightness ≤ 0.03 mm.
* Liner: tungsten-filled TPU, Shore A 90, thickness 2.5 mm continuous sleeve bonded to inner walls and roof.
* Top-out pad: liner thickened locally by +0.5 mm to soften impact.

**Tolerances (critical)**

* Guide-to-guide parallelism: ≤ 0.03 mm.
* Inner-to-outer shell concentricity: ≤ 0.05 mm.

**Notes**
Mechanical keys (micro-undercuts or through-holes) to be incorporated in PA12 for liner retention; adhesives not required.

## Lower Housing

**Material**

* Glass-filled PA12 shell with integrated W-TPU liner.
* Separate base gasket (W-TPU or butyl).

**Geometry**

* Shell wall thickness: 1.00 mm; draft 1.5°.
* Hall datum boss: molded reference plane under magnet path; flatness ≤ 0.03 mm.
* Actuation control: magnet-to-sensor gap ±0.05 mm across all keys.
* Liner: W-TPU, Shore A 90, 2.5 mm continuous on inner sidewalls/floor; bottom-out pad thickened to 3.0 mm beneath stem foot.
* Gasket seat: recess for 0.8 mm W-TPU/butyl gasket with concentric ribs to reduce squeeze-hardening.
* Shielding (optional): thin low-carbon steel shield below PCB (external to housing) for cross-talk mitigation.

**Tolerances (critical)**

* Snap features to upper: ±0.03 mm.
* PCB standoff posts: ±0.05 mm height.
* Plate latch retention: ≥ 20 N.

**Notes**
Keep ferromagnetic elements out of magnet path; any metals must be austenitic or isolated behind liner thickness.

## Spring

**Material**

* Music wire (ASTM A228) or SUS304 stainless steel.
* Optional shot-peen + light oil for damping.

**Specifications (linear example)**

* Free length: 16 mm.
* Wire diameter: 0.14 mm.
* Outer diameter: 3.9 mm.
* Active coils: 15.
* Bottom-out force (4.0 mm travel): 65 cN.
* Actuation force: \~40–50 cN (tunable).

**Anti-Ring Treatments**

* Micro-phosphate or thin polymer dip on 1–2 coils.
* Alternative: 0.2 mm W-TPU sleeve on lower 1–2 coils.

**Notes**
Spring centered via shallow pilot bosses in both housings; axial clearance 0.2 mm to avoid scrape noise.
