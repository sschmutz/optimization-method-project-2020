# Keyword Clustering
> implementing an optimisation method

[![Netlify Status](https://api.netlify.com/api/v1/badges/6244650b-6a5f-400e-9d84-b93250102209/deploy-status)](https://keyword-clust.netlify.app) 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sschmutz/optimization-method-project-2020/master?urlpath=rstudio)

The R code was written in a [R Markdown document](https://github.com/sschmutz/optimization-method-project-2020/blob/master/keyword_hclust.Rmd), compiled into HTML and deployed on Netlify which should make it simple to follow it without the need of executing it yourself.  
If this is however preferred, following section lists two options to reproduce the results.


## Executing code
### using Binder
The code can be executed by following the [Binder link](https://mybinder.org/v2/gh/sschmutz/optimization-method-project-2020/master?urlpath=rstudio).  
It takes a while (approximately 20min) to start the binder session. Once done, the RStudio interface is visible.  
Open `index.Rmd` from the Files pane. Each Chunk can be run separate `Run Current Chunk` or all `Run All`.


### using local RStudio
If you wish to run the code locally, the script can be downloaded from GitHub running following command in a terminal

```sh
git clone https://github.com/sschmutz/optimization-method-project-2020.git
```

or [download the ZIP folder](https://github.com/sschmutz/optimization-method-project-2020/archive/master.zip).

[R](https://stat.ethz.ch/CRAN/) and [RStudio](https://rstudio.com/products/rstudio/download/#download) need to be installed.

Open `index.Rmd`, install the required packages by running `install.packages(c("readr", "dplyr", "tidytext", "tidyr", "purrr", "usedist", "clusteval","dendextend", "ggplot2", "patchwork"))`.  
Each Chunk can be run separate `Run Current Chunk` or all `Run All`.
