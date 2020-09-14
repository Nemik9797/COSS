# COSS
// This is author's work by Roman Adamenkov on topic "Comparison of spatial 
// structures by method of compare symbolic sequences or it's short name  
// ------------------Comparison Of Spatial Structures  <C O S S>-------------------

<=====================> README <=====================> 

All files of this archive must be unzipped and put together in a separate folder

A brief description of the contents of the archive:
	"avg_functions.txt" - the file contains information about the zoning of the area for determining spatial angles encoding protein sequences
	"ScalesMatrix_ALL.txt" - calculated local alignment matrix

The COSS_v4e0_fast_compare.exe program has 4 required input parameters:
	1) pdb protein code (this protein will be compared with all other proteins in the folder (parameter No. 2))
		example - "4mbn"
	2) full path to the folder containing the pdb files required for comparison
		example - "D: \ COSS_v4 \ pdbfiles \"
	3) the total number of compared proteins in the folder (parameter No. 2)
		example - "157"
	4) flag parameter (specify 1 for pdb4mbn.ent format or specify 0 for 4mbn.pdb format)
		example - "1"

Then enter the start command, for example: "COSS_v4e0_fast_compare.exe 4mbn D:\COSS_v4\pdbfiles\ 157 1"

The information message "Stage: D O N E" will appear after successful completion of the program.
The following files will appear in the program folder:
	"LocalTraceback_4mbn.txt" - technical file
	"Rejects_4mbn.txt" - names of unread pdb files
	"results_4mbn.txt" - a detailed file with the results of alignments
	"xml_results_4mbn.txt" - brief information about alignments in the form of a delimited table
	
