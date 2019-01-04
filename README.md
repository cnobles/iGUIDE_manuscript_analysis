# iGUIDE manuscript analysis
Analysis provided in the "iGUIDE: an improved pipeline for analyzing CRISPR cleavage specificity" manuscript.

For an updated version of iGUIDE, please visit https://github.com/cnobles/iGUIDE.

This repository is meant to provide the source code for the analysis provided in the above manuscript by Christopher L. Nobles, Shantan Reddy, January Salas-McKee, Xiaojun Liu, Carl H. June, J. Joseph Melenhorst, Megan Suhoski, Yangbing Zhao, and Frederic D. Bushman.

Abstract:
Genome engineering methods have advanced greatly with the development of programmable nucleases, but methods for quantifying on- and off-target cleavage sites and associated deletions remain nascent. Here, we report an improvement of the GUIDE-seq method, iGUIDE, which allows filtering of mispriming events to clarify the true cleavage signal. Using iGUIDE, we specify the locations of Cas9-guided cleavage for four guide RNAs, characterize associated deletions, and show that naturally occurring background DNA double strand breaks are associated with open chromatin, gene dense regions, and chromosomal fragile sites. iGUIDE is available from https://github.com/cnobles/iGUIDE.

To run the analysis, run the R-code blocks from the 'manuscript_figures.archive.Rmd' file. Additionally, the user can knit the Rmd into a PDF document within an R session with rmarkdown::render(). The Rmd file will pull from already processed and compressed data in the rest of the repository to generate the figures from the manuscript. 

This repository also contains a final processing dataset from the manuscript. Anyone can use this data rather than reprocessing with the iGUIDE software from the SRA submission (BioProject: PRJNA506241). There is no certainty that reprocessing will yeild the same results if the version of the iGUIDE software is different (data processed with version 0.9).

This repository was successfully executed under the following session:

R version 3.4.0 (2017-04-21)
Platform: x86_64-pc-linux-gnu (64-bit)
Running under: Ubuntu 16.04.5 LTS

Matrix products: default
BLAS: /home/opt/R-3.4.0/lib/R/lib/libRblas.so
LAPACK: /home/opt/R-3.4.0/lib/R/lib/libRlapack.so

locale:
 [1] LC_CTYPE=en_US.UTF-8       LC_NUMERIC=C               LC_TIME=en_US.UTF-8       
 [4] LC_COLLATE=en_US.UTF-8     LC_MONETARY=en_US.UTF-8    LC_MESSAGES=en_US.UTF-8   
 [7] LC_PAPER=en_US.UTF-8       LC_NAME=C                  LC_ADDRESS=C              
[10] LC_TELEPHONE=C             LC_MEASUREMENT=en_US.UTF-8 LC_IDENTIFICATION=C       

attached base packages:
[1] stats4    parallel  stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] bindrcpp_0.2.2             kableExtra_0.8.0           knitr_1.19                
 [4] hiAnnotator_1.11.1         rmarkdown_1.8              gridExtra_2.3             
 [7] BSgenome_1.44.2            rtracklayer_1.36.6         data.table_1.10.4-3       
[10] stringr_1.3.1              ShortRead_1.34.2           GenomicAlignments_1.12.2  
[13] SummarizedExperiment_1.6.5 DelayedArray_0.2.7         matrixStats_0.53.0        
[16] Biobase_2.36.2             Rsamtools_1.28.0           BiocParallel_1.10.1       
[19] magrittr_1.5               pander_0.6.1               reshape2_1.4.3            
[22] scales_0.5.0               ggplot2_3.0.0              dplyr_0.7.6               
[25] gintools_0.1.1             Matrix_1.2-9               igraph_1.2.2              
[28] Biostrings_2.44.2          XVector_0.16.0             GenomicRanges_1.28.6      
[31] GenomeInfoDb_1.12.3        IRanges_2.10.5             S4Vectors_0.14.7          
[34] BiocGenerics_0.22.1       

loaded via a namespace (and not attached):
 [1] httr_1.3.1                        tidyr_0.8.1                      
 [3] viridisLite_0.2.0                 foreach_1.4.4                    
 [5] assertthat_0.2.0                  latticeExtra_0.6-28              
 [7] GenomeInfoDbData_0.99.0           yaml_2.1.16                      
 [9] pillar_1.1.0                      backports_1.1.2                  
[11] lattice_0.20-35                   glue_1.2.0                       
[13] digest_0.6.15                     RColorBrewer_1.1-2               
[15] rvest_0.3.2                       colorspace_1.3-2                 
[17] htmltools_0.3.6                   plyr_1.8.4                       
[19] XML_3.98-1.9                      pkgconfig_2.0.1                  
[21] zlibbioc_1.22.0                   purrr_0.2.5                      
[23] tibble_1.4.2                      withr_2.1.1                      
[25] lazyeval_0.2.1                    evaluate_0.10.1                  
[27] xml2_1.2.0                        hwriter_1.3.2                    
[29] grImport_0.9-0                    tools_3.4.0                      
[31] hms_0.4.2                         munsell_0.4.3                    
[33] compiler_3.4.0                    rlang_0.2.2                      
[35] grid_3.4.0                        RCurl_1.95-4.10                  
[37] iterators_1.0.9                   rstudioapi_0.7                   
[39] labeling_0.3                      bitops_1.0-6                     
[41] gtable_0.2.0                      codetools_0.2-15                 
[43] R6_2.2.2                          bindr_0.1.1                      
[45] rprojroot_1.3-2                   readr_1.1.1                      
[47] stringi_1.2.4                     Rcpp_0.12.17                     
[49] tidyselect_0.2.3                  BSgenome.Hsapiens.UCSC.hg38_1.4.1
