# Energy Output & Performance

## Power in the Wind

The power available in wind is:

```
P = 0.5 × ρ × A × v³
```

Where:
- `ρ` = air density (~1.225 kg/m³ at sea level)
- `A` = rotor swept area (π × r²)
- `v` = wind speed (m/s)

**Key insight**: power scales with the cube of wind speed — doubling wind speed multiplies available power by 8×.

## Annual Energy Production (AEP)

```
AEP = Capacity Factor × Rated Power × 8760 hours
```

Example: 5 MW turbine, 40% capacity factor → AEP ≈ 17,500 MWh/year

## Wind Resource Assessment

- **Wind speed distribution**: modeled with Weibull distribution (shape k, scale c)
- **Wind shear**: wind speed increases with height — tower height matters
- **Turbulence intensity**: affects fatigue loads and energy yield
- **Wake modeling**: accounts for losses within a wind farm

## Influence of Site on Output

| Factor | Impact |
|--------|--------|
| Mean wind speed | Dominant factor — small increase has large effect (cubic relationship) |
| Air density | Higher altitude = lower density = less power |
| Turbulence | Reduces energy capture, increases mechanical fatigue |
| Icing | Reduces output; blade heating systems mitigate in cold climates |

## Grid Integration

- Wind output is variable — grids require balancing (storage, flexible generation, interconnection)
- Power factor correction and reactive power control required
- Voltage ride-through: modern turbines must stay connected during grid faults
- Frequency response: newer turbines can provide synthetic inertia

## Levelized Cost of Energy (LCOE)

LCOE combines capital cost, O&M, and lifetime energy production into a single $/MWh figure.

- Onshore wind: ~25–50 $/MWh (2024, varies by region)
- Offshore wind: ~60–100 $/MWh (declining rapidly)
- Wind is now one of the cheapest sources of new electricity generation globally.
