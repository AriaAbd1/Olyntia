# Design Decisions

## Current Measurement Approach
- A transimpedance amplifier was selected to conver small input currents into measurable voltages 
- High-value feedback resistor was picked to increase sensitivity while avoiding output saturation

## Noise and Stability
- Added feedback capacitance to improve stability and reduce high-frequency noise
- Bandwidth intentionally liited to prioritize baseline stability over fast response
- Several decoupling capacitors were added to add signal integrity to components

## Power and Biasing
- Biasing network chosen to provide a stable operating point for current measurements
- Supply and refrence choices guided by noise considerations over power efficiency
