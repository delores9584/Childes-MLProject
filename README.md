# Childes-MLProject

This README.md file is a directory of all the files in this repository. 

## Folder Data

* Gillam_info: a combined data file with each row as an individual participant's detailed information. 
* Gillam_scripts: a combined data file with each row as a produced sentence by individual participants. 
* gil_info_update: an updated info data file with all scripts added into the data file. 
* Gillam_fin: the final version of Gillam_scripts for Word-based Analysis. 

## Folder Output

* CombineFiles.ipynb - code for preprocessing and combining scripts and info data. 
* PreliminaryAnalysis.ipynb - code for computing proportional use of POS tags and the preliminary analysis of these proportions to Impairment and Age. 
* WordbasedAnalysis.ipynb - code for creating word embeddings and building neural network models to use embeddings as inputs to predict Impairment and Age. 
* POS analysis-Age.ipynb - code for POS-based analysis. Contains model tunning, selection, feature importance, and ICE plots for Age. 
* POS analysis-Imp.ipynb - code for POS-based analysis. Contains model tunning, selection, feature importance, and ICE plots for Impairment. 
* best_model.h5 - file to store model information using early stopping.
* plot.png - generated plot file. 

## Folder - Figures
This folder stores figures that used for slides, poster, and final report use. Refer to the final report for further information. 
