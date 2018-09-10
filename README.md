# Org_Type_Classifier
This program makes use of https://github.com/spendnetwork/orgtype-classifier and determines whether or not an organisation is a company or not a company, based on the output of the classifier having taken a string containing the name of an organisation.

The module allows for the use of argument parsing, as follows :

When running the program from the terminal (ensuring connection to the localhost on port 8080 to the classifier above), the following arguments can be called :

--dir : being the directory where your data is saved (the default is '' i.e. the current location)

--datafile : being the csv file name (default is set to 'sample_orgs.csv')

Currently the program assumes the cloned orgtype-classifier folder is in the same directory as the core python file.

