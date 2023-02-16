# Penguins_DA_DV_ML
Demonstration of Data Analysis and Data Visualisation using the penguins dataset, accompanied by a Machine Learning Project predicting Penguin Sex and Species.

**Penguins_Data_Analysis,_Data_Visualisation,_and_Machine_Learning**


*Description*

The project 'penguins.ipynb' demonstrates use of various data analysis and visualisation techniques using libraries such as pandas, matplotlib, and seaborn. 
The data in the penguins_lter.csv dataset is analysed to establish relationships between features such as the penguins body measurements (Body Mass (g), 
Culmen Length (mm), Culmen Depth (mm), Flipper Length (mm)), as well as categorical variables such as Island, Species, and Sex. 
As it became clear in the inital EDA that Machine Learning techniques may be used to predict penguin species, based mainly on the Culmen measurements.
Thus, in ML_with_Penguins, this is explored and a second technique for filling in the missing Sex data is demonstrated (using KNeighbours). A model to 
predict penguin species is then trained and tested. The model is fairly successful, however it struggles with the lack of data provided on one of three 
species (about half as much as on the other two).

*Installation*

A code editor able to read .ipynb files can be used to run the programs, and the penguins_lter.csv will need to be in the same folder as the notebooks.

*Usage*

Predicting penguin Sex based mainly on Body Mass (g), and Species based on various body measurments, mainly Culmen measurements but also blood isotopes.
