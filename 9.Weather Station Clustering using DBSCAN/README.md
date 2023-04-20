# Weather Station Clustering using DBSCAN
The objective here is to cluster the location of weather stations in Canada.DBSCAN can be used here, for instance, to find the group of stations which show the same weather condition.

**Tools used**- Jupyter notebook 

**Language and Packages uesd**- Python (Pandas,Numpy,Matplotlib,Sklearn)

## Data Cleaning
The data is imported and checked troughly for any irregularities and the dirty data is cleaned for smooth exploration .

## DBSCAN Model
The data is preprocessed to create the model.

The model produced 3 main clusters with the majority of stations in those excluding outliers.

- Cluster 0 : Has a mean temperature of 6.2°C and a maximum and minimum temperature of 13.2°C and -1.5°C repectively in lattitude=50 degrees and longitude=-123 degrees .

- Cluster 3 : Has a mean temperature of -13.7°C and a maximum and minimum temperature of 4.3°C and -30.4°C repectively in lattitude=52.17 degrees and longitude=-108 degrees.

- Cluster 5 : Has a mean temperature of -16.4°C and a maximum and minimum temperature of -2.9°C and -31.3°C repectively in lattitude=45.89 degrees and longitude=-74 degrees .

The model is also used to predict the cluster of an imaginary weather station A .
