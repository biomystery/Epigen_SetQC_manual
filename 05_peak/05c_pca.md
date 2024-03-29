# PCA
Principal Component Analysis of samples based on peak intensity (fold enrichment of calculated background from MACS2). This can be useful for identifying relationships between samples based on ATAC-seq signal. Briefly, (1) peaks are merged across all samples (2) average fold enrichment (FE) are calculated for each peak in each sample, creating a peak-by-sample matrix, (3) Peaks’ average FEs are then log2 transformed and scaled to zero mean and one standard deviation on each sample, (4) PCA is performed and the first two PCs are plotted. Note that this is an interactive plot. You can zoom in by mousing over and scrolling. 
