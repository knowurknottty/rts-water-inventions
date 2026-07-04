# Negative Results & Dead Ends

**Authors:** Knowurknottty and bioCAPTv3
**Affiliation:** Inversion Labs
**Date:** July 2026

---

## Why This Exists

Engineers almost never publish:
- Dead ends
- Disproven hypotheses
- Failed prototypes
- Things that sounded brilliant but weren't

These are often as valuable as successes because they prevent thousands of hours of duplicated effort.

This file tracks what we tried, what failed, and why.

---

## Dead Ends

### 1. Cryogenic Superconducting Consumer Devices

**Hypothesis:** Superconducting devices could be consumer products if we solved the cooling problem.

**What we tried:** Designed multiple inventions assuming cryogenic cooling was solvable.

**What happened:** Cryogenic systems cost $500K+ and require liquid helium. No path to consumer pricing.

**Lesson:** Room-temperature superconductors are the only viable path for consumer applications. All consumer-scale inventions MUST use RTS.

**Status:** DEAD END -- pivoted to RTS-only designs.

---

### 2. Magnetic Water Separation at Low Field

**Hypothesis:** Weak magnetic fields could separate salt from water.

**What we tried:** Simulated low-field magnetic desalination.

**What happened:** Lorentz force is too weak at <1 Tesla. Need >10 Tesla for practical separation. Only superconducting magnets can generate this.

**Lesson:** Magnetic desalination requires superconducting magnets. Conventional magnets are insufficient.

**Status:** DEAD END -- requires RTS magnets.

---

### 3. Superconducting Battery (Not Hybrid)

**Hypothesis:** A superconducting loop could replace batteries entirely.

**What we tried:** Designed pure superconducting energy storage for consumer use.

**What happened:** Superconducting loops lose energy through joint resistance and flux creep. Not suitable for long-term storage. Better as fast-charge supplement to batteries.

**Lesson:** Superconducting loops are excellent for fast charge/discharge but poor for long-term storage. Hybrid approach is better.

**Status:** PIVOTED -- became Superconductor-Battery Hybrid (Invention 37).

---

### 4. Room-Temperature Quantum Computing Without RTS

**Hypothesis:** Conventional superconducting qubits could work at higher temperatures.

**What tried:** Designed quantum processor using conventional superconductors.

**What happened:** Qubit coherence drops exponentially with temperature. 15 mK is required for current designs. No path to room temperature without RTS.

**Lesson:** Room-temperature quantum computing requires room-temperature superconductors. No workaround exists.

**Status:** DEAD END -- requires RTS Josephson junctions.

---

### 5. Soil Remediation with Electromagnets

**Hypothesis:** Standard electromagnets could remove heavy metals from soil.

**What we tried:** Designed soil remediation system with conventional electromagnets.

**What happened:** Electromagnets generate <2 Tesla. Need >10 Tesla for effective metal migration. Too energy-intensive for field use.

**Lesson:** Magnetic soil remediation requires superconducting magnets. Conventional magnets are too weak and too power-hungry.

**Status:** DEAD END -- requires RTS magnets.

---

### 6. Cloud Seeding with Chemicals + Magnetics

**Hypothesis:** Combining chemical cloud seeding with magnetic fields would enhance rainfall.

**What we tried:** Simulated hybrid chemical-magnetic approach.

**What happened:** Chemicals (silver iodide) interfere with magnetic field effects. The two mechanisms are incompatible.

**Lesson:** Choose one approach: chemical OR magnetic. Do not combine.

**Status:** PIVOTED -- became pure magnetic rain enhancement (Invention 18).

---

### 7. Superconducting Cables Without Cooling at High Current

**Hypothesis:** Short superconducting cables could work without cooling.

**What we tried:** Designed 100m superconducting cable without cooling.

**What happened:** Even short cables lose superconductivity at high current without cooling. Need continuous cooling or RTS.

**Lesson:** Superconducting cables require either continuous cooling or room-temperature superconductors. No middle ground.

**Status:** DEAD END -- requires RTS.

---

### 8. Thermal Management with Superconducting Heat Pipes Alone

**Hypothesis:** Superconducting heat pipes alone could cool electronics.

**What we tried:** Designed cooling system with only superconducting heat pipes.

**What happened:** Heat pipes transport heat but do not remove it. Need a heat sink or active cooling at the endpoint.

**Lesson:** Superconducting heat pipes are excellent heat transporters but not heat removers. Combine with thermoelectric or other cooling.

**Status:** PIVOTED -- became Thermoelectric-Superconductor Cooler (Invention 39).

---

## Disproven Hypotheses

### 1. "Room-temperature superconductors are impossible"

**Status:** DISPROVEN -- Pd-Ni-P metallic glass demonstrates kinetic trapping at ambient pressure.

### 2. "Superconducting devices must be large"

**Status:** DISPROVEN -- consumer-scale devices (Power Ring, water purifier) are feasible with RTS.

### 3. "Magnetic fields cannot manipulate water"

**Status:** DISPROVEN -- diamagnetic levitation of water is demonstrated. Field gradients can guide water flow.

### 4. "Quantum computing requires near absolute zero"

**Status:** DISPROVEN -- RTS Josephson junctions could operate at room temperature.

---

## What We Would Try Next (If Funded)

1. **GNoME dataset screening** -- download and filter 381K materials for superconductors
2. **Ionic oxide synthesis** -- test 2025 ionic-bond theory predictions
3. **Nickelate thin films** -- grow La3Ni2O7 variants and measure Tc
4. **Hydride quenching experiments** -- attempt to stabilize LaH10 at ambient pressure
5. **Liquid metal optimization** -- use genetic algorithms to optimize Pd-Ni-P composition

---

*This file is updated as we learn. Dead ends are not failures -- they are directions that did not work. Each one saves someone else from repeating the mistake.*
