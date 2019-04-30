Package for analysing heterogeneous network data

Consists of:

mixglasso - Mixture Graphical Lasso

ggm_gsa - Graphical Gaussian Model Gene Set Analysis

DiffNet and DiffRegr - Statistical Test for difference in network and regression models.

Plotting and exporting - Convenient display and analysis of results.

Easy installation from github: 

    devtools::install_github('FrankD/nethet')

Also available on Bioconductor:

    if (!requireNamespace("BiocManager", quietly=TRUE))
        install.packages("BiocManager")
        
    BiocManager::install("nethet")

