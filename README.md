# Single-Cell-Analysis

Single cell analysis:
In RNA-seq single cell analysis we analyse 10X Chromium single-cell RNA-seq profiles using R. This will include reading the count data into R, quality control, normalisation, dimensionality reduction, cell clustering and finding marker genes.
The main part of the workflow uses the package SEURAT which is designed for QC, analysis, and exploration of single-cell RNA-seq data. Seurat aims to enable users to identify and interpret sources of heterogeneity from single-cell transcriptomic measurements, and to integrate diverse types of single-cell data.

File link: https://www.ncbi.xyz/geo/query/acc.cgi?acc=GSM6601966

CSV File: GSM6601966_p1001_raw_counts.csv.gz

PROCEDURE:
1. Basic quality control and filtering.
2. Meta.data count for cell quality check.
3. Different plots of metadata feature to check correlation between them.The number above each plot is a Pearson correlation coefficient.
4. Variable Feature Plot to View variable features and their expression.
5. Violin plots of the selected metadata features.
6. DimHeatmap plot and Elbow plot: DimHeatMap helps to create heatmap of each principal component or several PCs at once. Basically, it draws a heatmap focusing on a principal component. Both cells and genes are sorted by their principal component scores. Allows for nice visualization of sources of heterogeneity in the dataset.
7. We can now do clustering. For visualization purposes, we also need to generate UMAP reduced dimensionality representation.
8. Dimplot: Graphs of dimplots are the output of a dimensional reduction technique on a 2D scatter plot where each point is a cell and it's positioned based on the cell embeddings determined by the reduction technique. By default, cells are colored by their identity class.
9. Finds markers (differentially expressed genes) for each of the identity classes in a dataset.
10. Visualize 'features' on a dimensional reduction plot.
11. Cell type annotation.


