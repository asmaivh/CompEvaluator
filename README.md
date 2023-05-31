# CompEvaluator
CompEvaluator is an open source software that computes 12 performance assessment measures to evaluate a protein complex prediction method against a benchmark protein complexes.

# Compevaluator

## DESCRIPTION:

CompEvaluator is an open source software that computes 12 performance assessment measures to evaluate a protein complex prediction method against a benchmark protein complexes.

The 12 performance assessment measures include:
	Precision, Recall(Sensitivity1), F1-Measure
	Sensitivity2, PPV, Geometric Accuracy
	HM_CL, HM_CO, Homogeneity
	Jaccard_CL, Jaccard_CO, Jaccard_Fmeasure

	  
INTERFACES   :     GUI

DEPENDENCIES :     JDK 8.0


## Input & Output Files
      
Input:
         This program accepts a text file as input data with the following format:
         "Complex_id;Complex_name;subunits__UniProt_IDs"

Output:
          The output is a text file contains the result of the 12 performance assessment measures.	




## How to execute CompEvaluator 

You should do the following steps:

	1- Put benchmark complex data set into software folder
	   (Note that data set should be in this format : Complex_id; Complex_name; subunits__UniProt_IDs )
	2- Insert prediction clusters data set into software
	   (Note that data set should be in this format : Complex_id;Complex_name;subunits__UniProt_IDs )
	3- Click "Start" button to compute the selected measures this options 
	 
	4- Click "Save result" to store the results.
	
Copyright 2017 - Laboratory of Database Reaserch Groups ( DBRG ), University of Tehran, Tehran, IRAN.
All right Reserved.   
Enjoy!



