# Local_docking
Acquired environment
1. All steps required python 3 for MDanalysis, Vina, Pandas,Numpy, Matplotlib...
2. converting files can be pain in the ass since Vina only recognize pdbqt files, and PLI package requires sdf & pdb files, so below are a few tips:
   - for ligand to sdf files, ligand can be conveted through obabel: install openbible or python version(pybel), can be done on pyton 3
     (if you are lacking atom names in your pdb files which print out error while converting, load it in to pymol and save it out without touching anything or the position will change)
   - For converting DNA & protein requires python 2.7 for bioconda to install python version of MGLTools (to assign Autodock Vina force fields...)
   - or download MGLTools(./adt in linux) and convert
3. inport PLI
Process:
1. Obtain your known protein combined with ligand or DNA
2. Get seperate files of only protein and ligand/DNA from MDanalysis
3. 
