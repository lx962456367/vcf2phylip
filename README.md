# vcf2phylip
The script converts a collection of SNPs in VCF format into a PHYLIP, FASTA,  NEXUS, or binary NEXUS file for phylogenetic analysis. The code is optimized to process VCF files with sizes >1GB. For small VCF files the algorithm slows down as the number of taxa increases (but is still fast).
