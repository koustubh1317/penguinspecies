# Predicting Penguins species
# ML project:- supervised learning 
# Made by:-Koustubh sinha

Penguin dataset where we want to predict the species of penguins based on certain feature using appropriate model.

About penguin dataset

It is a great intro dataset for data exploration & visualization

The dataset consists of 7 columns.

-species: penguin species (Chinstrap, Adélie, or Gentoo)
-culmen_length_mm: culmen length (mm)
-culmen_depth_mm: culmen depth (mm)
-flipper_length_mm: flipper length (mm)
-body_mass_g: body mass (g)
-island: island name (Dream, Torgersen, or Biscoe) in the Palmer Archipelago (Antarctica)
-sex: penguin sex

What are culmen length & depth?
![p](https://user-images.githubusercontent.com/54525819/139197232-91df7152-f6a9-4149-89d6-d04ad2cf021a.jpg)

What are flippers?
![Pen](https://user-images.githubusercontent.com/54525819/139198017-769e8f61-2e58-48a9-947d-fd22947a6548.png)

The description of dataset and detailed exploratory analysis of it is done in predicting_penguins.ipynb file PLEASE go through it

# Getting started
Workflow:-
## * Step 1 :- Data Cleaning and visualization
  Done through different plots.
## * Step 2:- Exploratory data analysis and data preprocessing
  Understand the data and make the dataset ready to be fitted in model(label encoder,normalization).
  
![Screenshot 2022-12-18 192449](https://user-images.githubusercontent.com/54525819/208302615-32ada4f6-d5e7-47e4-a58f-6c0abaa986a2.png)
![Screenshot 2022-12-18 191547](https://user-images.githubusercontent.com/54525819/208302622-1d67d863-3766-40b5-b6a1-dd3616e4ade9.png)

## * Step 3:- Model Training and selection
![Screenshot 2022-12-18 191609](https://user-images.githubusercontent.com/54525819/208302680-b984e469-09b4-482a-b44a-7263d7187812.png)
  As seen from the step 2, Knc has the best parameters to satisfy our dataset.

## About KNeighborsClassifier
* KNeighborsClassifier is one of the simplest Machine Learning algorithms based on Supervised Learning technique.
* KNC algorithm assumes the similarity between the new case/data and available cases and put the new case into the category that is most similar to the available categories.
* KNC algorithm stores all the available data and classifies a new data point based on the similarity. This means when new data appears then it can be easily classified into a well suite category by using KNC algorithm.

## * Step 4:- Testing new data points
![Screenshot 2022-12-18 193326](https://user-images.githubusercontent.com/54525819/208303042-2c5c1155-3a09-461e-a130-96d9d02c715c.png)
