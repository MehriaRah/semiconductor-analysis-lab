# semiconductor-analysis-lab
Analysis of Silicon (1N4148) and Germanium (AA138) diode characteristics, featuring experimental V-I curve plotting, parameter extraction, and ripple factor analysis in half-wave and full-wave rectifier circuits.

# Diode Characteristics and Rectifier Circuits Analysis

## Project Overview
This project is a comprehensive study of semiconductor diode behavior, conducted as part of the Electronics I Laboratory at HAW Hamburg. It covers the transition from theoretical modeling to practical circuit implementation and measurement.

## Key Objectives
* **Comparative Analysis:** Evaluating the differences between Silicon (1N4148) and Germanium (AA138) diodes.
* **Parameter Extraction:** Calculating the ideality factor ($n$), reverse saturation current ($I_S$), and bulk resistance ($R_B$) using semilogarithmic plots.
* **Power Electronics:** Designing and testing half-wave and full-wave bridge rectifiers.
* **Signal Conditioning:** Measuring the impact of smoothing capacitors on the Ripple Factor.

## Technical Specifications
| Component | Type | Key Observation |
| :--- | :--- | :--- |
| **1N4148** | Silicon | Higher threshold voltage (~0.6V - 0.7V) |
| **AA138** | Germanium | Lower threshold voltage (~0.2V - 0.3V) |
| **Rectifiers** | Bridge | Full-wave rectification analyzed at 1kHz |

## Methodology & Tools
- **Hardware:** Oscilloscope (X-Y mode), Signal Generator, Differential Probes.
- **Components:** 1N4148 Diodes, AA138 Diodes, various Capacitors (47nF, 470nF), $10k\Omega$ resistors.
- **Theory:** Application of the Shockley Diode Equation:
  $$I = I_S (e^{\frac{V_D}{n V_T}} - 1)$$

## Results Summary
- Successfully plotted the V-I characteristics showing the exponential current rise.
- Verified that full-wave rectifiers significantly reduce ripple compared to half-wave versions.
- Observed the inverse relationship between filter capacitance ($C_L$) and output voltage ripple.


<img width="1376" height="2048" alt="WhatsApp Image 2026-05-08 at 17 15 46" src="https://github.com/user-attachments/assets/2deb9ee4-4913-4fa1-826f-8449b79a55d3" />
<img width="2048" height="963" alt="WhatsApp Image 2026-05-08 at 17 16 22" src="https://github.com/user-attachments/assets/3e27e189-37fa-47aa-8822-6d8ecc0ba7ff" />

