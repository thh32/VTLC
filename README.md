# VTLC

The Viral Taxonomic Lineage Classification (VTLC) dataset is an attempt to produce and provide a scientific method for identifying if a denovo contig has accuratly been assigned to a taxonomy. VTLC also allows identification as to which level taxonomic level the assignment can be trusted.

The VTLC dataset was created by use of the EGGNOG viral gene families. Eggnog provide pre-defined gene families for viruses, with taxonomic and functional annotations. We used this dataset to create a reference for taxonomic and functional annotation of unknown viral sequences. The procedure used was as follows: 

1) For each viral gene family from EGGNOG, the percentage similarity of every gene to every other in the family was calculated. 

2) For each taxonomic level (species, genus, family, etc..) the average percentage identity of all genes from the same group (i.e. myovirideae ) was calculated. 

3) This provided a reference dataset which allowed us to functionally and taxonomically identify unknown viral sequences.

VTLC is provides only the core dataset for comparison of annotations against. No code for use of the VTLC dataset is provided.
