# asst3_SLE712
Code to support assignment 3 task for unit SLE712

# myscript.sh
myscript.sh is a script to incorporate mismatches with msbar into a sequence and preform a blast search.
formatdb is used to index the nucleotide database which will be formatted for searching. 
-p F (the type of file used is nucleotide)
-o T (Parse options are parse SeqId and create indexes)
Using the msbar the sequence was mutated by changing the mismatch count. 
-point 4 (Types of point mutations to perform are changes)
-block 0 (Type of block mutations are none)
-codon 0 (Type of codon mutations are none)
For each mismatch count, 100 tests were performed by creating a loop and the performance of blast was assessed. 
The mismatch numbers were initially changed and assessed in a working directory which was later inserted to aat3_SLE712.
The change of mismatch count from 155 to 330 showed a gradual drop of blast performance.

# Gene expression

The file includes the codes to assess a .tsv file in RStudio. The codes includes importing a .tsv file to R and calculating and sorting the mean values as well as generate a pairs plot.

# Growth_data.csv

The file includes the codes to assess a .csv file in RStudio. The codes includes importing a csv file to R and calculating the average, standard deviation of the tree circumference at two different sites and to obtain box plots.
