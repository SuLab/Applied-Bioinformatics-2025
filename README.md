# Applied-Bioinformatics-2025

### Getting this repo

In RStudio, create a new project from version control using https://github.com/SuLab/Applied-Bioinformatics-2025.git

### Windows users only: Install Rtools

From https://cran.r-project.org/bin/windows/Rtools/rtools44/rtools.html, click "Rtools 44 installer" link. Click downloaded file to install, use all defaults.

### Install/restore everything else

`renv::restore()`

If you hit issues using renv, then do the following steps instead

install camprotR
* `renv::install("remotes")`
* `remotes::install_github("CambridgeCentreForProteomics/camprotR", dependencies = TRUE)`

install diann
* Must first install g++ (compiler) from https://jmeubank.github.io/tdm-gcc/download/ -- choose the 64+32-bit MinGW-w64 edition version, then restart
* `remotes::install_github("vdemichev/diann-rpackage", dependencies = TRUE)`

for all other packages, you should be able to use `install.packages` as normal.


## Course materials

* [Course Recordings](https://www.dropbox.com/scl/fo/ahddd1ci362ppzm8pcyet/AGp4X15MGMhK0RkTlpR_okc?rlkey=6fpej2sf0so8ppo4lqu5yg73z&st=zymytfcp&dl=0)


### 2025-01-07
* [Overall class intro](https://docs.google.com/presentation/d/1DFdVBRlitwfMhO4pZMOLntDAMrm32WAS/edit?usp=sharing&ouid=101769683166653841618&rtpof=true&sd=true)
* [Introduction to Proteomics; Importing proteomics data into R](https://docs.google.com/presentation/d/1AzBJR_JMnycM37_xtJLqZi4IJxPEpsUZ/edit?usp=sharing&ouid=117620351523798089230&rtpof=true&sd=true)
