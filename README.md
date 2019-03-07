# aglB-WGS-growth
## Data and analysis of whole genome sequencing and growth of _∆aglB_ strain in _Hbt. salinarum_
### Corresponds to the paper "N-glycosylation is required for archaellin transcription and translation, archaella assembly and cell motility in _Halobacterium salinarum_" by Marianna Zaretsky, Cynthia L. Darnell, Amy K. Schmid, and Jerry Eichler.

### Dependencies
#### Click on the links below for downloads, documentation, and dependencies of each package

#### Whole genome sequencing (WGS) dependencies
* Python v 2.7
* [Anaconda](https://docs.anaconda.com/anaconda/install/) 
* [FastQC](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/) for quality control.
* [TrimGalore!](https://www.bioinformatics.babraham.ac.uk/projects/trim_galore/) for trimming adaptors.
* [breseq](http://barricklab.org/twiki/pub/Lab/ToolsBacterialGenomeResequencing/documentation/index.html) for read mapping and analysis of mutations.
     * breseq publication: Deatherage, D.E., Barrick, J.E. (2014) Identification of mutations in laboratory-evolved microbes from next-generation sequencing data using breseq. Methods Mol. Biol. 1151: 165–188. 
    
#### Growth data calculation dependencies
* [Rstudio v1.1.463](https://www.rstudio.com/products/rstudio/download/) coding environment
* R packages 
    * plyr v 0.7.8
    * tidyr v 0.8.2
    * dplyr v 0.7.8
    * tibble v 1.4.2
    * ggplot2 v 3.1.0
    * tinytex v 0.9
    * data.table v 1.12.0

### Instructions

#### WGS
* Install dependencies
* Open Jupyter notebook "aglB_genome_sequencing.ipynb" in Anaconda navigator by clicking "root > open with Jupyter notebook"
* Run the notebook using the fastq data file in the data folder

#### Growth data
* Install dependencies using the command 'install.packages()'
* Open Rmd file 
* Run the file using data and metadata files in the data folder

