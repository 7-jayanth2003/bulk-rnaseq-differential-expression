# Research Question and Study Design

## Project title

Differential Gene Expression Analysis and Replicate-Number Evaluation in *Saccharomyces cerevisiae*

## Main biological question

Which genes show changes in expression when the chromatin-remodelling gene `SNF2` is deleted in *Saccharomyces cerevisiae*?

## Secondary methodological question

How does the number of biological replicates affect the detection and stability of differentially expressed genes?

## Study objectives

1. Obtain and inspect a published RNA-seq gene-count dataset and its sample metadata.
2. Verify the experimental design, biological replicates, sample labels, and any exclusions.
3. Perform differential expression analysis using DESeq2.
4. Evaluate sample quality, expression patterns, and statistical results using appropriate diagnostic plots.
5. Compare the analysis with published findings where the methods and comparisons are compatible.
6. Investigate how repeated subsampling of biological replicates affects differential-expression results.
7. Document the analysis so that it can be reproduced by another researcher.

## Dataset selection principle

The primary dataset will be selected based on scientific provenance, accessible sample metadata, sufficient biological replication, computational feasibility, and the availability of published results suitable for comparison.

The exact sample counts, exclusions, condition labels, and experimental design must be verified before analysis.

## Planned analysis

The initial analysis will use a published gene-count matrix rather than downloading all raw sequencing reads. A small raw-read subset may be analysed later to demonstrate quality control and a reproducible sequencing workflow, depending on file sizes and available computing resources.

## Statistical considerations

The analysis will distinguish biological replicates from technical replicates. Differential-expression results will be evaluated using effect sizes, statistical significance, and false discovery rate (FDR) control.

The replicate-number investigation will use repeated, reproducible subsampling and clearly defined comparison metrics. Conclusions will be limited to what the experiment supports.

## Reproducibility

Code, software and package versions, metadata, analysis decisions, quality-control results, and documentation will be tracked where appropriate. Large datasets and generated outputs will not be committed to Git unless there is a specific reason to do so.