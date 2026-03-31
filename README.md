Flow cytometry project using Rstudio

Dataset: Experiment name "Mobilization of cells through acute exercise in metabolic syndrome patients" from flowrepository.org 

#conpensate data (essential step in the analysis of multicolor panels --> corrects for the overlap of fluorescent signals between different channels)

#Quality check (Flow Rate Check , Signal Acquisition Check, Dynamic Range Check)
![Flow_Rate_Plot](flow_rate_plot.png)
![Signal_Plot](signal_plot.png)
![Dynamic_Plot](Dynamic_plot.png)

#Transformation (convert skewed data into a more normally distributed form)

#Visulaize the results using ggcyto
![SSC_FSC_Plot](SSC_FSC_plot.png)
![Markers_Plot](markers_plot.png)
#Gating (Cell Population Identification, Noise Reduction, Analysis Simplification, Quantitative Analysis,Sequential Gating)
![C1_Before_Plot](c1_before_plot.png)
![C1_After_Plot](c1_after_plot.png)
![M1_After_Plot](m1_after_plot.png)
![R1_After_Plot](r1_after_plot.png)
#statistics

