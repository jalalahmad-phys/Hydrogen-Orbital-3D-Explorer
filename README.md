# Hydrogen-Orbital-3D-Explorer
Interactive 3D visualization of hydrogen atom orbitals (s, p, d, f) in Jupyter using only NumPy, Matplotlib and ipywidgets
An interactive Jupyter tool that draws the 3D shapes of hydrogen orbitals. Use the n, l and m sliders to change the quantum numbers and the orbital updates live, either as a textbook-style boundary surface, as a probability cloud that shows radial nodes, or both side by side.
##Features
Based on the hydrogen wavefunctions in Griffiths, Introduction to Quantum Mechanics, Eq. 4.89
Associated Laguerre and Legendre functions written from scratch, so there is no SciPy dependency
Real orbitals (p_x, p_y, p_z, d_xy, d_z² and so on)
Colours show the sign of the wavefunction: gold/magenta for ψ > 0, cyan/blue for ψ < 0
Sliders only allow valid quantum number combinations (l ≤ n−1, |m| ≤ l)
Elevation and azimuth sliders for rotating the view
##Requirements: numpy, matplotlib, ipywidgets
##Usage: open Jupyter, paste or %run orbital_3d_explorer.py, and move the sliders.
