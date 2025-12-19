This readme file was generated on 2025-12-19 by Jabin Binnendyk

# GENERAL INFORMATION

Title of Dataset: example_data.csv

## Author/Principal Investigator Information
Name: Jabin Binnendyk 
ORCID:https://orcid.org/0000-0002-1491-6373 
Institution: Cornell University 
Email: jdbinnendyk@gmail.com

# DATA & FILE OVERVIEW

## File List: There are 2 folders (data and src).

### Folder: data
Contains a raw and clean data folder, each containing the respective csv file. 

### Folder: src
Contains the script to clean and aggregrate values. 

# Variables in clean -> example data
subj - subject id. 
acc - accuracy score for the GOT. Ranges from 0-10.  
GOT_Est - estimated performance on the GOT. Ranges from 0-5 as participants are asked for above chance estimates.   
conf - average confidence across all GOT trials at the subject level.  
GOT_Estz - z scored GOT_Est. 
confz - z scored conf. 
GOTz - mean value of GOT_Estz and confz.
