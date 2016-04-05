# pan-cancer-analysis
This repository contains all the codes with which pan-cancer analysis was made.

###Used Data:
Different data sources were used to retrieve data for this analysis:

 -Cancer expression data from the release_19 of ICGC (https://dcc.icgc.org/releases/release_19/Projects) 
 -Transcription factor binding sites (TFBS) from Ensmbl's Biomart (GRCh38.p5: http://www.ensembl.org/biomart/martview/b93767e77d50bf613a6071fabce444af)

###Folder format
In order to run the analysis script, the folder which contains the data must follow some rules.

 -Every cancer has its own folder in the main directory. These folders include the expression file for each cancer and the clinical data   
 -The main folder also must contain an anotation file which includes the TF-target pairs. This file was made overlapping the coordinates of the TFBS and the promoter regions of coding genes.


