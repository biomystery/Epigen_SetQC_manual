# Download. 

This section has 3 tabs:
1. Batch download. Instructions for downloading all files in a batch.
2. Individual download links. Links to download each file separately. 
3. Metadata table. A table with metadata about each library. 

**Note: The files that we provide for each library are:**

* `*.R1.fastq.gz`: Raw reads, first read in pair.
* `*.R2.fastq.gz`: Raw reads, second read in pair.
* `*.R1.trim.fastq.gz`: First read in pair, after trimming away adapter sequences.
* `*.R2.trim.fastq.gz`: Second read in pair, after trimming away adapter sequences.
* `*.bam`: Final alignments, after filtering steps described in section (3).
* `*.pileup.signal.bigwig`: Read depth in bins across the genome. This file is displayed in the Genome Browser session. The unit is Fragments Per Million Reads (FPRM). This is the signal file we suggest using for most purposes.
* `*.fc.signal.bigwig`: Fold enrichment over estimated background signal in bins across the genome. (see MACS2 documentation for more information https://github.com/taoliu/MACS).
* `*.pileup.signal.bigwig`: Normalized pileup signal (Fragment pileup Per Million Reads,aka FPMR)  of fragments centered on cutting sites across the genome. (see MACS2 documentation for more information https://github.com/taoliu/MACS).
* `*.narrowpeak.gz`: This is a bed-style file (https://genome.ucsc.edu/FAQ/FAQformat.html#format12)  that contains peaks calls (see MACS2 documentation for more information https://github.com/taoliu/MACS).
