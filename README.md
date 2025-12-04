# Hydrogen-Atom-Orbital-Explorer
A visual and interactive computational chemistry tool designed to help students and educatotrs to explore the orbitals of the hydrogen atom using quantum mechanics.
This project visualizes the shapes, probabilities and quantum numbers of atomic orbitals using 3D visualization and mathematical computation.

## Overview
The Hydrogen Atom orbital expplorer simulates the quantum wavefunctions of the hydrogen atom- solutions of the Schrodinger equation and renders the corresponding orbital shapes.
It provides intuitive viosual understanding of:
- Quantum Numbers (n,l,m)
- Orbital probability densities
- Angular and radial wavefunctions
- 3D plots of s, p, d, f orbitals
- Interactive Rotation and zoom

## Features

## Quantum Visualization
- Render orbitals using real spherical harmonics
- Display electron probability densities
- Visualize nodal surfaces
## Mathematical Computation
- Use exact hydrogen wavefunctions:
 - Radial wavefunction
 - Angular wavefunction 
## Interactive Controls
- Select values of n, l, m
- Toggle between:
   - Probability density plots
   - Isosurface models
   - 2D cross-sections
## Educational Mode
- Built-in explanations for each orbital
- Color-coded probability regions
- Tips and therory side panel

## Theory Behind this Project

Hydrogen orbitals are solutions of Schrodinger's equation:
     Ψn,l,m​(r,θ,ϕ)=Rn,l​(r)Yl,m​(θ,ϕ)
Where:
 - n - Principle quantum number
 - l - Azimuthal quantum number
 - m - Magnetic quantum number
This explorer calculates and visualizes these wavefunctions to show electron probabilty density:
      ∣Ψ∣^2=∣Rn,l​∣^2∣Yl,m​∣^2

## Technologies Used

 - Python
 - Numpy
 - Scipy
 - Matplotlib
 - Visual Studio Code

## Installation
git clone https://github.com/yourusername/Hydrogen-Atom-Orbital-Explorer
cd Hydrogen-Atom-Orbital-Explorer
pip install -r requirements.txt

## Contributors
- Aadra Khattri
- Naincy Chandra

