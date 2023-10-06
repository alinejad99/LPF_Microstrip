# LPF_Microstrip (in HFSS)

In this project, we will simulate a low-pass microstrip filter using Microwave Studio. The substrate parameters are as follows:

Substrate Thickness: 31 mil
Conductor Thickness: 10 µm
Substrate Material: Duroid/RT Rogers 5880
Dimensions:
a = 5 mm
b = 5 mm
g = 0.5 mm
w = 2.4 mm
W = 25.4 mm (substrate width)
L = 32.56 mm (substrate length)
Modal analysis type
Use Analysis Network in the analysis type selection window
Define the solution domain and ports based on provided instructions
Apply radiation boundary conditions on the top, left, and right sides of the solution domain (relative to the microstrip line)
Center frequency for simulation: 8 GHz
Frequency sweep range: 0.1 GHz to 10 GHz
Line impedance: 50 ohms
Note: Enable Fields Save since you need the field profile at frequencies other than the center frequency.

Simulation Steps
Run the simulation.
Plot the frequency domain response of scattering parameters S11 and S21 within the specified frequency range.
Calculate the 3 dB bandwidth of the filter.
Display the field distribution at the port.
Visualize the magnitude of surface current at approximately 300 MHz on the microstrip line and the ground plane.
Plot the electric field magnitude on the ground plane at 300 MHz and observe its dynamics.
Feel free to use the software and tools mentioned in the provided instructions to perform the simulation and analyze the results.
