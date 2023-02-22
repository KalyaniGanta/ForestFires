# ForestFires

Part1.py

The part1.py file is attached to the submission, however upon opening the file, there is a link commented out at the top of the file to the google colab where the file was orginally created.
I would recommend clicking this link and going to the google collab where all the information is organized. Once you have opened the link, begin by running the imports block of code at the top to import all the libraries used. After doing so, you can proceed to run the following bloack one by one, waiting until they have a check mark next to them before proceeding to the next block. The gradient descent algorithm may take anywhere from 7-11 seconds so please be patient. After running this function, you will recieve the Coefficients, Y-Intercept, Mean Squared Error, and the R2 score which was adjusted for multiple variable linear regression. Beneath that block, there is also a cost function block that displays the cost function for the given parameters, please feel free to run this after. 


Part2.py

libraries used:
import numpy as np
import pandas as pd
from sklearn import linear_model
from sklearn.metrics import r2_score
from sklearn.preprocessing import StandardScaler
from sklearn.model_selection import train_test_split
from sklearn.linear_model import SGDRegressor
from sklearn.metrics import mean_squared_error
