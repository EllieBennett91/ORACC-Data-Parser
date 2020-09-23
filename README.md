# ORACC-Data-Parser
Code based on work by Niek Veldhuis' Computational Assyriology projct (https://github.com/niekveldhuis/compass) to turn json files from ORACC project into data for linguistic analysis.
This takes the raw data, and returns a .csv file with one text per line. Each line has ORACC's ID number at the beginning to aid in identification. You can filter the results according to the metadata associated with the JSON file, and remove the duplicates from the project data.
This version has the filters of languge = 'Akkadian' and period = 'Neo-Assyrian'.
