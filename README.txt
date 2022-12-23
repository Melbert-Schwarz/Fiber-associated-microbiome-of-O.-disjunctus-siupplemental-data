############
The files included here are raw data associated with the article 
Distribution of microbial populations and digestive enzymes in the wood-feeding beetle Odontotaenius disjunctus (Coleoptera: Passalidae) underscores the importance of wood fibers in the gut as a microhabitat
Melbert Schwarz, Aram Mikaelyan

Affiliations: Department of Entomology and Plant Pathology, North Carolina State University, Raleigh, North Carolina, United States of America.

############


 contains 3 .csv files which were used in the R analysis:
	metadata.csv: includes the metadata associated with the samples. The file can be loaded into R.
	OTU_tab.csv: a file including the full OTU table used in the analysis
	TAX_tab.csv: a file including the taxonomic information (up to the genus level) of OTUs in the file OTU_tab.csv. This file and the OTU_tab.csv file share the first column (i.e OTU)

 also conatins the following files outputed from Mothur:
	Odonto_16S.phyloseq.OTUreps.fasta: Fasta formated file containin the representative sequences of each OTU.
	Odonto_16S.phyloseq.OTUreps.tree: A newick formated phylogeny which was calculated with FastTree (v2.1.3) using the GTR model. This file was used to calculate UniFrac distances. This file can be uploaded into R, incorporated in an analysis with QIIME/Mothur, or opened with any program cabable of opening phylogenetic trees.



 contains 1 file: qpcr analysis_copies_per_DNA.xlsx this file contains raw data outputed from the qPCR and the associated calculations to derive the number of 16S copy numbers.
