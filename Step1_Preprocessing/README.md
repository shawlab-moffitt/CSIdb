# CSIdb 

## Reference Script for extracting junction from Recount3
https://github.com/shawlab-moffitt/Splice-Junction-Filter-Workflow

## Input 
### 1. Specify Output Directory
### 2. Specify the project name (from recount3)
### 3. Expression cutoff (in junction count per million reads
### 4. Min number of samples with the expression.

User can visualize the study from https://jhubiostatistics.shinyapps.io/recount3-study-explorer/

A GTEx and BM junction list can be used as a filter for tumor specific junction: http://shawlab.science/shiny/GTEx_AMLBM_JunctionList/GTEx_AMLBM_JxnPresent_Vector.RData


## Output 
### 1. Normalization
### 2. Summarizing junction count per million read.
### 3. BED File of the final filtered junction list
