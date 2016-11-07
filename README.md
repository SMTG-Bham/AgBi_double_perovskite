# AgBi Double Perovskite

Repository for paper: Can Pb-Free Halide Double Perovskites Support High-Efficiency Solar Cells?

DOI: [10.1021/acsenergylett.6b00471](http://pubs.acs.org/doi/abs/10.1021/acsenergylett.6b00471)

Optimised crystal structures of Cs<sub>2</sub>AgBiX<sub>6</sub> (X = Cl, Br, I) from density functional theory, calculated using the Vienna *Ab initio* Package (VASP).

Computational Details
-----------------------
The crystal structures of Cs<sub>2</sub>AgBiCl<sub>6</sub> and Cs<sub>2</sub>AgBiBr<sub>6</sub> obtained by McClure et al.<sup>1</sup> were used as the starting point for the calculations.

The stuctures were optimised using the PBEsol functional.
The final structures have been obtained following an iterative procedure where the ion positions, cell shape, and cell volume are allowed to change (`ISIF = 3` in VASP) using a Quasi-Newton algorithm.

Requirements
------
To open the .cif file, a viewer such as [VESTA](http://jp-minerals.org/vesta/en/).
To run the `POSCAR` file: a VASP license, and suitable input `INCAR`, `KPOINTS`, and `POTCAR` files.

Disclaimer
------
This file is not affiliated with VASP. Feel free to use and modify, but do so at your own risk.

References
-------
1. E. T. McClure, M. R. Ball, W. Windl‡, and P. M. Woodward, Cs<sub>2</sub>AgBiX<sub>6</sub> (X = Br, Cl): New Visible Light Absorbing, Lead-Free Halide Perovskite Semiconductors, *Chem. Mater.*, **28**, 1348–1354 (2016) doi: [10.1021/acsenergylett.6b00471](http://pubs.acs.org/doi/abs/10.1021/acsenergylett.6b00471)
