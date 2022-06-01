# hello-world
This is my GitHub tutorial for BIMM143.
I am a student in BIMM143 and a senior at UCSD studying Molecular and Cell Biology with a Math minor.

**This is my GitHub tutorial assignment.**

## There are a couple files needed for the first draft of Project 2:
1) Project 2C Lydia Chen.Rmd contains the R Notebook with all of the code and comments for this project
2) Project-2C-Lydia-Chen.html is the knitted HTML file of the above Project 2C Lydia Chen.Rmd
3) FOXO3_species.fasta is a fasta file that contains the amino acid sequence of human, mouse, pig, and chimpanzee FOXO3 as obtained through the Uniprot database. This is used in order to run multiple sequence alignment.
4) 2uzk.fasta is a fasta file that contains the amino acid sequence of the DNA binding domain of human FOXO3. This is used for homology modeling in conjunction with the corresponding pdb file for the read.fasta.pdb() function, in order to visualize PyMol structures in R.
5) FOXO3_species_limited.fasta is a fasta file that contains the amino acid sequence of the DNA binding domain of mouse, pig, and chimpanzee FOXO3. It is again used for homology modeling in conjunction with the corresponding pdb files for the read.fasta.pdb() function for visualizing PyMol structures in R.
6) FOXO3_mouse.pdb is a pdb file containing the structure of the DNA binding domain of mouse FOXO3, as predicted through SWISS-MODEL using human FOXO3 DNA binding domain as the template. This is used to visualize PyMol structures in R with the read.fasta.pdb() function in conjunction with the fasta file above.
7) FOXO3_pig.pdb is a pdb file containing the structure of the DNA binding domain of pig FOXO3. It was obtained and is used for similar purposes as FOXO3_mouse.pdb.
8) FOXO3_chimpanzee.pdb is a pdb file containing the structure of the DNA binding domain of chimpanzee FOXO3. It was obtained and is used for similar purposes as FOXO3_mouse.pdb and FOXO3_pig.pdb.
9) 2UZK.pdb is a pdb file containing the structure of the DNA binding domain of human FOXO3. It was directly downloaded from the PDB database (accession number 2UZK), and is used for similar purposes as the other pdb files.

## Scientific question
Are the amino acid sequences and thus the structure of the DNA binding domain of the human FOXO3 gene more than 70% identical to the FOXO3 gene in mice, pigs, and chimpanzees?

## Scientific hypothesis
If FOXO3's DNA binding domain is highly conserved across humans, mice, pigs, and chimpanzees, then we expect the human FOXO3 protein sequence to be more than 70% similar to FOXO3 in other species, and the structure of the DNA-binding domain to not be affected by differences in sequence.
