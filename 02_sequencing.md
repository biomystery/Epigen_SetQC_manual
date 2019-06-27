# Sequencing metrics.

This section contains results from a software tool called MultiQC that
calculates multiple quality control (QC) metrics associated with
Illumina sequencing data (Code and documentation available at
https://multiqc.info/). These metrics can be useful for diagnosing
problems that occur during sequencing or library construction. Please
note that Center staff review these metrics and will flag any
concerns. For users interested in more detail, A full MultiQC report
for your samples can be viewed by following the link below the plots:
"view full MultiQC report (in new window)". In addition, we provide
three of the most commonly viewed plots are shown here for
convenience: 

a. **Per base N content.** This plot shows the percentage of reads
 with a no-call base (“N”) at each position along the read length for
 each library. It is typical to see slightly elevated N content of
 ~0.5% at the beginning and end of the read. Other anomalies can
 indicate technical problems during the sequencing run. 
 
b. **Mean Quality Scores.** This plot the average base call quality score
 (“phred” score) at each position along the read length for each
 library. It is typical to see slightly lower scores at the  beginning 
 and end of the read. Average scores below 30 can indicate technical
 problems during  the sequencing run.
 
c. **FastQC: Sequence Duplication Levels.** This plot shows the percentage
 of sequences in the library that are present at different
 frequencies. This can provide an early indication of library
 complexity, but the post-alignment metrics described in sections 3a
 and 3b below are usually more informative.
 
