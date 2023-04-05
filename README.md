# Waveheight Prediction

Predictics daily maximum observed waveheight on northshore Oahu from offshore buoy data. This project is based on the project: https://github.com/benfreeston/surfline_recruitment_project.

There are two notebooks, `data-processing.ipynb` cleans and processes the data as well as makes exploratory plots, and `prediction-model.ipynb` builds a model to predict `Obs` from various features.

`data` folder contains all the raw data and `processed_data.csv` is the output of the first notebook `data-processing.ipynb`.


### Data Descriptions

- Offshore buoy data descriptions: https://www.ndbc.noaa.gov/measdes.shtml
- Observed wave heights data description: https://www.nodc.noaa.gov/archive/arc0012/0001754/1.1/data/1-data/meta/data_file_format_description.txt
