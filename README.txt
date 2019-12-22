Ayca Begum Tascioglu

To run the code:

1) Please go to the directory of where source code(buildUPGMA.py) located.
 
2) Add sequence file that you want to use, in the same file with the source code.

3) After, in the terminal go to the directory where buildUPGMA.py and desired input files( i.e sequences.fasta) are located.

4) type 'make'.
	>>make
	python buildUPGMA.py program.dat

5) after you see the program compiled, write the parameters as given in the assignment. 
Example:
	>>buildUPGMA --fasta sequences.fasta --match 5 --mismatch -3 --gapopen -8 --gapext -1 --out sequences.tree

6)The program will create the out file with given name, saves the computed tree in Newick format.


