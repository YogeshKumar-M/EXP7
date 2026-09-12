# EXP7
## CHARACTERISTICS OF DIRECTIONAL COUPLER

## AIM:
To study a microwave directional coupler and to determine its coupling factor, insertion loss, isolation and directivity.

## EQUIPMENT AND COMPONENTS
1 Klystron power supply. 
2 Klystron tube (2K25) with mount. 
3 Isolator. 
4 Frequency meter. 
5 Variable attenuator. 
6 Directional coupler (device under test).
7 Two detector mounts.
8 Matched termination. 
9 VSWR meter. 
10 Waveguide stands.

## EXPERIMENTAL SETUP

<img width="1056" height="327" alt="image" src="https://github.com/user-attachments/assets/b13111af-da3d-46b8-9e62-bf9dd2f47475" />

## THEORY

A directional coupler is a four–port waveguide junction consisting of a primary (main) waveguide and a secondary (auxiliary) waveguide coupled to it through one or more small apertures. In a typical two–hole (Bethe–hole type) coupler, the coupling holes are spaced a quarter of a guide wavelength apart, so that the waves coupled through the two holes add constructively in the forward direction of the secondary guide and cancel in the reverse direction. This gives the device its directional property: power injected at the input port mainly couples into the secondary guide travelling toward the “coupled” port, while very little couples toward the “isolated” port. The four ports of a directional coupler are usually identified as: the input port, the transmitted (through) port on the main line, the coupled port on the secondary line (in the forward direction), and the isolated port on the secondary line (in the reverse direction, ideally carrying no power). For a two–hole coupler the holes are separated by s = λg/4, where λg is the guide wavelength at the operating frequency; this quarter–wave spacing is what makes the two coupled contributions add in the forward direction and cancel in the reverse direction.
All readings in this experiment are taken directly in dB on a calibrated VSWR meter, which uses a square–law crystal detector followed by a logarithmic amplifier; hence the meter reading is already proportional to power in dB and no separate detector–law correction is required for the calculations below.
The performance of a directional coupler is described by the following parameters, all expressed in decibels: the coupling factor, which is the ratio of the input power to the coupled power; the insertion loss, the ratio of input power to the power delivered at the through port; the isolation, the ratio of input power to the power leaking to the isolated port; and the directivity, the ratio of the coupled power to the power at the isolated port, which is a measure of how well the coupler distinguishes the direction of the travelling wave.

## CIRCUIT / PORT DIAGRAM
<img width="780" height="337" alt="image" src="https://github.com/user-attachments/assets/f39c33af-dc07-4a79-9a79-ba039695d4df" />

## PROCEDURE
1. The bench is set up as in Fig. 1 with the klystron tuned to give a stable output at the working frequency.
2. With the directional coupler removed, the detector is connected directly after the variable attenuator and the incident power Pi is noted on the VSWR meter.
3. Coupling factor: the coupler is inserted, the through port is terminated in a matched load, the isolated port is also terminated, and the detector is connected to the coupled port; the reading Pc is noted.
4.  Insertion loss: with the coupled port terminated in a matched load, the detector is connected to the through port and the transmitted power Pt is noted.
5.   Isolation / Directivity: the input and through connections are interchanged (power fed from the opposite end / through port terminated appropriately) so that power now travels toward the isolated port; the detector reading Piso at the isolated port is noted with the coupled port similarly excited for comparison.
6.   All readings are recorded in dB (or converted to power) and used to compute the four parameters using the formulae below.

## PROCEDURE FLOWCHART
<img width="1117" height="555" alt="image" src="https://github.com/user-attachments/assets/80758d97-ed3f-4f5a-b90e-8ee42cfcf98d" />

## TABULATION
<img width="1053" height="235" alt="image" src="https://github.com/user-attachments/assets/5a609cba-038c-4caf-969c-1a3474b441a8" />

## FORMULA
1. Coupling Factor, C = Pi – Pc = 10 log10 (Pi / Pc) dB
2. Insertion Loss, IL = Pi – Pt = 10 log10 (Pi / Pt) dB
3. Isolation, I = Pi – Piso = 10 log10 (Pi / Piso) dB
4. Directivity, D = I – C dB

## MODEL GRAPH AND ACTUAL GRAPH

<img width="1050" height="417" alt="image" src="https://github.com/user-attachments/assets/078ef7f9-00a3-4197-97b5-5903a54477f5" />

## CALCULATION
1. Using the average readings (Pi taken as the 0 dB reference):
2. C = 0.0 – (–19.9) = 19.9 dB
3. IL = 0.0 – (–1.05) = 1.05 dB
4. I = 0.0 – (–31.75) = 31.75 dB
5.D = I – C = 31.75 – 19.9 = 11.85 dB

## RESULT / CONCLUSION
The characteristics of the given microwave directional coupler were measured. Coupling Factor C = 19.9 dB (close to its rated 20 dB coupling), Insertion Loss IL = 1.05 dB, Isolation I = 31.75 dB, and Directivity D = 11.85 dB, values that are consistent with a typical two–hole X–band waveguide directional coupler.
