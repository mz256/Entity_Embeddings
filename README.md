# Random forest + Entity embeddings

## Summary

A series of notebooks covering Entity Embeddings for categorical variables. Specifically, these kernels show how we can learn categorical embeddings by training a feed-forward DNN on high-performance gpu-enabled hardware, and later exploit them to boost the performance of other algorithms, such as tree-based ensembles (here we use a random forest), which can be trained on more lightweight infrastructure.

## NB

The embeddings were learnt previously in [this notebook](https://github.com/mz256/ashrae_energy_forecast/blob/main/notebooks/03b_tabularNN_train.ipynb), as part of the ASHRAE competition on Kaggle.
