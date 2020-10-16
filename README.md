Problem Statement

To build a classification methodology to predict the quality of wafer sensors based on the given training data. 

Data Description

The client will send data in multiple sets of files in batches at a given location. Data will contain Wafer names and 590 columns of different sensor values for each wafer. The last column will have the "Good/Bad" value for each wafer.
"Good/Bad" column will have two unique values +1 and -1.  
"+1" represents Bad wafer.
"-1" represents Good Wafer. 
Apart from training files, we also require a "schema" file from the client, which contains all the relevant information about the training files such as:
Name of the files, Length of Date value in FileName, Length of Time value in FileName, Number of Columns, Name of the Columns, and their datatype.

How to use the code

To use this Python code, please follow the following steps:

1. Download the zip file to local computer
2. Create an environment with python 3.6.10 preferably in Pycharm
3. Run pip install -r requirements.txt to install all the dependencies
4. Open run.py in Pycharm and run the file
