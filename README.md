**Normalisation_SCFAs**

Code for reproducing the statistical analysis and figures published at “Normalisation of short-chain fatty acid concentration by bacterial count of stool samples improves discrimination between eubiotic and dysbiotic gut microbiota samples”. The code within the R markdown file (Code_analysis_and_plots.Rmd) is organised in the following order:
-	Bacterial count analysis (including preliminary tests and the density plot of the total bacterial count)
-	Analysis of sample stability
-	Normalisation of SCFAs levels (and the boxplots comparing eubiotic and dysbiotic patients)
-	Density plots and ROC curves of SCFAs (acetate, propionate and butyrate)
-	Supplementary materials 

The script automatically access the necessary data once the working directory is set to the github folder location. You can manually modify it in the first lines of the .Rmd file.
