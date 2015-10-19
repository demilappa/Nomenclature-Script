List of files that can be found in this repository:

--assign_identifiers.py:		python script to break down GEM model to its basic components
--names.tsv:				all the metabolite names in ChEBI database
--mets.tsv				A .tsv format file, parsed from a GEM model, containing Metabolites(In this case Metabolites from the original HMR2 model)
--ChEBI_KEGG_conversion_list-tsv:	flat file including all the metabolites' chemical formulas annotations in ChEBI database
--ChEBI_KEGG_conversion_list-tsv:       flat file including all the metabolites' ChEBI ids and their respective InChi ids	

INPUT:  A .tsv format file, parsed from a GEM model, containing Metabolites
OUTPUT: A .tsv file containg metabolites ids, CHeBI and InChi Identifiers

COMMAND LINE:

	1. make the file executable:	chmod +x assign_identifiers.py
	2. type the command:		./assign_identifiers.py						# The nomenclature assignment can be seen in your screen
	4. type the command:		./assign_identifiers.py > <filename_for_model_components>.tsv	# The nomenclature assignment can be stored in a .tsv file

  
