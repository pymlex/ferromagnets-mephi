# Investigation of Ferromagnets in Alternating Magnetic Field

## About
<img width="2997" height="2199" alt="8_1729417917 1264286" src="https://github.com/user-attachments/assets/3e2ad1b1-e25e-4fc3-aa94-8a91f6f83e33" />

This project provides Python code for processing experimental data from Lab Work 8 at the MEPhI Electricity and Magnetism Laboratory, enabling accurate calculations and visualization of ferromagnetic properties in alternating magnetic fields observed in iron rods. Errors are estimated using the [`pyprecision`](https://github.com/gopyc-code/pyprecision) package, and visualizes the results for both long and short rods. The generation of graphs and tables is automated.

## Quantities ObtainedВот ваши формулы, переписанные в LaTeX:

- Magnetic flux density $$ B $$ with uncertainties.
- Magnetic field intensity $$ H $$ with uncertainties.
- Magnetic permeability with uncertainties:

$$ \mu = \frac{B}{\mu_0 H} $$

- Remanent flux density $B_r$ and coercive field $H_c$ from hysteresis loops.
- Saturation flux density $$ B_s $$ and corresponding field $$ H_s $$.
- Hysteresis loop area $$ \sigma $$ and specific energy loss $$ w $$ with uncertainties.
- Power loss $$ P $$ calculated from loop area.

## Visualisations
- **B-H curves** for long and short rods (magnetic flux density vs. field intensity).
- **μ-H curves** showing the dependence of magnetic permeability on the field intensity.
- **Hysteresis loops** for long and short rods, including error bars and spline interpolation.
- Graphical representation of remanence $$ B_r $$, coercive field $$ H_c $$, saturation points $$ B_s $$ and $$ H_s $$, and calculated areas.

## Features
- Error propagation and rounding using the [`pyprecision`](https://github.com/gopyc-code/pyprecision) package.
- Automatic generation of high-resolution graphs and Excel tables.
- Supports analysis of both major magnetization curves and limiting hysteresis loops.
- Uses `scipy` for interpolation and numerical integration.
- Provides reproducible results and automated visual reports.
