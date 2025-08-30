Just a basic file where I will post the necessary tolerances

# Global notes

* **Datums:**
*     A = lower-housing Hall datum plane;
*     B = housing X guide wall; C = housing Y guide wall.
*     Where relevant, stem datums reference mating surfaces to B/C.
* **Process capability target:** Cpk ≥ 1.33 on criticals (≈±3σ inside spec).

# Stem (POM)

* **Overall stem height:** ±0.05
* **Rail width (each):** ±0.02; **rail thickness**: ±0.02; **rail straightness**: ≤0.03.
* **Rail parallelism to stem axis:** ≤0.03 relative to stem axis.
* **Magnet pocket Ø:** ±0.03; **pocket depth:** ±0.02; **concentricity** of pocket to stem axis: ≤0.05.
* **Travel-stop ledge heights/chamfer lands:** ±0.05.
* **Stem shoulder axial play (assembly limit):** ≤0.03 (functional requirement; enforce via gage).

# Upper housing (GF-PA12)

* **Guide bores/slots width (X & Y):** ±0.03; **straightness**: ≤0.03; **parallelism (B∥C):** ≤0.03.
* **Inner-to-outer shell concentricity:** ≤0.05.
* **Roof (top-out) pad land height:** ±0.05; **local thickening features**: ±0.05.
* **Snap features (upper half):** height ±0.05; lateral ±0.10.
* **Non-functional outer walls/ribs:** ±0.10–0.20 (cosmetic).

# Lower housing (GF-PA12)

* **Datum A (Hall reference plane) flatness:** ≤0.03.
* **Magnet-to-sensor nominal gap (functional stack):** variation ≤±0.05 across keys.
* **Guide entrance lead-in geometry:** ±0.05 on land heights; chamfers ±0.10.
* **PCB standoff post height:** ±0.05; **planarity of 3+ standoffs:** ≤0.05 relative to A.
* **Plate latch/snap:** retention geometry ±0.05 height, ±0.10 lateral.
* **Non-functional outer walls/ribs:** ±0.10–0.20.

# Elastomer (TPU pads/liners, if molded)

* **Bottom-out pad thickness (effective):** ±0.10 (thickness uniformity matters more than absolute).
* **Top-out pad/local bumper thickness:** ±0.10.
* **Overmold lock features (holes/keys in nylon):** ±0.05 (necessary).

# Spring

* **Free length:** ±0.10; **OD:** ±0.02; **wire Ø:** ±0.01; **force @ specified travel:** ±10%.

# Magnet (NdFeB, disc)

* **Diameter / thickness:** vendor spec (typ. ±0.02 / ±0.02).
* **Stem pocket fit:** aim for press or light interference 0.01–0.03 (no adhesive required if retention ribs are used).
* **Axial location in stem:** resultant gap contribution ≤±0.02.

# Functional clearances & assemblies

* **Running clearance, stem-to-guides (each side):** **20–30 µm** (achieved via rail width control ±0.02 and slot width ±0.03).
* **Total lateral key-top wobble (assembled, no cap):** ≤0.20 measured at stem tip.
* **Bottom-out height (from A):** ±0.05 across keys.
* **Actuation repeatability (Hall threshold):** gap-stack ≤±0.05.

# GD\&T callouts

* **A:** Lower housing Hall reference plane — **FLAT ≤0.03**.
* **B/C:** Mutually perpendicular guide walls — **PERP B⊥C ≤0.03**, **PAR C∥B ≤0.03**.
* **Guide slots:** **STR ≤0.03** to B/C; **POS** width to B/C: ±0.03.
* **Stem rails:** **PAR rails ∥ stem axis ≤0.03**; **STR ≤0.03**; **SIZE** ±0.02.
* **Magnet pocket (stem):** **POS ≤0.05 to stem axis**; **DEPTH** ±0.02.
* **PCB standoffs:** **POS** to A within **Ø0.10**, **HEIGHT** ±0.05.
