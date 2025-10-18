README -Phase 3

Assessing_supepression_measures.ipynb is a file taken from previous work in the literature (https://github.com/daniele-proverbio/assessing_strategies/tree/master) and was used to obtain data that were then manually inserted into the three files Austria.ipynb, Denmark.ipynb, and Switzerland.ipynb

The Python scripts must be executed in the following order to ensure correct functionality and consistency with the thesis structure:
- datasetcreation.ipynb
- modellazionemanuale.ipynb
- Assessing_supepression_measures.ipynb
- Austria.ipynb
- Denmark.ipynb
- Switzerland.ipynb

For the proper functioning of the code, it is necessary to create a folder named 'csv' containing all the initial CSV files. This folder will also automatically store the CSV files generated during the execution of the scripts, which are needed to propagate information between the different programs.

The following datasets are required to obtain the data needed for Phase 3, along with their respective sources:
  - cs_long_v1.csv e cd_long_v1.csv https://www.icpsr.umich.edu/web/ICPSR/studies/39206/versions/V3
  - covid-containment-and-health-index.csv https://ourworldindata.org/grapher/covid-containment-and-health-index
  - owid-covid-data.csv https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-data.csv
  - face-covering-policies-covid.csv https://ourworldindata.org/grapher/face-covering-policies-covid

Before running the scripts, the code lines responsible for saving figures must be either modified or commented out to ensure the code executes correctly.

The csv folder already contains the dati.csv file obtained after integrating the other files. Therefore, it is possible to run modellazionemanuale.ipynb, Austria.ipynb, Denmark.ipynb, and Switzerland.ipynb directly if desired.
