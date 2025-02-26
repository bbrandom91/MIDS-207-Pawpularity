# MIDS-207-Pawpularity
This is a fork of my final project for MIDS Data Science 207. 

The goal of this project was to train a ML model to predict the "pawpularity" score for pictures of pets. 
The data comes from Kaggle and can be found [here](https://www.kaggle.com/competitions/petfinder-pawpularity-score).

Basically: the "pawpularity" score is a metric defined by the people of PetFinder.my, a Malaysian animal welfare program. A high score indicates a pet is likely to be adopted based on its photo, so a good classifier can be used to optimize photo choices for adoption. Pawpularity is a number from 1-100. 

We found the task quite challenging; a dummy model that spat out just the mean pawpularity score yielded a RMSE of abour 20.4. After tons of experimentation, with a transfer learning approach we managed to get RMSE down a point or two, but it seeme there may just not be much signal in the data. 

TODO: Create a pipeline to train a model and extract the inference artifact. Then, serve the inference artifact via an API. 
