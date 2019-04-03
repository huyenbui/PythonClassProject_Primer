# PythonClassProject_Primer
Extract a reference gene sequence and incorporate strain-specific SNP for primer design 

# To do:
  - Get a mini gff and a mini vcf
  - parse the gff using Biopython
  - take input gene name, locate the beginning and the ending coordinates
  - take input of the length of upstream and downstream fragment you want to include
  - parse the vcf using Biopython, fetch SNPs' coordinates and alternative nucleotides
  - "transform the coordinate" and replace the reference base with the alternative base, use lower case to mark the replaced bases
  - check the file format if it is 0-based ot 1-based
  - write out the strain-specific version of the gene, which can be input into Primer3
  - Need: find ways to mark/output indels
