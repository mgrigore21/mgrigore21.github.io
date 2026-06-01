---
layout: post
title: "Wind Physics & Energy Content"
date: 2026-05-21
---

Understanding how much energy the wind actually carries — and why that number changes so dramatically with speed, height, and terrain — is the foundation of everything in wind energy. Before looking at turbine design or economics, the physics has to be clear.

---

## The Power Equation

The power available in a stream of wind is:

```
P = ½ × ρ × A × v³
```

Where:
- **P** — power in watts
- **ρ** (rho) — air density in kg/m³
- **A** — rotor swept area in m² (the circle traced by the blade tips)
- **v** — wind speed in m/s

Two things stand out immediately.

**Power scales with the cube of wind speed.** Doubling the wind speed doesn't double the available power — it multiplies it by eight (2³ = 8). A site with an average of 9 m/s carries roughly twice the energy of a site averaging 7 m/s, not 30% more. This is why choosing a good site matters more than almost any other design decision.

**Power scales with rotor area.** Doubling the rotor diameter quadruples the swept area, and therefore quadruples the available power. This is the main reason turbines keep getting larger — a bigger rotor captures exponentially more energy for a relatively modest increase in cost.

### Air Density Matters Too

| Condition | Air Density |
|-----------|-------------|
| 15°C, sea level | 1.225 kg/m³ |
| 0°C (cold winter air) | 1.293 kg/m³ |
| 30°C (hot summer air) | 1.164 kg/m³ |

Cold air is denser and carries more energy. A turbine in northern Europe in winter operates in noticeably richer wind than the same turbine in a hot desert summer.

---

## The Betz Limit

No turbine can extract all of the energy in the wind. If it slowed the wind to a complete stop, the air would pile up in front of the rotor and stop flowing through — there'd be nothing left to push the blades.

Albert Betz proved in 1919 that the optimum is reached when the turbine slows the wind to exactly **one-third of its incoming speed**. At that point, exactly **16/27 = 59.25%** of the wind's kinetic energy has been extracted. This is the **Betz limit** — an absolute physical ceiling, not a technology limitation.

Real turbines reach a power coefficient (cp) of around **0.45–0.50**, accounting for blade drag, tip losses, and mechanical friction. That is impressively close to the theoretical maximum.

---

## Key Operating Parameters

| Parameter | Typical Value |
|-----------|---------------|
| Cut-in speed (minimum wind to generate power) | 3–5 m/s |
| Rated speed (turbine reaches full output) | 12–15 m/s |
| Cut-out speed (turbine shuts down for safety) | ~25 m/s |
| Survival speed (parked turbine maximum) | 50–60 m/s |

Between cut-in and rated speed, output rises steeply with wind — following the cubic law. Above rated speed, the turbine's control system limits output to protect the machine.

---

## Wind Shear: Why Height Matters

Wind is faster higher up. The ground creates friction that slows the air near the surface, and that effect decreases with altitude. The relationship follows the **logarithmic wind shear law**:

```
v = v_ref × ln(z / z₀) / ln(z_ref / z₀)
```

Where **z₀** is the *roughness length* — a terrain parameter that describes how much the surface slows the wind. Moving from a 50 m to a 100 m hub height at a typical onshore site often yields around 1 m/s extra wind speed. Because of the cubic law, that translates to roughly **30% more power**.

### How Terrain Affects Everything

| Roughness Class | Terrain | Energy Index |
|-----------------|---------|--------------|
| 0 | Open water | 100% |
| 0.5 | Airport runways, mowed grass | 73% |
| 1 | Open farmland | 52% |
| 2 | Farmland with scattered buildings | 39% |
| 3 | Villages, small towns | 24% |
| 4 | Large cities | 13% |

The *energy index* shows the available wind energy relative to open water (100%). A turbine in a city captures only 13% of the energy that an identical turbine would capture over the sea. This is why offshore wind is so attractive — the resource is fundamentally richer — and why taller towers almost always pay for themselves.

---

## Weibull Distribution: Why Average Speed Isn't Enough

Wind speed is not constant. It varies continuously, and the distribution of speeds over a year follows a **Weibull distribution**. This has a critical practical consequence: using the average wind speed to estimate energy production significantly *underestimates* actual output.

Why? Because power scales with v³. Periods of high wind contribute disproportionately to total energy. About **two-thirds of annual energy production** comes from the fastest third of wind speeds.

The Weibull distribution is described by two parameters:
- **Scale parameter (c)** — related to the mean wind speed
- **Shape parameter (k)** — describes how variable the wind is. Higher k means steadier wind; lower k means more gusty and variable conditions.

When k = 2, the distribution is called the **Rayleigh distribution**, which turbine manufacturers use as a standard reference for performance specifications.

> A site with a 7 m/s average might seem modest. But the wind at 11–13 m/s, which occurs a meaningful fraction of the time, generates 5–8× more power than at 7 m/s. A proper Weibull analysis captures this; a simple average does not.

---

## Summary

The physics of wind energy is shaped by a few powerful relationships:

- **Cubic dependence on speed** — small improvements in wind resource yield large gains in output
- **The Betz limit** — 59.25% is the absolute ceiling; good turbines reach 45–50%
- **Logarithmic wind shear** — taller towers access faster, more energetic wind
- **Terrain roughness** — site selection and hub height are among the most important design decisions
- **Weibull statistics** — always model the full distribution, not just the mean

These principles underpin every design and siting decision in the industry. Future posts will build on them to look at how turbines are designed to extract energy as efficiently as the physics allows.
