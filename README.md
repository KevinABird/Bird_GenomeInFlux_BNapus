# Bird_GenomeInFlux_BNapus
Code used for manuscript Genomic rearrangements , subgenome dominance, and gene dosage balance constraints in resynthesized allopolyploid Brassica napus

I'm sorry I'm not good at programming or READMEs

Intermediate files and additional scripts can be found at https://doi.org/10.5061/dryad.h18931zjr

Two main scripts:

1. BNapus_HEs.Rmd is a copy of the old code used to identify putative HEs based on read depth ratios. This outputs files for each line and for each 'class' of HEs e.g. 0:4, 1:3, 2:2, 3:1, 4:0. These classifications aren't heavily relied on for subsequent analyses, but they are recorded.

2. Birdetal_HEs_Expression.Rmd Includes code for all analyses and figures for this paper. Needed files, including the files the Syntelog anchors and list of Arabidopsis-Brassica oleracea synteologs are included in the Data directory. Supplemental files for the Dosage sensitivity classification can be found at https://academic.oup.com/plcell/article/32/5/1434/6115612?supplementary-data
