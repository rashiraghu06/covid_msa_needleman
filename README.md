# covid_msa_needleman

The pseudocode for the algorithm implementation is:

1. Reads the files and converts the files into a single line with just the sequence for
each virus

2. A function for the Needleman-Wunsch algorithm was created that by takes in two
sequences and returning a directions matrix with the movements

3. A function that does pairwise alignment by taking in the directions matrix and the
two sequences, returning the alignments of both sequences, along with a final
alignment which indicates the locations of mismatches and gaps and a percent
identity between the two sequences

4. Determines which strain is which. And calls the Needleman-Wunch and pairwise
for the newly aligned Tor2 strain and the Urbani strain.

5. Combines the final alignments of the two alignments and finds the final
alignment of all the three strains

6. Creates an output file with the newly aligned sequences, a final sequence which
indicates the locations of dissimilarity, and a percent alignment.
