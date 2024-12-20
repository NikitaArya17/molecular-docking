# Molecular Docking


Molecular Docking is a computational method that allows researchers to predict interactions between two molecules, in this case, a protein and a ligand. The method can be used to predict the binding affinity of ligands for their respective receptor proteins.

AutoDock is a popular software tool that can be used to perform molecular docking. It is relatively easy to use and can predict how drugs bind to the 3D molecular structures of their target receptors. It generates several possible binding conformations, or 'poses', between a protein and a ligand, each with a different Gibbs free energy. The Gibbs free energy refers to the energy that is released when two molecules bond with each other. The more negative the value of Gibbs free energy for a chemical reaction, the more spontaneous the reaction will be, and thus, the more likely the occurrence of that reaction will be.

For this example, aspirin was the drug in question, while the soluble acetylcholine receptor found in *Aplysia californica* was its receptor.

The relevant files were obtained from the [Protein Data Bank](https://www.rcsb.org/structure/5AIN) and the [PubChem database](https://pubchem.ncbi.nlm.nih.gov/compound/2244#section=3D-Conformer).

The software used may be downloaded from the following links:

* [UCSF ChimeraX](https://www.cgl.ucsf.edu/chimerax/)
* [MGLTools](https://ccsb.scripps.edu/mgltools/)
* [AutoDock Vina](https://vina.scripps.edu/)
* [Cygwin](https://www.cygwin.com/)


The coordinates of the 3D molecular structure of aspirin was downloaded from the PubChem database in the SDF (Structured Data File) format. This is a file format that stores information about the positions of each individual atom in a molecule. The ChimeraX software was then used to convert this file to a PDB (Protein Data Bank) file. Both of these files were then converted to the PDBQT (Protein Data Bank, Partial Charge (Q), & Atom Type (T)) format with AutoDock. This format stores information about the partial charges on the atoms that make up the molecule.

These files have been stored in the 'intermediate_files' folder.

Separate files containing the grid parameters and docking parameters were also created using AutoDock and have been stored in the 'intermediate_files' folder.

The output and log files contain the results that were written out by the program. They have been stored in the 'output_files' folder.

A text file containing commands has been stored in the 'required_commands' folder. These commands are entered in the Windows Command Prompt.
