Title: DNA-Seq Analysis of TP53 Gene for Variant Identification and Annotation
Objective: 
To identify genetic variants in the TP53 gene using DNA sequencing data
To perform variant calling and functional annotation
To understand mutation patterns relevant to cancer genomics
Dataset Information:
Data type: RNAseq data
Format: FASTQ 
Referecene genome used: GRCh38
Data source: Public data source (SRA, ENA)
Tools used:
FASTQC - Quality check
Trimming: FASTP
BWA - Alignment
SAM TOOLS - BAM processing
GATK - Variant calling
VEP - Annotation
IGV - Visualization
Workflow- pipeline
Data extraction - quality control - trimming - alignment - sorting - remove duplicates - variant calling - variant annotation.
Results- 
A total of 12,795 variants were identified and analyzed using Ensembl VEP.
Variants processed: 12,795
Variants filtered out: 0
Novel variants: 7,605 (59.4%)
Known variants: 5,190 (40.6%)
Genes affected: 1,643
Transcripts affected: 15,184
Regulatory regions impacted: 256
The majority of variants were located in non-coding regions, with the following distribution:
Intronic variants: 29%
Downstream gene variants: 15%
Upstream gene variants: 11%
Non-coding transcript variants: 7%
Splice-related variants (donor, acceptor, region): ~13%
Other categories: Remaining fraction
Interpretation
This distribution indicates that most variants occur outside coding regions, which is expected in genomic datasets. However, splice-site variants (~13%) may significantly affect gene expression and transcript stability.
Variants affecting coding regions were further classified as follows:
Synonymous variants: 36%
Coding sequence variants: 31%
Missense variants: 13%
Frameshift variants: 13%
Inframe insertions: 5%
Stop gained variants: 1%
Interpretation:
Missense and frameshift variants (26%) suggest potential functional impact on protein structure and function.
Stop gained variants (1%) are high-impact mutations that may lead to truncated, non-functional proteins.
A high proportion of synonymous variants (36%) indicates many mutations are likely neutral.
Key findings:
Identified a substantial number of novel variants (59.4%), highlighting potential for discovery
Detected functionally significant mutations including:
Missense variants
Frameshift mutations
Stop-gained mutations
Observed splice-site variants, which may influence gene regulation
Overall results suggest the presence of variants with potential biological and clinical relevance, especially in the context of cancer-associated genes like TP53.
