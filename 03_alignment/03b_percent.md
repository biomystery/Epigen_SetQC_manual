## Alignment statistics (by %). 

This table shows the percentage of reads that remain after each major step in the processing pipeline, as calculated from the numbers in the “Alignment statistics (by count)” table. See above for descriptions of each category. Note that there is no distinction made here between “fragments” and “reads” because this distinction does not change the percentages, only the absolute counts.

1. **Reads sequenced.** This is the starting point and should always be 100%.

2. **Reads aligned.** Alignment rates should be 99%+ in most cases.

3. **Reads aligned and pass mapq.** A value of >70% is ideal, though this percentage can vary depending on a number of factors including mitochondrial read content and reference genome assembly. 

4. **Reads aligned, pass mapq, and PCR dup removal.** Read loss of >10% at this stage can indicate low library complexity and/or high mitochondrial content. 

5. **Reads aligned, pass mapq, PCR dup and mito removal.** This is the percentage of total reads that are used for downstream analysis after all filtering steps, and should be >60% in most cases. Note that many mitochondrial reads are eliminated at steps (3) and (4). For a more accurate estimate mitochondrial read content see “Mitochondrial read fraction” section below.
