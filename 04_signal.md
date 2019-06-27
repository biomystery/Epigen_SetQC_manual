## Signal-to-noise metrics. 
This section has four tabs:

1. **TSS enrichment (TSSe).** In our experience, this is the single most important metric for ATAC-seq library quality. High quality ATAC-seq libraries should have strong enrichment for reads around Transcription Start Sites (TSS) reflecting the characteristic nucleosome free region at gene promoters. Each row in the heatmap represents one protein-coding TSS, and darker red indicates higher density of TN5 cutting events. An average profile is shown below the heatmap. The TSSe is quantified by a single number which reflects the enrichment of TN5 cutting at TSS relative to flanking regions. Standards for TSSe have been established by the ENCODE consortium (https://www.encodeproject.org/atac-seq/). 

2. **TSSe average profiles.**  These plots are identical to the average profiles in (a), but plotted on the same axis for ease of cross-library comparison.

3. **TSSe barplot.** TSSe values from (1) are plotted as bars for ease of cross-library comparison.

4. **Fraction of Reads that Overlap TSS (FROT).** This is alternative metric to measure the enrichment of ATAC-seq signal at TSS. 
