# HTS_Project
This repository contains files related to the final project for HTS class at Jagiellonian Univeristy.
The project was completed in January, 2026.

## About project:
The main goal of our final project was to verify whether replication of publicly available, aged RNA-seq data with tools available at the moment could yield new information.

## Used data:
For our project we decided to use reads from BioProject PRJNA147913, due to the fact that these reads were uploaded into SRA archive in 2011. We also used human reference genome: GRCh38.p14 from NCBI.

### Versions of used tools and packages:

entrez-direct 24.0  
fasterq-dump : 3.2.1  
md5sum (GNU coreutils): 9.4  
bowtie2-align-s version: 2.5.4  
samtools 1.22.1

disclaimer: during work on this project we used ChatGPT 5.2 version - this AI tool was used for translating to polish part of documentation, managing YAML options and debugging code. Examples of used prompt can be found in file:AI_usage.txt

R version 4.3.3 (2024-02-29)
Platform: x86_64-pc-linux-gnu (64-bit)
Running under: Ubuntu 24.04.1 LTS

Matrix products: default
BLAS:   /usr/lib/x86_64-linux-gnu/blas/libblas.so.3.12.0 
LAPACK: /usr/lib/x86_64-linux-gnu/lapack/liblapack.so.3.12.0

locale:
 [1] LC_CTYPE=pl_PL.UTF-8       LC_NUMERIC=C               LC_TIME=pl_PL.UTF-8        LC_COLLATE=pl_PL.UTF-8    
 [5] LC_MONETARY=pl_PL.UTF-8    LC_MESSAGES=pl_PL.UTF-8    LC_PAPER=pl_PL.UTF-8       LC_NAME=C                 
 [9] LC_ADDRESS=C               LC_TELEPHONE=C             LC_MEASUREMENT=pl_PL.UTF-8 LC_IDENTIFICATION=C       

time zone: Europe/Warsaw
tzcode source: system (glibc)

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
[1] biomaRt_2.58.2

loaded via a namespace (and not attached):
 [1] KEGGREST_1.42.0             SummarizedExperiment_1.32.0 gtable_0.3.6                xfun_0.55                  
 [5] ggplot2_4.0.1               Biobase_2.62.0              lattice_0.22-5              vctrs_0.7.0                
 [9] tools_4.3.3                 bitops_1.0-9                generics_0.1.4              curl_7.0.0                 
[13] stats4_4.3.3                parallel_4.3.3              tibble_3.3.1                AnnotationDbi_1.64.1       
[17] RSQLite_2.4.5               blob_1.3.0                  pkgconfig_2.0.3             Matrix_1.6-5               
[21] dbplyr_2.5.1                RColorBrewer_1.1-3          S7_0.2.1                    S4Vectors_0.40.2           
[25] lifecycle_1.0.5             GenomeInfoDbData_1.2.11     stringr_1.6.0               compiler_4.3.3             
[29] farver_2.1.2                progress_1.2.3              Biostrings_2.70.3           DESeq2_1.42.1              
[33] codetools_0.2-19            GenomeInfoDb_1.38.8         RCurl_1.98-1.17             pillar_1.11.1              
[37] crayon_1.5.3                BiocParallel_1.36.0         DelayedArray_0.28.0         cachem_1.1.0               
[41] abind_1.4-8                 digest_0.6.39               tidyselect_1.2.1            locfit_1.5-9.12            
[45] stringi_1.8.7               dplyr_1.1.4                 fastmap_1.2.0               grid_4.3.3                 
[49] cli_3.6.5                   SparseArray_1.2.4           magrittr_2.0.4              S4Arrays_1.2.1             
[53] XML_3.99-0.20               rappdirs_0.3.4              filelock_1.0.3              prettyunits_1.2.0          
[57] scales_1.4.0                bit64_4.6.0-1               XVector_0.42.0              httr_1.4.7                 
[61] matrixStats_1.5.0           bit_4.6.0                   hms_1.1.4                   png_0.1-8                  
[65] evaluate_1.0.5              memoise_2.0.1               knitr_1.51                  GenomicRanges_1.54.1       
[69] IRanges_2.36.0              BiocFileCache_2.10.2        rlang_1.1.7                 Rcpp_1.1.1                 
[73] glue_1.8.0                  DBI_1.2.3                   xml2_1.5.1                  BiocGenerics_0.48.1        
[77] rstudioapi_0.18.0           R6_2.6.1                    MatrixGenerics_1.14.0       zlibbioc_1.48.2            
