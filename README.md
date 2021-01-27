# Coursera_Capstone
Repository for course "Applied Data Science Capstone" on Coursera.

This project identifies the best locations to set up a series of 5 tourist E-Scooters stations in the central area of Paris. 

Best locations are based on the distribution of tourist attractions within a radius of 10km from Paris center. 

The list of venues is collected from FourSquare API and filtered for highly rated venues according to number of user likes and average rating. 

An unsupervised learning (K-Means clustering) was applied to group venues into 5 clusters. Coordinates of the clusters’ centroids are reversed geocoded to recommend 5 physical addresses in Paris where the E-Scooter stations should be set up.

See [project report](../master/CapstoneReport-Best%20locations%20to%20set%20up%20tourist%20E-Scooter%20stations%20in%20Paris.pdf) for details.
