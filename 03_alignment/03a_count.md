# Alignment statistics (by count). 
This table shows the number of reads that remain after each major step in the processing pipeline (code and accompanying documentation about our processing pipeline can be found here: https://github.com/epigen-UCSD/atac_seq_pipeline). Normal ranges, where applicable, are discussed in the following section (b).

1. **Fragments sequenced:** The total number of reads or read pairs sequenced. If using paired-end sequencing this is the total number of reads divided by two, because both read pairs come from the same fragment. If using single-end sequencing this number will be identical to the number of reads.

1. **Reads sequenced.**  The total number of reads sequenced, regardless of whether single-end or paired-end.

1. **Reads aligned.** The number of reads from (ii) that align to the reference genome of interest.

1. **Reads aligned and pass mapq.**  The number of reads from (iii) that pass a mapping quality (mapq) filter to eliminate reads mapping to repetitive regions of the genome.

1. **Reads aligned, pass mapq, and PCR dup removal.**  The number of reads from (iv) that remain after eliminating potential PCR duplicates. 
Reads aligned, pass mapq, PCR dup and mito removal. The number of reads from (v) that remain after eliminating reads that map to the mitochondrial genome. Mitochondrial reads are overrepresented in ATAC-seq libraries, but are not used for most downstream analysis.

1. **Final number of fragments.** This is the final number of usable fragments that remain after all filtering steps in the pipeline. This is the effective read depth of each library. If using single-end sequencing, this number will be the same as (vi). If using paired-end sequencing, this is (vi) divided by two.
