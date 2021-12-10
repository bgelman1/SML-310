# SML-310

This project creates a set of statistical models that can predict turnout for the Texas statewide primary elections (Gubernatorial and Senate races) in 2018, on the county level. 

It is broken up into 3 main folders:
1. Data-Retrieval
This folder contains code for retrieving census data, cleaning and merging it with election data, and conducting some EDA.

  a. Census_Data_Retrieval.ipynb: Retrieves census data
  
  b. Data_Cleaning_Merging.ipynb: Cleans and Merges data

  c. EDA.ipynb: Explores data


2. Validation-Testing
This folder has scripts for conducting validation testing on 3 types of models, full linear regression, a simplified linear regression with fewer variables, and random forest, for both Democratic and Republican primary models.

  a. Final_Validation_Testing_LR_Dem.ipynb, Final_Validation_Testing_LR_Rep.ipynb: Validation testing for linear models, for Republican and Democratic primaries.

  b. Final_Validation_Testing_Mini LR_Dem.ipynb, Final_Validation_Testing_ Mini LR_Rep.ipynb: Validation testing for mini linear models, for Republican and Democratic primaries.

  c. Final_Validation_Testing_RF_Dem.ipynb, Final_Validation_Testing_ RF_Rep.ipynb: Validation testing for random forest models, for Republican and Democratic primaries.

 d. Final_Validation_Testing_RF_with_2016.ipynb: Random forest Republican validation testing with 2016 data.

 

3. Testing
This folder tests the models on the 2018 senatorial and gubernatorial primaries.

  a. Final_Full LR_New.ipynb : Testing for full linear regression
 
 Final_Mini LR_New.ipynb : Testing for mini linear regression
 
 Final_RF_New.ipynb : Testing for random forest
 
 Final_BT_New.ipynb : Testing for boosted trees
 
 Final_ET_New.ipynb : Testing for extra trees


 b. Final_Dem_BT_New No Election Data.ipynb: Test Dem BT model without past election data
  
  Final_Dem_BT_New No Election No Race Data.ipynb: Test Dem BT model without past election or racial data


 c. Final_Rep_ET_New No Election Data.ipynb: Test Rep ET model without past election data
  
  Final_Rep_ET_New No Election No Race Data.ipynb: Test Rep ET model without past election or racial data






Please see the slideshow and research paper for a more complete summary.
