Introductory investigation into UK used car sales.
  
  Contents:
  1. Project Description
  2. How to Install and Run the Project

1. Project Description
  In this project we investigate and draw inferences on the UK used car market.
  The work focusses on public-domain data, obtained from UK-based Kaggle user adityadesai13:
  # https://www.kaggle.com/adityadesai13/used-car-dataset-ford-and-mercedes

  An analysis of this data with respect to 3 business-oriented questions is given on Medium:
  # https://medium.com/@andrew.croudace/uk-used-car-analysis-2020-1842eb2380e4

  The data is broken down by make across 9 .csv files, and 4 model-focused sets: 2 cleaned and 2 uncleaned.
  We disregard the model-focused sets as the models are included in other car make files.

  To summarise, this code:
  1. Imports locally saved .csv files
  2. Cleans and assembles the data into a single DataFrame
  3. Creates dummy columns for categorical features
  4. Splits the data set into training and testing sets
  5. Performs linear-regression modelling to determine whether car price can be predicted
  6. Returns an r-squared score

  I've used standard python data analysis packages, including pandas, numpy, matplotlib, and seaborn.
  In addition, glob is imported to load .csv data files.

  Presently, the code only tests the linear-regression model on a test sample of the supplied data sets, so there
  is no user input or interaction, aside from choosing features on which the linear-regression model will be trained.
  A future development may be to allow users to input values for the features manually, and utilise the
  linear-regression model to predict the car's market price.

2. How to Install and Run the Project
  The Jupyter notebook .ipynb file included was developed using Atom, and is called used_car_code.ipynb. 
  Used-car data sets will need to be downloaded and stored in the local folder to be loaded, or the used_car_code.ipynb code can be amended to
  the files' location.

