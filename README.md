# Applied-Bioinformatics-2025

## getting this repo

In RStudio, create a new project from version control using https://github.com/SuLab/Applied-Bioinformatics-2025.git


## installing packages

renv::install("remotes")

### Camprot

remotes::install_github("CambridgeCentreForProteomics/camprotR", dependencies = TRUE)

### Rtools (windows users only)

From https://cran.r-project.org/bin/windows/Rtools/rtools44/rtools.html, click "Rtools 44 installer" link. Click downloaded file to install, use all defaults.


### install/restore everything else

renv::restore()
