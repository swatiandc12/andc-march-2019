# andc-march-2019

## Install R 3.5
```{shell}
# Ubuntu
sudo add-apt-repository ppa:marutter/rrutter3.5
sudo apt-get update
sudo apt-get install r-base
```
## Install RforProteomics
```{R}
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("RforProteomics", version = "3.8")

``` 