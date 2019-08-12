# Development of a Forecasting Model for Tropical Solar Energy Systems Using Support Vector Machines
This repository contains a tropical solar energy forecasting model using support vector machines, developed as part of an accepted research paper at the International Conference on Applied Energy 2019 (ICAE 2019).

## Abstract
The rise of mixed-use buildings has contributed to the sustainable development of cities, but they still lack energy design guidelines. Energy consumption forecasting models have been crucial to the improvement of energy efficiency and sustainability of buildings, but their application to mixed-use buildings have been challenging and less tackled in literature. This study presented a novel forecasting model to predict energy consumption in mixed-use buildings using machine learning techniques. The model integrated k-means clustering algorithm and support vector regression to improve predicting performance. The model was demonstrated to a case study considering mixed-use buildings in a tropical area. Clustering results found major differences in the consumption behavior of building clusters, especially on peaking characteristics. The proposed forecasting model was able to capture these variations due to clustering, leading to an increase in predicting performance. The model also performed within building modeling standards and better than statistical approaches in the literature.

## About the Datasets
The building energy consumption dataset was obtained from Open Energy Information (OpenEI) database. The dataset consists of simulated energy consumption data of 30 buildings, modeled using Energy Plus. The buildings were based from the United States Department of Energy (US DOE) reference buildings, with various types and purposes. The dataset can be accesed [here](https://openei.org/datasets/dataset/simulated-load-profiles-17year-doe-commercial-reference-buildings).

The National Solar Radiation Data Base (NSRDB) is an open dataset of solar radiation and weather data across various locations in the United States. Weather data were acquired from meteorological stations while the solar radiation data were modeled using National Renewable Energy Laboratory's (NREL's) Physical Solar Model (PSM). The dataset was accessed through its application programming interface (API). Documentation on the dataset can be found [here](https://doi.org/10.1016/j.rser.2018.03.003), while the dataset can be accessed [here](https://nsrdb.nrel.gov).

## About the Model Script
The model script was written in MATLAB R2019a using [MATLAB Live Editor](https://www.mathworks.com/products/matlab/live-editor.html), an interactive script editor that enables the model code to be integrated with formatted text and graphics.

## Directory
* [__/ClusteringResults/__](/ClusteringResults/) - contains the .mat files of the results from executing the developed clustering model
* [__/DataPreprocessing/__](/DataPreprocessing/) - contains the .mat files of the imported and pre-processed data
* [__/ForecastingResults/__](/ForecastingResults/) - contains the .mat files of the results from executing the developed forecasting model
* [__/EnergyConsumptionPredictiveModel__](/EnergyConsumptionPredictiveModel.mlx) - contains the .mlx file of the model script written in MATLAB R2019a's Live Editor

## Contact Details
Aaron Jules R. Del Rosario, Graduate Student, Mechanical Engineering Department, De La Salle University (DLSU), Manila, Philippines | [E-mail](aaron_jules_delrosario@dlsu.edu.ph) | [DLSU Mechanical Engineering Department](https://www.dlsu.edu.ph/colleges/gcoe/academic-departments/mechanical-engineering/)
