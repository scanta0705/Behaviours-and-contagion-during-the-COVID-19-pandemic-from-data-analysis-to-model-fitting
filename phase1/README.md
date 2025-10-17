README - PHASE 1

The Python scripts should be run in this order to ensure correct results for phase 1:
- country.ipynb
- country-us.ipynb
- samplesize.ipynb
- US_epidemiology.ipynb
- coveragetest+CHI.ipynb

As visible from the code, all created CSV files are saved inside a folder named 'csv', providing a clear organization of the files.

The external data are sometimes retrieved via APIs and sometimes come from existing CSV files available on relevant websites. The following links provide the CSV files needed for Phase 1:
- owid-covid-data.csv https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-data.csv
- positive-rate-daily-smoothed.csv https://ourworldindata.org/grapher/positive-rate-daily-smoothed
- face-covering-policies-covid.csv https://ourworldindata.org/grapher/face-covering-policies-covid
- covid-containment-and-health-index.csv https://ourworldindata.org/grapher/covid-containment-and-health-index
- time_series_covid19_US.csv https://github.com/govex/COVID-19/tree/master/data_tables/testing_data

All these CSV files must be placed in the csv folder for the scripts to function properly. During the execution of the Python scripts additional CSV files will also be generated and stored in the same folder. From country.ipynb and country-us.ipynb, two external tables will be generated (named Data and Dataus respectively). These contain CSV files with data retrieved via APIs.

Finally, the most important CSV file is FULL_DATA5_FINALE.csv, which contains the data required for Phase 2.

The lines responsible for saving the images must be commented out or modified to ensure the proper functioning of the code.
