# Wind Turbine Agent — Knowledge Summary

This document summarizes the structured knowledge base in `knowledge/`. Use it as a quick reference or as a system-prompt context for an AI agent.

---

## 1. Fundamentals (`01-fundamentals.md`)

- Wind turbines convert kinetic wind energy to electricity via rotating blades and a generator.
- Main types: **HAWT** (horizontal axis, dominant) and **VAWT** (vertical axis).
- Scale ranges from micro (<100 kW) to offshore utility-scale (5–20 MW).
- Key metric: **capacity factor** — actual output / theoretical max. Onshore: 25–40%, Offshore: 40–60%.

---

## 2. Components (`02-components.md`)

- **Blades**: 3-blade airfoil design, 50–120 m, fiberglass or carbon fiber. Pitch-controlled.
- **Nacelle**: houses gearbox (or direct-drive), generator, yaw system, brakes.
- **Tower**: 80–160 m tubular steel. Taller = more energy.
- **Foundation**: onshore (concrete), offshore fixed (monopile, jacket), offshore floating (spar, semi-sub).
- **Electrical**: power converter, transformer, SCADA for remote monitoring and control.

---

## 3. Aerodynamics (`03-aerodynamics.md`)

- Blades generate **lift** (drives rotation) and **drag** (opposes rotation).
- **Betz limit**: max 59.3% of wind energy can be extracted. Modern turbines achieve ~45–50%.
- **Tip Speed Ratio (TSR)**: optimal ~7–8 for 3-blade turbines.
- **Pitch control**: adjusts blade angle to optimize output below rated speed; limits output above.
- **Power curve**: cut-in ~3 m/s, rated ~12–15 m/s, cut-out ~25 m/s.
- **Wake effect**: downstream turbines get slower, turbulent wind — 5–20% farm-level losses.

---

## 4. Operations & Maintenance (`04-operations-maintenance.md`)

- O&M = 20–30% of LCOE. Major focus for cost reduction.
- Maintenance modes: **preventive** (scheduled), **corrective** (reactive), **condition-based**, **predictive** (ML-driven).
- Top failure modes: gearbox bearings, blade erosion, generator bearings, pitch/yaw actuators.
- Blade inspection: visual, drone, thermography, acoustic emission.
- **SCADA** collects thousands of signals; anomaly detection flags early failures.
- Typical availability: 95–98% onshore, 90–95% offshore.

---

## 5. Energy Output & Performance (`05-energy-output.md`)

- Power in wind: `P = 0.5 × ρ × A × v³` — cubic dependence on wind speed.
- **AEP** = Capacity Factor × Rated Power × 8760 h.
- Wind resource: Weibull distribution, wind shear, turbulence intensity, wake losses.
- **LCOE** (2024): onshore ~25–50 $/MWh, offshore ~60–100 $/MWh. Wind is among cheapest new generation sources.
- Grid integration: variable output requires balancing; modern turbines provide reactive power and synthetic inertia.

---

## Knowledge Gaps (to fill over time)

- [ ] Wind farm siting and permitting
- [ ] Offshore installation methods
- [ ] Control systems and advanced pitch/torque strategies
- [ ] Structural loads and fatigue analysis
- [ ] Repowering and end-of-life considerations
- [ ] Market and regulatory landscape
