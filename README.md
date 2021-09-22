# MMP1
Structure and parameter data for simulations of MMP1 using the Amber 14sb force field and made compatible for the Gromacs software suite. 

POSE1, POSE2, POSE3, POSE3_MUTANT - Gromacs coordinate and topology parameter files, including new amino acid side chain force constant and charge data. All force field information is contained in each .itp file (per pose). Each system.top needs to be linked to the corresponding .itp file before using grompp. 

ATOMIC_CHARGES - atomic charges for each pose generated using Amber's MCPB.py. The charges eventually make their way into the Gromacs .itp file. 

QM_CALCULATIONS - GAMESS-US log files of the QM calculations for each metal binding site. 


![MMP1](https://user-images.githubusercontent.com/20614766/134327240-68e13139-79a5-4794-abdf-0fac041ceb5d.jpeg)
