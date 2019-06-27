## QC
Quality Control.

## Library
The collection of DNA fragments generated during the ATAC-seq process. 

## Fragment
A DNA fragment in the ATAC-seq library, representing a region of accessible chromatin.

## Fragment size
Length of the DNA fragment in bps. 

## Reads
The short sequences obtained from sequencing a DNA library.

## Fastq file
A file containing sequencing reads.

## Alignment
the process of mapping each read sequence to a location in a given reference genome.

## Bam file 
A file containing read alignments to a reference genome.

## Duplicate reads
Reads that align to the exact same location. This is usually an artifact of PCR, and thus all but one of these reads are eliminated so that we don’t count the same library fragment twice. 

## GC bias
The percentage of Guanine and Cytosine nucleotides present in a given DNA sequence.

## Filtering
The process of narrowing down the full list of sequencing reads to a final list of high quality reads for use in downstream analyses like peak calling. 
## Mapping quality
The confidence with which a read sequence can be mapped to a single location in a reference genome.

## Tracks 
Files that can be viewed on a genome browser. For more information see: https://genome.ucsc.edu/FAQ/FAQformat.html.

## TSS Enrichment
In our experience, this is the single most important metric for ATAC-seq library quality. High quality ATAC-seq libraries should have strong enrichment for reads around Transcription Start Sites (TSS) reflecting the characteristic nucleosome free region at gene promoters. 
