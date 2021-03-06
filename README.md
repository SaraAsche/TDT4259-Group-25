# TDT4259-Group-25
This GitHub provides the raw material as well as code and analysis ran by group 25 in the course TDT4259. The project has the aim of investigating which policies and restrictions affected COVID-19 mortality from the start of 2020 to October 2021. The cleaned and integrated dataset can is placed in [combinedCovidData.xlsx](combinedCovidData.xlsx).

# Analyses in R on correlation
The main analysis are written by Sara Johanne Asche in R-markdown and can be found in [Wilcoxon.ShapiroWilks.Spearman.Rmd](Wilcoxon.ShapiroWilks.Spearman.Rmd). These analysis includes plotting of boxplots, Spearman rank correlation tests, Shapiro-Wilk tests, and Wilcoxon pairwise tests. The matrix output from the Spearman analysis can be seen in the excelfiles marked either "p_valuecorrelation" + country name for p-value and "correlation" + country for the rho value. One example is the [Rho correlation coefficient for Spain](correlationSpain.xlsx) as well as [associated p-values](p_valcorrelationSpain.xlsx). 

# Analysis in Jupiter notebook on mortality shift
The analysis of the 21 day mortality shift are done by Anna Katharina Herrmann and written in Jupyter notebook. They can be accessed in [Mortality_Shift.ipynb](Mortality_Shift.ipynb). One example of a 21 day shift in mortality can be seen for [Germany after 21 days](df_Germany_after21days.csv). 

# Raw data
The raw data extracted from the different sources as described in the report can be found in the [rawData folder](.\rawData). 

# Illustrations from analyses
Illustrations from the different analyses can be found in the [analyses folder](./analyses)
