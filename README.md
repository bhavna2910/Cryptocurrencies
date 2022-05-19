# Cryptocurrencies
## Analysis Overview
The purpose of this project is to use unsupervised machine learning to analyze a database of cryptocurrencies and create a report including the traded cryptocurrencies classified by group according to their features.
This classification report could be used by an investment bank to propose a new cryptocurrency investment portfolio to its clients.
We use the following methods for the analysis:
* preprocessing the database,
* reducing the data dimension using Principal Component Analysis,
* clustering cryptocurrencies using K-Means,
* visualizing classification results with 2D and 3D scatter plots.

## Results
### Clustering Cryptocurrencies using K-Means - Elbow Curve
Produced the elbow curve below using the K-Means method iterating on k values from 1 to 10. (Refer Image- Deliverable4-d)
The best k value appears to be 4 so we would conclude on an output of 4 clusters to categorize the crytocurrencies.

### Visualizing Cryptocurrencies Results
**3D-Scatter plot with clusters**  (Refer Image- Deliverable4-a)
This 3-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.

**2D-Scatter plot with clusters**  (Refer Image- Deliverable4-e)

Plotting the scatter plot from two cryptocurrency features directly does not efficiently segregate the different classes. Then using the PCA algorithm is the right method for better visualizations.


**Tradable Cryptocurrencies Table**   (Refer Image- Deliverable4-c)

Most of the cryptocurrencies are part of class #0 and #1.

## Summary
Have identified the classification of 532 cryptocurrencies based on similarities of their features.
Particularities of each group need to be analyzed to determined their performance and potential interest for the investment bank's clients.


