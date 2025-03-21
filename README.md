# Satellite Attitude Control System

This repository contains MATLAB code and Simulink models for analyzing and designing a satellite attitude control system.

![Root Locus](Satellite%20Attitude%20Controller/Blocks.jpg)

## Features
- **Step Response Analysis**: Visualize the system's time-domain behavior.
- **Bode Plot Analysis**: Frequency response of the system.
- **Root Locus Analysis**: Stability and control design insights.

## Files
- `Code.m`: MATLAB script for transfer function definitions and control analysis.
- `Blocks.slx`: Simulink model for the control system.
- Images: Visualizations of step responses, Bode plots, and root locus diagrams.

## Usage
1. Open `Code.m` in MATLAB to run the analysis.
2. Use `Blocks.slx` in Simulink for model-based simulations.

## Visualizations
### Step Responses
<div style="display: flex; justify-content: space-around; align-items: center; width: 50%;">

<div style="text-align: center;">
<h4>Step Response Satellite</h4>
<img src="Satellite%20Attitude%20Controller/S%20Step%20Response.jpg" alt="Step Response (S)">
</div>

<div style="text-align: center;">
<h4>Step Response DC Motor</h4>
<img src="Satellite%20Attitude%20Controller/M%20Step%20Response.jpg" alt="Step Response (M)">
</div>

</div>

### Bode Plot
<div style="display: flex; justify-content: space-around; align-items: center; width: 50%;">

<div style="text-align: center;">
<h4>Bode Plot Satellite</h4>
<img src="Satellite%20Attitude%20Controller/margin(S).jpg" alt="Bode Plot (S)">
</div>

<div style="text-align: center;">
<h4>Bode Plot DC Motor</h4>
<img src="Satellite%20Attitude%20Controller/margin(M).jpg" alt="Bode Plot (M)">
</div>

</div>

### Root Locus
<div style="display: flex; justify-content: space-around; align-items: center; width: 50%;">

<div style="text-align: center;">
<h4>Root Locus Satellite</h4>
<img src="Satellite%20Attitude%20Controller/rlocus(S).jpg" alt="Root Locus (S)">
</div>

<div style="text-align: center;">
<h4>Root Locus DC Motor</h4>
<img src="Satellite%20Attitude%20Controller/rlocus(M).jpg" alt="Root Locus (M)">
</div>

</div>


