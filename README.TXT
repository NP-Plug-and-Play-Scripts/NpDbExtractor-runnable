========================
NpDbExtractor Discription
========================

This project is made to connect to a Natural product database and extracted information based on the input (sub/super)classes.

By using a gui created with Java the program connects to a database of choice and after selecting the (super/sub) 
classes you want you can then search to get all the entries for those set values. 
The results are then displayed in a table on the screen where the results can be reviewed.
If the user is satisfied with the results they can then be saved This gives the user the results in a
csv file, which can then be used for further research. 
Currently the tool only gives you the ID and the SMILES string back in the csv this can be changed in
the code however found at https://github.com/NP-Plug-and-Play-Scripts/NpDbExtractor. 
The tool was primarily made to be used for the cfm-id pipeline which requires a csv input containing the ID and SMILES string. 

To run the project from the command line, go to the folder containing these files and
type the following:

java -jar "NaturalProductsDbGui.jar" 

To distribute this project, zip up the folder (including the lib folder)
and distribute the ZIP file.
