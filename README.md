# genescomp
An application to identify polymorphisms in genomic data

This is the initial release of genescomp. It is intended to provided a detailed view of the characteristics of polymorphims, including intron splice site - mutaations, branch site mutations, nonsense, "resense" (loss of stop codon), non-synonymous changes, and eventually structural changes.
This program is written and tested in the Linux, specificly Ubuntu 20.04.

Dependencies:

The code is written in python3, and uses several standard python3 modules.
In addition:
NCBI blast+
EMBOSS (http://emboss.sourceforge.net)
fasta/Smith Waterman (https://fasta.bioch.virginia.edu/fasta_www2/fasta_list2.shtml)

In addition specific information for the species of interest is required.
This information includes species specific information including intron splice site consensus sequences, intron branch site consenus sequences, intron lengths, genetic code, and information on codon usage.
Scripts to generate this data from the .gff3 file will be uploaded soon.

