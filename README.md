[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)

# Dimension_reduction, Feature selection, anomaly detection and association analysis.
This repository consists of 3 jupyter notebooks with results and technical aspects of the following:

## 1. Dimension reduction and feature selection
## Identify which individuals visiting our clients site are likely to click on her ad.
First notebook aims to  answer the following research question "A Kenyan entrepreneur has created an online cryptography course and would want to advertise it on her blog. She currently targets audiences originating from various countries. In the past, she ran ads to advertise a related course on the same blog and collected data in the process. She would now like to employ your services as a Data Science Consultant to help her identify which individuals are most likely to click on her ads. 


### Approach 1: Dimension reduction
We will analyse the data and determine which of the following algorithms to use that is t-SNE or PCA. With the identified algorithm we will then reduce the dataset dimensions.

### Approach 2: Feature selection. 
We will use filter methods and and feature ranking methods to determine which features are most imporaant to use.

After both approaches we will give our conclusions and recommendations.

# 2. Anomaly detection.
## Check whether there are any anomalies in the given sales dataset.
The second notebook aims to find anomalies within the dataset provided.

### Approach 1: Using anomalize package.
We will use the anomalize package to plot and display anomalies within the data provided.

# 3. Association analysis
## Create association rules that will allow you to identify relationships between variables in the dataset. 
The third notebook aims at finding rules in the provided dataset.

### Approach 1: Using the arules package.
We will perform basic data exploration, find the rules and plot the rules. 
We will then give our conclusions and recommendations

## Getting Started.

To get a copy of this solution fork the repository. On the upper right there is a Fork button click on it, then after this is successfull click on git clone or download to get a local copy on you machine. 

## Overview.

This repository contains the technical aspects of Data Science Core IP submission week 14 as outlined above. The project applies the techniques learnt in R. The notebook can be accessed in the repository.

## Files in the Repository.

The repository contains the following files/folders:

    *license: MIT
    *google collab notebook 1: Dimensionality reduction_in_R.ipynb
    *google collab notebook 2: Associative_analysis_in_R_IP.ipynb
    *google collab notebook 3: Anomaly_Detection_in_R.ipynb
    *README: This README.

## Packages

The following packages are necessary to run the cells in notebook 1:

    DataExplorer
    tidyverse
    ggplot2
    data.table
    gridextra
    fbasics
    dplyr
    corrplot
    CatEncoders
    caret
    factoextra
    FSelector
 
  
  The following packages are necessary to run the cells in notebook 2:
  
     arules
     arulesViz
    
   The following packages are necessary to run the cells in notebook 3:
   
     anomalize
     tibbletime
     tidyverse
     tibble
     dplyr
     DataExplorer
    

### Prerequisites
1. A browser to access the google collabs.
2. Google collaboratory which can be accessed through the [link](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwius97P4tjpAhVwxoUKHU9jDQQQFjAAegQIBhAC&url=https%3A%2F%2Fcolab.research.google.com%2F&usg=AOvVaw3A5aPK2kLFzKOzb6sOckVw)


### Installing

Install a browser of your choice preferabbly google chrome.


## Built With

* [R version 3.6.3]- The R version used in collabs
* [Google Collabs](colab.fan/r) - google collabs notebook




## Authors

* **Antony Mwaura Ngige** - *Initial work* 


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to my mentors and peers
* Inspiration
