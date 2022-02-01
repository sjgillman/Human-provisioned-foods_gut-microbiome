# Human-provisioned foods reduce gut microbiome diversity in American black bears (*Ursus americanus*) 2021
#### Published Manuscript in Journal of Mammalogy; [DOI: 10.1093](https://doi.org/10.1093/jmammal/gyab154)
Authors: Sierra J. Gillman, Erin A. McKenney, Diana J.R. Lafferty
All infromation can also be downloaded from [zenodo](https://zenodo.org/record/5133808#.YfnEOvXMJhE)


Directory structure | Description
--- | ---
blackbear-gme-JoM/
  README.md
  **data/** | **Description**
  *MetaFile.tsv* | the metadata file including sampleID, stable carbon and nitrogen values, sex, age-class etc for each sample
  *BlackBeardemuxsequences.tar.gz* | demultiplexed EMP-paired end sequences demultiplexed on QIIME2
  *OTU_table.qza* | QIIME2 artifact with ASVs called with DADA2
  *taxonomy.qza* | QIIME2 artifact
  *rooted-tree.qza* | QIIME2 artifact created with MAFFT
  *phyloseq.rds* | phyloseq object created with MetaFile.tsv, OTU_table.qza, taxonomy.qza, and rooted-tree.qza and used for downstream analysis in R.
  *phyloseq_srs.rds* | normalized "phyloseq.rds" object.
  **scripts/** | **Description**
  *QIIME2 Pipeline.md* | bioinformatic pipeline to prepare sequences for analysis in R
   *Supplementary Data SD3.pdf/RMD* | code for analysis and figure creation in R.
  **images/**
  *blackbear.jpg*

<p align="center">
<img src="images/blackbear.jpg" width="500" />
  </p>


