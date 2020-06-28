# Anomalous-Traffic-Patterns-Detection
## Requirements
- Pandas=='0.25.0'
- Scikit-learn=='0.20.3'
- Numpy=='1.16.4'
- Numpydoc=='0.8.0'
- Jsonschema=='3.0.1'
## Data Process
**Run the test.py file in the data_process package**
```
python test.py
```
**Change the DataSet to 'R50' or 'R18' for processing other datasets, see the following code**
```
DataSet = 'R66'
```
**And also change the corresponding paths in the configfile.txt, see the following settings in the configfile.txt**
```
{"pathTrain": "./data/R66/train-rgb/",
"pathTest": "./data/R66/test-rgb/",
"pathOutTrain": "./result/R66/spa_temp_feature_train.csv",
"pathOutTest": "./result/R66/spa_temp_feature_test.csv"
}
```
## ATPD_algorithm
**Copy the csv files in result fold of data_process package to the data fold of ATPD_algorithm package, configure the path in the configfile.txt**
```
configuration_file = './configfile.txt'
```
```
{"pathIn": "./data/R66/",
"trainFile": "spa_temp_feature_train.csv",
"testFile": "spa_temp_feature_test.csv"
}
```
**Set the values of parameters for each dataset, and run the test.py in ATPD_algorithm package**
```
python test.py
```
