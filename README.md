# MAGeCK
Model-based Analysis of Genome-wide CRISPR-Cas9 Knockout (MAGeCK) is a computational tool to identify important genes from the recent genome-scale CRISPR-Cas9 knockout screens technology.

Please refer to the [bitbucket repo](https://bitbucket.org/liulab/mageck/src/master/) for source code, and [sourceforge](https://sourceforge.net/projects/mageck/) for installation.

# MAGeCK-VISPR
Quality Control, Modeling and Visualization of CRISPR/Cas9 Screens with MAGeCK-VISPR

Please refer to the [bitbucket repo](https://bitbucket.org/liulab/mageck-vispr/src/master/) for source code and usage information. MAGeCK-VISPR is a comprehensive quality control, analysis and visualization workflow for CRISPR/Cas9 screens. The workflow combines:
* the MAGeCK algorithm to identify essential genes from CRISPR/Cas9 screens considering multiple conditions
* with VISPR to interactively explore results and quality control in a web-based frontend.

# MAGeCKFlute (R package)
Integrative analysis pipeline for pooled CRISPR functional genetic screens

Please refer to the [bioconductor page](https://bioconductor.org/packages/devel/bioc/vignettes/MAGeCKFlute/inst/doc/MAGeCKFlute.html) for installation and usage information. MAGeCKFlute provides several strategies to remove potential biases within sgRNA-level read counts and gene-level beta scores. The downstream analysis with the package includes identifying essential, non-essential, and target-associated genes, and performing biological functional category analysis, pathway enrichment analysis and protein complex enrichment analysis of these genes. The package also visualizes genes in multiple ways to benefit users exploring screening data. Collectively, MAGeCKFlute enables accurate identification of essential, non-essential, and targeted genes, as well as their related biological functions. This vignette explains the use of the package and demonstrates typical workflows.
