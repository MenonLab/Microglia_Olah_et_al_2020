# Microglia_Olah_et_al_2020
Supplementary files and code for Olah et al. 2020 Nature Communications paper

This repository contains two supplementary files from the original publication: the counts table for all cells that passed filtering and were used in the final analysis, and a metadata table of donor and cluster IDs. 
This repository also contains the general workflow coded in R for clustering these cells. Note that this workflow was implemented in Seurat v2 in the paper.

Finally, there is a Seurat v4 object that contains the raw counts and additional metadata, including t-SNE coordinates used for the paper. Although this object contains an SC-Transformed field and subsequent Principal Component calculations, these are not the same as the ones used to generate the t-SNE coordinates in the paper. Because of the version differences in Seurat and the iterative nature of the clustering (described in the paper and outlined in the code), the t-SNE Cell Embeddings in the object as they are saved will not correspond to applying the RunTSNE command on the object.
