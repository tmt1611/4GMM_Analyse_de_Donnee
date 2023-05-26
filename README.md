# Introduction
This project is carried out as part of the 4GMM Data Analysis course at INSA Toulouse. Here we study a dataset of the Vélib system (shared bicycle service) in Paris, France. The data are loading profiles of the bicycle stations over one week, collected every hour during the one-week period, from Monday 2nd to Sunday 7th, September 2014 and are stored under the format csv and RData. Extra information about the 1189 station's name, longitude and attitude, and information indicating if the station is on a hill or not, are also available in velibAdds.csv and the variable named 'bonus' of the RData file.
The loading profile of a station, or simply loading, is defined as the ratio of number of available bikes divided by the number of bike docks. A loading of 1 means that the station is fully loaded, i.e., all bikes are available. A loading of 0 means that the station is empty, all bikes have been rented. From the viewpoint of data analysis, the individuals are the stations. The variables are the 168-time steps (hours in the week). The aim is to detect clusters in the data, corresponding to common customer usages. This clustering should then be used to predict the loading profile. 
# Outline:  
In this project, we will: 
- Perform initial exploration data analysis (EDA), e.g., variable identification, univariate analysis, bi-variable analysis, detecting-treating missing values, detecting-treating outliers (or anomalies), visualizing some data samples, …   
- Use Principal Component Analysis (PCA) and try to reduce the dimensions of the problem. 
- Apply 3 different clustering techniques (K-Means, Agglomerative Hierarchical Clustering, Gaussian Mixture models) to group stations into clusters that we can interpret. 
- Compare and choose the best way of defining clusters of stations corresponding to common customer usages. 
- Conclude. 
In this project, we focus on the interpretations of the station clusters and link it to common customer usages. Some technical explanations of the methods are also detailed as proof of our conclusions. Detailed codes and results (in R and Python) are available under the format of Jupyter notebooks (project_velib_R.ipynb and project_velib_python.ipynb).
# Report
Please refer to the pdf file Report_Velib.pdf for detailed report of the project.
