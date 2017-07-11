# VarPred
VarPred is a flexible variant annotator written in Python 3 which exploits all features of Pandas library (http://pandas.pydata.org/). VarPred efficiently annotates all types of variants including long indels and complex changes for almost all species of which a reference genome and a gene annotation (GTF/GFF) are available. Contrary to other tools, which works on preprocessed cached-files, VarPred runs directly on source files of the various databases (DB) available for annotations, such as allele frequencies DBs (dbSNP, ExAC, ESP6500) or other variant DBs (COSMIC, Clinvar), allowing not only an always updated annotations, but also a customized selection of DB versions used for the processing.
