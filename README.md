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
* (Windows only) install g++ (compiler) from https://jmeubank.github.io/tdm-gcc/download/ -- choose the 64+32-bit MinGW-w64 edition version, then restart
* `remotes::install_github("vdemichev/diann-rpackage", dependencies = TRUE)`

for all other packages, you should be able to use `install.packages` as normal.


## Course materials

* [Course Recordings](https://www.dropbox.com/scl/fo/ahddd1ci362ppzm8pcyet/AGp4X15MGMhK0RkTlpR_okc?rlkey=6fpej2sf0so8ppo4lqu5yg73z&st=zymytfcp&dl=0)


### 2025-01-07
* [Overall class intro](https://docs.google.com/presentation/d/1DFdVBRlitwfMhO4pZMOLntDAMrm32WAS/edit?usp=sharing&ouid=101769683166653841618&rtpof=true&sd=true)
* [Introduction to Proteomics; Importing proteomics data into R](https://docs.google.com/presentation/d/1AzBJR_JMnycM37_xtJLqZi4IJxPEpsUZ/edit?usp=sharing&ouid=117620351523798089230&rtpof=true&sd=true)


### 2025-01-09
* [Data manipulation; Dplyr and EnrichR](https://docs.google.com/presentation/d/1EXqxfV6nAepYD6nMXxSyAppymuyJvTvv/edit?usp=sharing&ouid=117620351523798089230&rtpof=true&sd=true)


### 2025-01-14
* [How to ask for help](https://docs.google.com/presentation/d/1X_A7HeIQ0SYK1iWilKVG3uIArGInNmoN/edit?usp=sharing&ouid=101769683166653841618&rtpof=true&sd=true)
* [Bioconductor](https://docs.google.com/presentation/d/1bd-1Mm4HrUiA7W3KixEDrmEcKA717EFN-oWmOEuySWw/edit?usp=sharing)
* [Data visualization with mixOmics](https://docs.google.com/presentation/d/14J1nxm7Yu7deGskz63wlcH9qgU7iAsJS/edit?usp=sharing&ouid=117620351523798089230&rtpof=true&sd=true)

### 2025-01-16
* [Formatting Data for mixOmics](https://docs.google.com/presentation/d/1ZazO1xg4PBTX7BPGp2RnEppZ-6nlHPGN/edit?usp=sharing&ouid=101769683166653841618&rtpof=true&sd=true)

### 2025-01-21
* [Introduction to MSstats](https://docs.google.com/presentation/d/14hCFWaeSLAZkacpwWwO_STvFpNdBH91g/edit)
* [Git and Github](https://docs.google.com/presentation/d/1xAKv2cfepvKv57Ojcxb0Tvxrjee1skJB0wTP00W3grg/edit)

### 2025-01-23
* [Differential Protein Abundance and Volcano Plots | Capstone Walkthrough](https://docs.google.com/presentation/d/1xuFXC3QBQiVE6qRZzaKchKLOmufJBWrY/edit?usp=drive_link&ouid=117620351523798089230&rtpof=true&sd=true)

### 2025-01-28
* [Genotype-Phenotype Associations - Intro](https://docs.google.com/presentation/d/1CcGaAceNjFeHXAEtAsvs0kI32zChtmsM/edit?usp=drive_link&ouid=117620351523798089230&rtpof=true&sd=true)
