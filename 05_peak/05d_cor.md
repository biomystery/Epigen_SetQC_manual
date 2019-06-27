# Correlation matrix
This can also be useful for identifying relationships between samples based on ATAC-seq signal.

1. Left panel: Spearman’s correlation heatmap based on the same log2 FE peak-by-sample matrix described in (c) above. Hierarchical clustering is performed to produce the dendrogram displayed above and to the right of the heatmap. The color scale is Spearman’s correlation coefficient [0-1].

2. Right panel: Hexbin heatmap [https://python-graph-gallery.com/84-hexbin-plot-with-matplotlib/]  showing pairwise comparison of average peak log2 FE between two samples. Each dot represents a hexbin in 50x50 grids of the plot. The color scale is the count of peaks in the hexbin with blue represents low number and red represent high number of peaks. Note that this is an interactive plot linked the left panel. You can select any pairwise comparison by clicking on the corresponding box in the left panel. Spearman’s correlation coefficient between the two samples selected is displayed above the counterpart.
