# Molecular-dynamics-with-NAMD
Perform molecular dynamics experiments (MD) with NAMD on colab

instructions:

1. utilize VMD on desktop or with the file 'VMD_colab' to:\
a. generate the new pdb file of the protein containing hydrogens atom, and the psf associate file.\
b. solvate the protein in a water sphere. A new pdb and psf files are generate. 

2. open 'Run_simulation_NAMD' file on colab to perform minimization, equilibration and run of the system.\
If you just have your final pdb and psf files, you can directly use this module for your MD simulation. To perform it, you must unpload on your drive (and mount it on colab worksheet) psf and pdb files of your solvate protein and run the final code line.

3. Analyze data using 'data_analysis' file on colab to calculate rmsd, residue rmsd and others.
