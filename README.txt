REQUIREMENTS:
Python 3.7.6 64-bit ('base': conda) works best in this version
Installing Anaconda would be preferred, since without it, you have to install some packages.

HOW TO USE:
Step 1: Download this repository and extract it.
Step 2: Replace the "mutants" list with your desired list of mutants.
	Each mutant is its own string, and if you are doing multiple mutations per mutant, separate the mutations with plus (+) signs.
	Each mutation is written in the form of the wild type amino acid 1-letter code, the position, and the 1-letter code for the new amino acid.
	Use the sample "mutants" list as a formatting guide.
Step 3: Place the PDB file of your desired wild-type protein into the same folder in which the mutagenesis.py file is located.
Step 4: Open the mutagenesis.py file to start the program, and when it finishes, you will get an output PDB file for each mutant in your "mutants" list.
You can use this for any protein and for as many mutants and mutations as you want.

NOTE: I added a sample PDB file "tmafc.pdb" and set the "mutants" list to specific examples in this protein. Change these for your own projects.
I am also mutating only the "A" chain of this protein.