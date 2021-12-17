STEPS INVOLVED

1. scf calculation
2. nscf calculation
3. DOS calculation
4. plot DOS

SCF

- use celldm(1) as calculated from the previous variation of cell calculation

- conv_thr and ecutwfc are decreased for more precision

- k points are increased to 8, more precision, less time spent because it is only scf calculation

NSCF 

- occupations = 'tetrahedra' more appropriate for DOS calculations

- increased k points for refining previous calculation

DOS

- plotted from -9 to 16 eV