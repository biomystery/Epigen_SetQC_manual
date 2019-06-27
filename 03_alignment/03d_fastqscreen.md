# FastQ Screen. 

This software tool is designed to screen for interspecies contamination in sequencing libraries (Code and documentation available at https://www.bioinformatics.babraham.ac.uk/projects/fastq_screen/). Briefly, reads are randomly sampled from the fastq file and aligned to multiple reference genomes as labeled on the X-axis. The barplot shows the percentage of reads that align to each reference genome. The colors indicate whether a read aligned:

1. To only one genome, and only one location (red, “%One_hit_one_genome)
2. To only one genome, but multiple locations (yellow, “%Multiple_hits_one_genome) 
3. To multiple genomes, but one location per genome (lavender, “%One_hit_multiple_genomes)
4. To multiple genomes, and multiple locations per genome  (green, “%Multiple_hits_multiple_genomes)

It is normal to see some level of cross-mapping among mammalian genomes as indicated in green and lavender. It is also normal to have see reads that don’t map to any genome (usually <5%). However, the reads that align uniquely to one genome (“red”) should all be aligned to the expected genome. Red bars indicating reads that align uniquely to other genomes may indicate potential library contamination, and should be discussed with Center staff. Note: if examining paired-end sequencing each read end is treated separately, so one library will be represented by two bars (one bar for “R1”, and bar one for “R2”). It is normal for “R2” files to have slightly more “No Hits” due to the lower quality of Read 2 base calls on Illumina instruments.
