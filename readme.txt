Programming language: Python 3

Required packages: pandas, numpy, datetime, sklearn, tensorflow, matplotlib, csv, time, copy, os, tempfile

How to reproduce using the notebook final_model.ipynb:
1. Import the packages in the first cell 
2. In the last cell, update the paths to the model in h5 format, train.csv, test.csv
3. Run

Notes on 01 Dec 2019:
Please also take a look at the cell generating the csv file of the results. The playtime_forever fit into the model was the square root of the original value. Small numbers were truncated to 0 for better reading. These were all the difference between the predicted result from the model and the final result in the csv file.