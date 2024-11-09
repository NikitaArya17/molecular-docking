# Molecular Docking


Molecular Docking is a computational method that allows researchers to predict interactions between two molecules, in this case, a protein and a ligand. The method can be used to predict the binding affinity of ligands for their respective receptor proteins.

AutoDock is a popular software tool that can be used to perform molecular docking. It is relatively easy to use and can predict how drugs bind to the 3D molecular structures of their target receptors.

For this example, aspirin was the drug in question, while the soluble acetylcholine receptor found in *Aplysia californica* was its receptor.

The relevant files were obtained from the [Protein Data Bank](https://www.rcsb.org/structure/5AIN) and the [PubChem database](https://pubchem.ncbi.nlm.nih.gov/compound/2244#section=3D-Conformer).

The software used may be downloaded from the following links:

* [UCSF ChimeraX](https://www.cgl.ucsf.edu/chimerax/)
* [MGLTools](https://ccsb.scripps.edu/mgltools/)
* [AutoDock Vina](https://vina.scripps.edu/)
* [Cygwin](https://www.cygwin.com/)


The coordinates of the 3D molecular structure of aspirin was downloaded from the PubChem database in the SDF (Structured Data File) format. This is a file format that stores information about the positions of each individual atom in a molecule. The ChimeraX software was then used to convert this file to a PDB (Protein Data Bank) file. Both of these files were then converted to the PDBQT (Protein Data Bank, Partial Charge (Q), & Atom Type (T)) format. This format stores information about the partial charges on the atoms that make up the molecule.

These files have been stored in the 'intermediate_files' folder.
