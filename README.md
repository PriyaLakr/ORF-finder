# ORF-finder and Interspersed repeat finder

This is the "open reading frame" (ORF) and "interspersed repeat sequences" finder. 




ORF (https://en.wikipedia.org/wiki/Open_reading_frame): 

It finds ORF of required length (can be given as an input by the user) in the positive strand of a nucleotide sequence.
It splits the file into individual sequences and find all possible ORFs in that sequence. 

ORF: It is a protein-coding nucleotide sequence. It starts with a start codon ATG, followed by a stretch of codons,
and ends with stop codons TAA, TGA, TAG. 

Input: FASTA file containing single or multiple nucleotide sequences 

Output: ORF's nucleotide sequence, their length and offsets, and ORFs per frame. 







Interspersed repeats (https://en.wikipedia.org/wiki/Interspersed_repeat):

It finds repetitive sequences of a particular length or a range of lengths (can be given as an input by the user) in a large string (i.e., nucleotide/genomic sequences).
It splits the file into individual sequences and find all possible interspersed repeats in that sequence. 

Input: FASTA file containing single or multiple nucleotide sequences 

Output: Repeat sequences and their occurence frequencies.







