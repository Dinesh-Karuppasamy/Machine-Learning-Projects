# Hierarchical Clustering on Vehicle Dataset
An automobile manufacturer has developed prototypes for a new vehicle. Before introducing the new model into its range, the manufacturer wants to determine which existing vehicles on the market are most like the prototypes--that is, how vehicles can be grouped, which group is the most similar with the model, and therefore which models they will be competing against.

**Tools used**- Jupyter notebook 

**Language and Packages uesd**- Python (Pandas,Numpy,Matplotlib,Sklearn,Scipy)

## Data Cleaning
The data is imported and checked troughly for any irregularities and the dirty data is cleaned for smooth exploration .

## Hierarchical Clustering Model
The data is preprocessed to create the model.

The model produces 6 clusters out of which we have 3 main clusters with the majority of vehicles in those.

**Cars (Type=0):**

- Cluster 1: with almost high mpg, and low in horsepower.

- Cluster 2: with good mpg and horsepower, but higher price than average.

- Cluster 3: with low mpg, high horsepower, highest price.

**Trucks (Type=1):**

- Cluster 1: with almost highest mpg among trucks, and lowest in horsepower and price.

- Cluster 2: with almost low mpg and medium horsepower, but higher price than average.

- Cluster 3: with good mpg and horsepower, low price.

Later the model is also used to predict the type of an imaginary vehicle.
