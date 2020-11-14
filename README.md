# COVID
- Connect to bigquery-public-data project on BigQuery before runing the notebooks
- an external data source is used for obtaining the population details of each country
- infectionrate_vs_population.xlsx is the file which should be in same directory as infection_rate.ipynb 
- make sure all the packages listed in requirement.txt are installed
- go to all .ipynb files- Run -> Run all 

- infection_rate.ipynb contains code for ploting infection_rate vs population and infection_rate vs testing
- Fatalities.ipynb file contains code for ploting fatalities/cumulative deceased in each country
- cluster_breakout.ipynb contains code for ploting weekly cumulative confirmed cases in each country
- predictor.ipynb contains Machine learning models for predicting the confirmed cases for next 90 days