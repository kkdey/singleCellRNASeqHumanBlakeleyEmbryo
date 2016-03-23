# singleCellRNASeqHumanBlakeleyEmbryo
Blakeley et al 2015 RNA-seq data, check the [paper](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC4582176/).

To load the data 

```
library(singleCellRNASeqHumanBlakeleyEmbryo)
counts <- exprs(HumanBlakeleyEmbryo)
meta_data <- pData(HumanBlakeleyEmbryo)
gene_names <- rownames(counts)

```
