# ORF-finder

This is the open reading frame (ORF) finder. 

It finds ORF of required length (can be given as an input by the user) in the positive strand of a nucleotide sequence.
It splits the file into individual sequences and find all possible ORFs in that sequence. 

ORF: It is a protein-coding nucleotide sequence. It starts with a start codon ATG, followed by a stretch of codons,
and ends with stop codons TAA, TGA, TAG. 

Input: FASTA file containing single or multiple nucleotide sequences 

Output: ORF's nucleotide sequence, their length and offsets, and ORFs per frame. 






