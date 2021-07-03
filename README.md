# clusterProfiler 4.0: A universal enrichment tool for interpreting omics data


If you use this work in published research, please cite:

T Wu<sup>§</sup>, E Hu<sup>§</sup>, S Xu, M Chen, P Guo, Z Dai, T Feng, L Zhou, W Tang, L Zhan, X Fu, S Liu, X Bo<sup>\*</sup>, and **G Yu**<sup>\*</sup>. clusterProfiler 4.0: A universal enrichment tool for interpreting omics data. **_The Innovation_**. doi: <https://doi.org/10.1016/j.xinn.2021.100141>.

This repo contains source code and data to produce **Supplementary Material** of the above paper.


To compile the [supplementary_file.pdf](supplementary_file.pdf),
please run the following command in R:

``` r
rmarkdown::render("supplementary_file.Rmd")
```


Here is the output of `devtools::session_info()` on the system on which [the document](supplementary_file.pdf) was compiled:

```
─ Session info ───────────────────────────────────────────────────────────────
 setting  value                       
 version  R version 4.1.0 (2021-05-18)
 os       Arch Linux                  
 system   x86_64, linux-gnu           
 ui       X11                         
 language (EN)                        
 collate  en_US.UTF-8                 
 ctype    en_US.UTF-8                 
 tz       Asia/Chongqing              
 date     2021-06-15                  

─ Packages ───────────────────────────────────────────────────────────────────
 package                           * version    date       lib source        
 AnnotationDbi                     * 1.54.0     2021-05-19 [1] Bioconductor  
 ape                                 5.5        2021-04-25 [1] CRAN (R 4.1.0)
 aplot                               0.0.6      2020-09-03 [1] CRAN (R 4.1.0)
 assertthat                          0.2.1      2019-03-21 [1] CRAN (R 4.1.0)
 Biobase                           * 2.52.0     2021-05-19 [1] Bioconductor  
 BiocFileCache                       2.0.0      2021-05-19 [1] Bioconductor  
 BiocGenerics                      * 0.38.0     2021-05-19 [1] Bioconductor  
 BiocIO                              1.2.0      2021-05-19 [1] Bioconductor  
 BiocManager                         1.30.15    2021-05-11 [1] CRAN (R 4.1.0)
 BiocParallel                        1.26.0     2021-05-19 [1] Bioconductor  
 biomaRt                             2.48.0     2021-05-19 [1] Bioconductor  
 Biostrings                          2.60.0     2021-05-19 [1] Bioconductor  
 bit                                 4.0.4      2020-08-04 [1] CRAN (R 4.1.0)
 bit64                               4.0.5      2020-08-30 [1] CRAN (R 4.1.0)
 bitops                              1.0-7      2021-04-24 [1] CRAN (R 4.1.0)
 blob                                1.2.1      2020-01-20 [1] CRAN (R 4.1.0)
 bookdown                            0.22       2021-04-22 [1] CRAN (R 4.1.0)
 boot                                1.3-28     2021-05-03 [1] CRAN (R 4.1.0)
 cachem                              1.0.5      2021-05-15 [1] CRAN (R 4.1.0)
 callr                               3.7.0      2021-04-20 [1] CRAN (R 4.1.0)
 caTools                             1.18.2     2021-03-28 [1] CRAN (R 4.1.0)
 ChIPseeker                        * 1.28.3     2021-05-21 [1] Bioconductor  
 cli                                 2.5.0      2021-04-26 [1] CRAN (R 4.1.0)
 clusterProfiler                   * 4.0.0      2021-05-19 [1] Bioconductor  
 codetools                           0.2-18     2020-11-04 [1] CRAN (R 4.1.0)
 colorspace                          2.0-1      2021-05-04 [1] CRAN (R 4.1.0)
 conflicted                        * 1.0.4      2019-06-21 [1] CRAN (R 4.1.0)
 cowplot                             1.1.1      2020-12-30 [1] CRAN (R 4.1.0)
 crayon                              1.4.1      2021-02-08 [1] CRAN (R 4.1.0)
 curl                                4.3.1      2021-04-30 [1] CRAN (R 4.1.0)
 data.table                          1.14.0     2021-02-21 [1] CRAN (R 4.1.0)
 DBI                                 1.1.1      2021-01-15 [1] CRAN (R 4.1.0)
 dbplyr                              2.1.1      2021-04-06 [1] CRAN (R 4.1.0)
 DelayedArray                        0.18.0     2021-05-19 [1] Bioconductor  
 desc                                1.3.0      2021-03-05 [1] CRAN (R 4.1.0)
 devtools                            2.4.1      2021-05-05 [1] CRAN (R 4.1.0)
 digest                              0.6.27     2020-10-24 [1] CRAN (R 4.1.0)
 dlstats                           * 0.1.4      2021-04-23 [1] CRAN (R 4.1.0)
 DO.db                               2.9        2021-05-22 [1] Bioconductor  
 DOSE                              * 3.19.1     2021-06-13 [1] Bioconductor  
 downloader                          0.4        2015-07-09 [1] CRAN (R 4.1.0)
 dplyr                               1.0.6      2021-05-05 [1] CRAN (R 4.1.0)
 ellipsis                            0.3.2      2021-04-29 [1] CRAN (R 4.1.0)
 enrichplot                        * 1.13.0.992 2021-06-13 [1] Bioconductor  
 evaluate                            0.14       2019-05-28 [1] CRAN (R 4.1.0)
 fansi                               0.5.0      2021-05-25 [1] CRAN (R 4.1.0)
 farver                              2.1.0      2021-02-28 [1] CRAN (R 4.1.0)
 fastmap                             1.1.0      2021-01-25 [1] CRAN (R 4.1.0)
 fastmatch                           1.1-0      2017-01-28 [1] CRAN (R 4.1.0)
 fgsea                               1.18.0     2021-05-19 [1] Bioconductor  
 filelock                            1.0.2      2018-10-05 [1] CRAN (R 4.1.0)
 forcats                           * 0.5.1      2021-01-27 [1] CRAN (R 4.1.0)
 fs                                  1.5.0      2020-07-31 [1] CRAN (R 4.1.0)
 generics                            0.1.0      2020-10-31 [1] CRAN (R 4.1.0)
 GenomeInfoDb                      * 1.28.0     2021-05-19 [1] Bioconductor  
 GenomeInfoDbData                    1.2.6      2021-05-21 [1] Bioconductor  
 GenomicAlignments                   1.28.0     2021-05-19 [1] Bioconductor  
 GenomicFeatures                   * 1.44.0     2021-05-19 [1] Bioconductor  
 GenomicRanges                     * 1.44.0     2021-05-19 [1] Bioconductor  
 ggforce                             0.3.3      2021-03-05 [1] CRAN (R 4.1.0)
 ggnewscale                          0.4.5      2021-01-11 [1] CRAN (R 4.1.0)
 ggplot2                           * 3.3.3      2020-12-30 [1] CRAN (R 4.1.0)
 ggprism                           * 1.0.2      2021-02-22 [1] CRAN (R 4.1.0)
 ggraph                              2.0.5      2021-02-23 [1] CRAN (R 4.1.0)
 ggrepel                             0.9.1      2021-01-15 [1] CRAN (R 4.1.0)
 ggtree                              3.1.1.992  2021-06-13 [1] Bioconductor  
 ggupset                             0.3.0      2020-05-05 [1] CRAN (R 4.1.0)
 glue                                1.4.2      2020-08-27 [1] CRAN (R 4.1.0)
 GO.db                               3.13.0     2021-05-22 [1] Bioconductor  
 GOSemSim                            2.18.0     2021-05-19 [1] Bioconductor  
 gplots                              3.1.1      2020-11-28 [1] CRAN (R 4.1.0)
 graphlayouts                        0.7.1      2020-10-26 [1] CRAN (R 4.1.0)
 gridExtra                           2.3        2017-09-09 [1] CRAN (R 4.1.0)
 gtable                              0.3.0      2019-03-25 [1] CRAN (R 4.1.0)
 gtools                              3.8.2      2020-03-31 [1] CRAN (R 4.1.0)
 hms                                 1.1.0      2021-05-17 [1] CRAN (R 4.1.0)
 htmltools                           0.5.1.1    2021-01-22 [1] CRAN (R 4.1.0)
 httr                                1.4.2      2020-07-20 [1] CRAN (R 4.1.0)
 igraph                              1.2.6      2020-10-06 [1] CRAN (R 4.1.0)
 IRanges                           * 2.26.0     2021-05-19 [1] Bioconductor  
 jsonlite                            1.7.2      2020-12-09 [1] CRAN (R 4.1.0)
 kableExtra                        * 1.3.4      2021-02-20 [1] CRAN (R 4.1.0)
 KEGGREST                            1.32.0     2021-05-19 [1] Bioconductor  
 KernSmooth                          2.23-20    2021-05-03 [1] CRAN (R 4.1.0)
 knitr                               1.33       2021-04-24 [1] CRAN (R 4.1.0)
 labeling                            0.4.2      2020-10-20 [1] CRAN (R 4.1.0)
 lattice                             0.20-44    2021-05-02 [1] CRAN (R 4.1.0)
 lazyeval                            0.2.2      2019-03-15 [1] CRAN (R 4.1.0)
 lifecycle                           1.0.0      2021-02-15 [1] CRAN (R 4.1.0)
 magrittr                          * 2.0.1      2020-11-17 [1] CRAN (R 4.1.0)
 MASS                                7.3-54     2021-05-03 [1] CRAN (R 4.1.0)
 Matrix                              1.3-3      2021-05-04 [1] CRAN (R 4.1.0)
 MatrixGenerics                      1.4.0      2021-05-19 [1] Bioconductor  
 matrixStats                         0.58.0     2021-01-29 [1] CRAN (R 4.1.0)
 memoise                             2.0.0      2021-01-26 [1] CRAN (R 4.1.0)
 munsell                             0.5.0      2018-06-12 [1] CRAN (R 4.1.0)
 nlme                                3.1-152    2021-02-04 [1] CRAN (R 4.1.0)
 org.Hs.eg.db                      * 3.13.0     2021-05-22 [1] Bioconductor  
 patchwork                           1.1.1      2020-12-17 [1] CRAN (R 4.1.0)
 pillar                              1.6.1      2021-05-16 [1] CRAN (R 4.1.0)
 pkgbuild                            1.2.0      2020-12-15 [1] CRAN (R 4.1.0)
 pkgconfig                           2.0.3      2019-09-22 [1] CRAN (R 4.1.0)
 pkgload                             1.2.1      2021-04-06 [1] CRAN (R 4.1.0)
 plotrix                             3.8-1      2021-01-21 [1] CRAN (R 4.1.0)
 plyr                                1.8.6      2020-03-03 [1] CRAN (R 4.1.0)
 png                                 0.1-7      2013-12-03 [1] CRAN (R 4.1.0)
 polyclip                            1.10-0     2019-03-14 [1] CRAN (R 4.1.0)
 prettyunits                         1.1.1      2020-01-24 [1] CRAN (R 4.1.0)
 processx                            3.5.2      2021-04-30 [1] CRAN (R 4.1.0)
 progress                            1.2.2      2019-05-16 [1] CRAN (R 4.1.0)
 ps                                  1.6.0      2021-02-28 [1] CRAN (R 4.1.0)
 purrr                               0.3.4      2020-04-17 [1] CRAN (R 4.1.0)
 qvalue                              2.24.0     2021-05-19 [1] Bioconductor  
 R6                                  2.5.0      2020-10-28 [1] CRAN (R 4.1.0)
 rappdirs                            0.3.3      2021-01-31 [1] CRAN (R 4.1.0)
 RColorBrewer                        1.1-2      2014-12-07 [1] CRAN (R 4.1.0)
 Rcpp                                1.0.6      2021-01-15 [1] CRAN (R 4.1.0)
 RCurl                               1.98-1.3   2021-03-16 [1] CRAN (R 4.1.0)
 remotes                             2.3.0      2021-04-01 [1] CRAN (R 4.1.0)
 reshape2                            1.4.4      2020-04-09 [1] CRAN (R 4.1.0)
 restfulr                            0.0.13     2017-08-06 [1] CRAN (R 4.1.0)
 rjson                               0.2.20     2018-06-08 [1] CRAN (R 4.1.0)
 rlang                               0.4.11     2021-04-30 [1] CRAN (R 4.1.0)
 rmarkdown                         * 2.8        2021-05-07 [1] CRAN (R 4.1.0)
 rprojroot                           2.0.2      2020-11-15 [1] CRAN (R 4.1.0)
 Rsamtools                           2.8.0      2021-05-19 [1] Bioconductor  
 RSQLite                             2.2.7      2021-04-22 [1] CRAN (R 4.1.0)
 rstudioapi                          0.13       2020-11-12 [1] CRAN (R 4.1.0)
 rtracklayer                         1.52.0     2021-05-19 [1] Bioconductor  
 rvcheck                           * 0.1.8      2020-03-01 [1] CRAN (R 4.1.0)
 rvest                               1.0.0      2021-03-09 [1] CRAN (R 4.1.0)
 S4Vectors                         * 0.30.0     2021-05-19 [1] Bioconductor  
 scales                              1.1.1      2020-05-11 [1] CRAN (R 4.1.0)
 scatterpie                          0.1.6      2021-04-23 [1] CRAN (R 4.1.0)
 sessioninfo                         1.1.1      2018-11-05 [1] CRAN (R 4.1.0)
 shadowtext                          0.0.8      2021-04-23 [1] CRAN (R 4.1.0)
 stringi                             1.6.2      2021-05-17 [1] CRAN (R 4.1.0)
 stringr                           * 1.4.0      2019-02-10 [1] CRAN (R 4.1.0)
 SummarizedExperiment                1.22.0     2021-05-19 [1] Bioconductor  
 svglite                             2.0.0      2021-02-20 [1] CRAN (R 4.1.0)
 systemfonts                         1.0.2      2021-05-11 [1] CRAN (R 4.1.0)
 testthat                            3.0.2      2021-02-14 [1] CRAN (R 4.1.0)
 tibble                              3.1.2      2021-05-16 [1] CRAN (R 4.1.0)
 tidygraph                           1.2.0      2020-05-12 [1] CRAN (R 4.1.0)
 tidyr                               1.1.3      2021-03-03 [1] CRAN (R 4.1.0)
 tidyselect                          1.1.1      2021-04-30 [1] CRAN (R 4.1.0)
 tidytree                            0.3.4      2021-05-22 [1] CRAN (R 4.1.0)
 tinytex                             0.31       2021-03-30 [1] CRAN (R 4.1.0)
 treeio                              1.17.1.992 2021-06-13 [1] Bioconductor  
 tweenr                              1.0.2      2021-03-23 [1] CRAN (R 4.1.0)
 TxDb.Hsapiens.UCSC.hg19.knownGene * 3.2.2      2021-05-22 [1] Bioconductor  
 usethis                             2.0.1      2021-02-10 [1] CRAN (R 4.1.0)
 utf8                                1.2.1      2021-03-12 [1] CRAN (R 4.1.0)
 vctrs                               0.3.8      2021-04-29 [1] CRAN (R 4.1.0)
 viridis                             0.6.1      2021-05-11 [1] CRAN (R 4.1.0)
 viridisLite                         0.4.0      2021-04-13 [1] CRAN (R 4.1.0)
 webshot                             0.5.2      2019-11-22 [1] CRAN (R 4.1.0)
 wget                              * 0.0.1      2020-04-27 [1] local         
 withr                               2.4.2      2021-04-18 [1] CRAN (R 4.1.0)
 xfun                                0.23       2021-05-15 [1] CRAN (R 4.1.0)
 XML                                 3.99-0.6   2021-03-16 [1] CRAN (R 4.1.0)
 xml2                                1.3.2      2020-04-23 [1] CRAN (R 4.1.0)
 XVector                             0.32.0     2021-05-19 [1] Bioconductor  
 yaml                                2.2.1      2020-02-01 [1] CRAN (R 4.1.0)
 zlibbioc                            1.38.0     2021-05-19 [1] Bioconductor  

[1] /home/ygc/R/library
[2] /usr/lib/R/library
> 

```
