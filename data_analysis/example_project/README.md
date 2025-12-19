This readme file was generated on 2025-12-19 by Jabin Binnendyk

# GENERAL INFORMATION

Title of Dataset: example_data.csv

## Author/Principal Investigator Information
Name: Jabin Binnendyk <br>
ORCID:https://orcid.org/0000-0002-1491-6373 <br>
Institution: Cornell University <br>
Email: jdbinnendyk@gmail.com <br>

# DATA & FILE OVERVIEW

## File List: There are 2 folders (data and src).

### Folder: data
Contains a raw and clean data folder, each containing the respective csv file. 

### Folder: src
Contains the script to clean and aggregrate values. 

# Variables in clean -> example data
subj - subject id. <br>
acc - accuracy score for the GOT. Ranges from 0-10. <br> 
GOT_Est - estimated performance on the GOT. Ranges from 0-5 as participants are asked for above chance estimates.   <br>
conf - average confidence across all GOT trials at the subject level.  <br>
GOT_Estz - z scored GOT_Est. <br>
confz - z scored conf. <br>
GOTz - mean value of GOT_Estz and confz.<br>
