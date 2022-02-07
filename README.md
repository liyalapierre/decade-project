# decade-project

## Description of decade-project

Contains data and code involved in producing the The Decade Project's 2019 maps. 

## Description of files in decade-project

"Firms_2018.xlsx" contains the number of firms for each state by each demographic group of interest. This data was from the 2019 Annual Business Survey conducted by the US Census Bureau, which contains data from the 2018 calendar year. This data has been proccessed from it's original state to contain only the data of interest. 

"Firms_2019.csv" is the data from the 2020 Annual Business Survey conducted by the US Census Bureau, which contains data from the 2019 calendar year. This data is in it's original form downloaded from the US Census Bureau website, and as such, requires cleaning to find the information we are interested in and make further calculations.

"Population_2018.csv" is the data from the 2019 Census Bureau Population Estimates. This data is in it's original form downloaded from the US Census Bureau website, which requires cleaning to find the information we are interested, join it with our firms data, and make further calculations. 

"Data_Cleaning_Code_2019_Maps.Rmd" is the R Markdown file that contains the code involved in cleaning datasets, joining datasets, making calculations from the data, and retrieving the needed information from the combined dataset. The outputs of this code are two csv files: "tableau.csv" and "tableau_change.csv". These two csv files are used in producing our Tableau maps. 
