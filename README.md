# andc-march-2019

## Install R 3.5
```{shell}
# Ubuntu
sudo add-apt-repository ppa:marutter/rrutter3.5
sudo apt-get update
sudo apt-get install r-base
```

## Download this repo
```{shell}


# go to home folder
cd ~

# fork this repo first from your github account

# go to the clone
git clone https://github.com/rintukutum/andc-march-2019.git

# go to the folder
cd andc-march-2019/

# go to session folder
cd session-01/

# open a file name
gedit student-details.md
``` 
## Install RforProteomics
```{R}
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("RforProteomics", version = "3.8")

``` 
