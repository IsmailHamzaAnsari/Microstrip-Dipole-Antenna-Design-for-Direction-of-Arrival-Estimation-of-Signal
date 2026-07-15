# Microstrip-Dipole-Antenna-Design-for-Direction-of-Arrival-Estimation-of-Signal
# Microstrip Dipole Antenna for DOA Estimation (2.4 GHz)

A half-wave microstrip dipole antenna (MDA) designed on FR4 substrate 
for direction-of-arrival (DOA) estimation. The antenna's radiation 
pattern dependence on θ and φ makes it usable as a simpler alternative 
to conventional smart-antenna arrays for DOA sensing. Designed and 
optimized in CST Studio Suite, fabricated, and experimentally validated.

## Design Approach
- Half-wave (λ/2) microstrip dipole, center-fed, on FR4 (εr = 4.4, 
  h = 1.6 mm) substrate
- Feed line and gap dimensions optimized via analytical relations and 
  parametric ('hit and trial') sweeps to match the dipole's radiation 
  resistance to the microstrip feed impedance
- Parametric study across dipole lengths of 13.5 mm, 14.5 mm, and 
  15.5 mm to observe resonance shift, validating L = λ/2 = v/2f
- Smith chart analysis used to confirm impedance matching within the 
  VSWR = 2 circle around resonance

**Final geometry:** dipole length Lp = 14.64 mm, width Lw = 1.38 mm, 
feed length Lf = 7.94 mm, feed gap Gf = 0.31 mm, substrate 17.26 × 
37.88 mm.

## Results

| Parameter | Simulated / Measured |
|---|---|
| Resonant frequency | 2.4 GHz |
| \|S11\| | -27.2 dB |
| VSWR | < 2 |
| Directivity | 1.98 dBi |
| Gain | 1.88 dBi |
| Radiation efficiency | 96.8% |
| HPBW | 85.66° |
| Main lobe direction | ~180° |
| Front-to-back ratio | 0.032 |
| Polarization | Linear |

The fabricated prototype was measured on a Rohde & Schwarz ZVH cable 
and antenna analyzer; the measured reflection coefficient closely 
matched the CST simulation, validating the design methodology.

## Repository Contents
- `Geometrical_layout_of_the_proposed_antenna.png` - Layout of Proposed Antenna
- `Prototype_of_fabricated_MDA.png` - Image of prototype
- `Reflection_coeffcient_for_different_length_of_MDA_Simulated.png` - Simulated |S11| vs frequency
- `Smith_impedance_plot_of_different_length_MDA_Simulated.png` - Smith impedance plot at resonance for different length.
- `Simulated_reflection_coeffcient_plot_of_proposed_MDA_at_2.4_GHz.png` - Simulated |S11| vs frequency.
- `Smith_impedance_plot_of_MDA_at_2.4_GHz.png` - Smith impedance plot at resonance (2.4 GHz)
- `radiation_pattern.png` — E- and H-plane polar radiation pattern
- `Measured_reflection_coeffcient_plot_of_fabricated_MDA.png` - Measured |S11| vs frequency
- `paper/` — accepted manuscript (author copy)

## Publication
P. S. Rathore, S. K. Jain, A. Jain, I. H. Ansari, "Microstrip Dipole 
Antenna Design for Direction of Arrival Estimation of Signal," 
4th IEEE Wireless, Antenna and Microwave Symposium (WAMS 2025), 
IIITD&M Kancheepuram, Chennai, June 5-8, 2025.

**DOI:** [10.1109/WAMS64402.2025.11157973](https://doi.org/10.1109/WAMS64402.2025.11157973)

## Author
Ismail Hamza Ansari
