# Operations & Maintenance

## O&M Cost Overview

O&M accounts for ~20–30% of the levelized cost of energy (LCOE) for wind. Reducing O&M cost is a major focus of the industry.

## Maintenance Types

| Type | Description | Frequency |
|------|-------------|-----------|
| Preventive | Scheduled inspections, lubrication, filter changes | Annual or semi-annual |
| Corrective | Reactive repair after failure | As needed |
| Condition-based | Triggered by sensor data (vibration, temperature, oil) | Continuous monitoring |
| Predictive | ML models forecast failure before it occurs | Continuous |

## Common Failure Modes

- **Gearbox**: bearing wear, gear tooth fatigue — most expensive component failure
- **Blades**: leading edge erosion, lightning strikes, delamination
- **Generator**: bearing failure, insulation breakdown
- **Pitch system**: hydraulic or electric actuator failure
- **Yaw system**: wear in yaw drive or brake

## Blade Inspection Methods

- Visual inspection (ground-level binoculars, drones, rope access)
- Thermography — detects delamination and internal damage
- Acoustic emission — detects cracks
- Automated drone inspection with AI-based defect detection

## SCADA & Remote Monitoring

SCADA systems collect thousands of sensor signals per turbine (every 10 minutes or faster). Key monitored parameters:
- Wind speed and direction
- Rotor speed, generator speed
- Power output, reactive power
- Temperatures: gearbox oil, generator winding, nacelle, ambient
- Vibration levels

Anomaly detection algorithms flag deviations from expected behavior before they become failures.

## Availability

Turbine availability (fraction of time operational) is typically 95–98% for modern onshore turbines. Offshore availability is lower (~90–95%) due to access constraints in bad weather.
