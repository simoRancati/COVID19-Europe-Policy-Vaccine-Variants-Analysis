## COVID19-Europe-Policy-Vaccine-Variants-Analysis
This repository contains the code for replicating the analysis presented in the paper titled "A Country-Level Comparative Study on the Impact of Containment Policies, Vaccination Strategies, and Virus Variants during the COVID-19 Pandemic in Europe."

## Requirements and installation

**Dependencies**
**Python** scientific stack: 
1. pandas <code>pip install pandas==1.5.3</code>
2. numpy <code>pip install numpy==1.24.1</code>
3. statistics <code>pip install statistics==1.0.3.5</code>
4. scipy <code>pip install scipy==1.10.1</code>
5. matplotlib <code>pip install matplotlib==3.8.3</code>
6. scikit-learn <code>pip install scikit-learn==1.2.1</code>
7. biopython <code>pip install biopython==1.80</code> 

**R language**:
1. BiocManger <code>install.packages("BiocManager")</code>
2. Biostrings <code>BiocManager::install("Biostrings")</code>
3. stringr <code>install.packages("stringr")</code>
4. vroom <code>install.packages("vroom")</code>
5. Matrix <code>install.packages("Matrix")</code>
6. dplyr <code>install.packages("dplyr")</code>
7. ggplot2 <code>install.packages("ggplot2")</code>
8. lme4 <code>install.packages("lme4")</code>
9. lubridate <code>install.packages("lubridate")</code>
10. mlVAR <code>install.packages("mlVAR")</code>
11. pheatmap <code>install.packages("pheatmap")</code>
12. plm <code>install.packages("plm")</code>
13. plyr <code>install.packages("plyr")</code>
14. pompom <code>install.packages("pompom")</code>
15. psych <code>install.packages("psych")</code>
16. readr <code>install.packages("readr")</code>
17. reshape2 <code>install.packages("reshape2")</code>
18. tidyr <code>install.packages("tidyr")</code>
19. tidyverse <code>install.packages("tidyverse")</code>
20. zoo <code>install.packages("zoo")</code>

Python version <code>[3.8](https://www.python.org/downloads/release/python-390/)</code> and R <code>[4.4.0](https://cran.r-project.org/bin/windows/base/)</code> are required. 

## Data
The <code>Data</code> folder contains the necessary CSV files for the analysis. These Folder include:
1. <code>Death.csv.zip</code>: This file contains data on the weekly COVID-19 death counts across various nations.
2. <code>Hospital.csv.zip</code>: This file includes data on weekly hospitalizations due to COVID-19 in different countries.
3. <code>Vaccine_EU.csv.zip</code>: This dataset provides information on COVID-19 vaccinations across different nations.
4. <code>owid-covid-data.csv.zip</code>: This file contains the weekly stringency index data for various countries, indicating the level of government responses.
5. <code>metadata.csv</code>: To use this file, you must register with the <code>[GISAID](https://gisaid.org/)</code> database and download the corresponding TSV file.

## Preprocessing

