###
## The original cluster_plot file had an error which was located at line 62. 
## 1) The code was originally k=min(k,3) and corrected to k=k. This change removes the limitation
## of the script producing valid results upto k=3 therefore k=4,k=5 are now working as intended. k on the left side is a paramater introduced in the loop whereas the k on the right hand side of the equalty is a variable.
## 2) The script returns numbers for silhouette however in the script there is different string assigned to this called silhouette_score. Correcting this change creates consistency when reconciling the script with what the code produces in the terminal.