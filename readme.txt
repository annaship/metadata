Purpose of the survey:
Ideally we want to create a table to show relationships between names/units currently used by scientists and a standard ones. For example, some uses "ammonium" and some - "Ammonium_NH4". To compare data across datasets and projects we want to let the database know, that those two are the same parameter. Or to measure "calcium" some scientists uses "milligramPerLiter"  and others - "partPerMillion". That would be good to have possibility to convert the data to a common unit and compare them.

To accomplish that we need to know 
1) which names represent the same parameter,  
2) what do you think will be a "universal", "standard" name for those,
3) which unit is appropriate. 

A valid name should has only lowercase letters and underscores and should be from MIMARKS, where possible. For units that would be correct from MIMARKS point of view to use a SI unit (where applicable).

An "units_review" spreadsheet has an information to be reviewed. Rows sorted alphabetically by Parameter Name, but yellow fields contain "clusters" of names we guess are the same, so there the alphabetical order is broken.
 
Columns are:
Parameter Name	-	current parameter name, as in vamps database
Suggested Name	-	suggested name, if we cannot find an appropriate "standard" name within MIMARKS.
MIMARKS Standard Name	-	suggested "standard" name. On a left click a drop-down menu of MIMARKS names could be used by clicking down arrow button on the right border of a cell.
Questions
Project Count	-	how many projects use this parameter name
Current unit	-	current unit, as in vamps database
Valid Unit (SI where applicable)	-	suggested unit
MIMARKS Expected value	-	additional information about suggested unit

Some colors are used to mark our guesses. Yellow - for what we think should have the same parameter name. Blue - for what we suggest for all yellow cells just above. Grey - names should be renamed and reconciled with another.

A "projects_info" spreadsheet contain an information which project uses a parameter name.

A "MIMARKS" and "MIMARKS_environmental_packages" spreadsheets are copied from MIMARKS checklist (http://gensc.org/gc_wiki/index.php/MIENS#Submission_of_MIMARKS_data_to_GenBank_and_ENA) for additional information.

At the end:
1) "MIMARKS Standard Name" OR "Suggested Name"  should be filled out for every parameter (or "parameters cluster");
2) Parameters which were mistakenly grouped with other should be marked by removing yellow color on a row(s);
3) "Valid Unit" should be filled out for every parameter (or "parameters cluster");
3a) For all “concentration” units please indicate, if it is an “amount-of-substance concentration” or a “mass concentration”					
amount-of-substance concentration	-	mole per cubic meter			
mass concentration	-	kilogram per cubic meter			
					
