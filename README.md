# BIOSTAT 823 Final Project

This is my final project for BIOSTAT 823. The goal of this study is to compare the efficiency of various matrix algebra computations across base R and RcppEigen.

Below are the dependencies:

R version 4.2.1 (2022-06-23)
Platform: aarch64-apple-darwin20 (64-bit)
Running under: macOS Monterey 12.5

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] ggpubr_0.4.0         reshape2_1.4.4       flextable_0.8.3      foreach_1.5.2       
 [5] microbenchmark_1.4.9 RcppEigen_0.3.3.9.2  forcats_0.5.2        stringr_1.4.1       
 [9] dplyr_1.0.10         purrr_0.3.5          readr_2.1.3          tidyr_1.2.1         
[13] tibble_3.1.8         ggplot2_3.4.0        tidyverse_1.3.2     

loaded via a namespace (and not attached):
 [1] httr_1.4.4          jsonlite_1.8.3      carData_3.0-5       modelr_0.1.9       
 [5] assertthat_0.2.1    googlesheets4_1.0.1 cellranger_1.1.0    yaml_2.3.6         
 [9] gdtools_0.2.4       pillar_1.8.1        backports_1.4.1     lattice_0.20-45    
[13] glue_1.6.2          uuid_1.1-0          digest_0.6.30       ggsignif_0.6.4     
[17] rvest_1.0.3         colorspace_2.0-3    htmltools_0.5.3     Matrix_1.5-1       
[21] plyr_1.8.7          pkgconfig_2.0.3     broom_1.0.1         haven_2.5.1        
[25] scales_1.2.1        officer_0.4.4       tzdb_0.3.0          timechange_0.1.1   
[29] googledrive_2.0.0   car_3.1-1           generics_0.1.3      ellipsis_0.3.2     
[33] withr_2.5.0         cli_3.4.1           magrittr_2.0.3      crayon_1.5.2       
[37] readxl_1.4.1        evaluate_0.18       fs_1.5.2            fansi_1.0.3        
[41] rstatix_0.7.1       xml2_1.3.3          tools_4.2.1         data.table_1.14.4  
[45] hms_1.1.2           gargle_1.2.1        lifecycle_1.0.3     munsell_0.5.0      
[49] reprex_2.0.2        zip_2.2.2           compiler_4.2.1      systemfonts_1.0.4  
[53] rlang_1.0.6         grid_4.2.1          iterators_1.0.14    rstudioapi_0.14    
[57] base64enc_0.1-3     rmarkdown_2.18      gtable_0.3.1        codetools_0.2-18   
[61] abind_1.4-5         DBI_1.1.3           R6_2.5.1            lubridate_1.9.0    
[65] knitr_1.40          fastmap_1.1.0       utf8_1.2.2          stringi_1.7.8      
[69] Rcpp_1.0.9          vctrs_0.5.0         dbplyr_2.2.1        tidyselect_1.2.0   
[73] xfun_0.34   
