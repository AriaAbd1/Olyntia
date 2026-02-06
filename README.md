# Olyntia

Olyntia is an in-progress hardware project focused on designng and validating a low-noise current measurement system from scratch, inspired by the nanopore sensing lab instrumentation by Oxford Nanopore Technologies.

## Overview
The project is centered around an analog front-end design, PCB-based input signal conditioning, and using microcontroller-based data acquisitiion to resolve small current changes under under controlled test conditions.

This repository documents the system architecture, design decisions, and experimental validation work as the project matures.

## Current Status
- Analog front-end design: in progess
- PCB design: initial revision completed
- Data acquisition: basic logging implemented
- Experimental validation: basedline characterization underway

## System Architecture
- Biasing and sensing electrodes
- Transimpedance amplifier and noise filtering stage
- ADC-based data acquisition
- Python-based data post-processing

## What is it?
- A hardware project focused on measuring very small electrical currents
- Converts tiny input currents into measurable voltages using analog circuitry
- Uses low-noise amplification and filtering to reduce drift and noise
- Digitizes the conditioned signal using an ADC for logging and analysis
- Emphasizes measurement stability, repeatability, and noise behaviour

## Repository Structure
- `/hardware` - schematics, PCB files, and renders
- `/firmware` - data acquisition code
- `/test` - measurement data and analysis
- `/docs` - design decisions and limitations
- `/photos` - setup and prototype images

## Next Milestones (Target: March 2026)
- Stable baseline current over extended runs
- Measurable response to controlled current perturbations
- Documented noise performance and bandwidth limits
