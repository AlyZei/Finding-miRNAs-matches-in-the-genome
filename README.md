# Finding-miRNAs-matches-in-the-genome
Based on the assignment designed by François Major from the Université de Montréal

This program takes as inputs:
1. A list of miRNAs fasta sequences
2. A list of kmers
3. A seed length for the miRNAs

Based on the Gale-Shapley algorithm, it outputs a list of indexes of best matches, by comparing the miR reverse sequence to the kmer sequence. It allows the user to hypothesize targets of miRs in the genome and thus narrow down the potential function of the specific miR.

Example of inputs: see files kmers_simple.tsv and mirnas_simple.fa

Example of outputs: see file output_MiRMatching_mirnas_simple_kmers_simple_4
