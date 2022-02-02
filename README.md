# Human-provisioned foods reduce gut microbiome diversity in American black bears (*Ursus americanus*) 2022
#### Published Manuscript in Journal of Mammalogy; [DOI: gyab154](https://doi.org/10.1093/jmammal/gyab154)
Authors: Sierra J. Gillman, Erin A. McKenney, Diana J.R. Lafferty
All infromation can also be downloaded from [zenodo](https://zenodo.org/record/5133808#.YfnEOvXMJhE)

**Abstract**:
The distal gut is home to the dynamic and influential gut microbiome, which is intimately linked to mammalian health by promoting and facilitating countless physiological functions. In a time of increased anthropogenic pressures on wildlife due to widespread habitat destruction, loss of natural prey/foods, and rapid urbanization, the study of wildlife gut microbiomes could prove to be a valuable tool in wildlife management and conservation. Diet is one of the most influential determinants of a host’s gut microbiome; yet many wildlife agencies allow baiting to facilitate wildlife harvest, although the impact of human-provisioned foods on wildlife gut health is largely unknown. We used stable isotope analysis derived from carbon (δ 13C) to index the use of human-provisioned foods by 35 legally harvested American black bears (Ursus americanus), and16S rRNA gene amplicon sequencing to examine the impact of human-provisioned foods on the gut microbial diversity of black bears. We found that greater long-term consumption of human-provisioned foods was associated with significantly reduced microbial species richness and phylogenetic diversity. Our results indicate that consumption of anthropogenic foods through baiting significantly alters the mammalian gut microbiome.

Directory structure | Description
--- | ---
blackbear-gmb-JoM/
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
<img src="images/blackbear.jpg" width="300" />
  </p>


