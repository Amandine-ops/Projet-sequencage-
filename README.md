# Projet-sequencage-
## Abstrat 08.11.24
Background 

Enterococcus faecium is a gram-positive bacteria of the human gastrointestinal tract. It can affect the bloodstream of hospitalized patients. The study aim is to identify genes useful by the bacteria to grow in human serum. Transcriptome profiling (RNA-seq) and high-throughput transposon mutant library sequencing approach (Tn-seq) are used. 

Results

Firstly, they sequenced the genome of E. faecium E745 by using a combination of short and long read sequencing. This one is a specific bacteria that is vancomycin-resistant. It revealed the presence of 2,765,010 nucleotides in chromosomes and 6 plasmids, with size ranging between 9.3kbp and 223.7 kbp.
Transcriptome has been compared between a rich medium and in human serum thanks to RNA seq. It shows a difference of 27,8% in gene expression between these conditions.
Then by comparing the library, it enabled the lighting up transposon mutant required for growth of the bacteria in serum .
Many genes have been identified as genes involved in de novo nucleotide biosynthesis such as pyrK_2, pyrF, purD, purH… and gene encoding a phosphotransferase system subunit such as manY_2.
The pyrK_2 and manY_2 mutants were tested for their virulence in an intravenous zebrafish infection, showing attenuated effect.


The combination of techniques with short and long read sequences are used. Short-read Illumina sequencing and long-read sequencing on the RSII Pacific Biosciences and Oxford NanoPore’s MinION techniques are used to detect the genes involved in the disease. 

Conclusions

Genes of the carbohydrate metabolism and nucleotide biosynthesis are use by the bacteria to develop in the serum. 
This gene identification allows them to target them for the development of novel anti-infectives against Enterococcus faecium.

## Programs used for the study 
- SPAdes : (version 3.0)
- BWA :(BWA-MEM algorithm ) 
- Celera Assembler: 
- SAMtools : identify bas-calling/assembly errors
- Prokka : sequences corrected 
- ParSNP with settings-c (forcing inclusion of all genome sequences) and-x (enabling recombination detection and filtering)
- MEGA: visualisation of phylogenetic tree 
- FastAQ
- Integrative Genomics Viewer (IGV) 


