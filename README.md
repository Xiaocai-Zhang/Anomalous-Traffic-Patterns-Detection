# Anomalous-Traffic-Patterns-Detection
## Requirements
- Pandas=='0.25.0'
- Scikit-learn=='0.20.3'
- Numpy=='1.16.4'
- Numpydoc=='0.8.0'
- Jsonschema=='3.0.1'
## Data Process
**Run the test.py file in the in the data_process package**
```
python test.py
```
**Change the dataset to 'R50' or 'R18' to process other datasets, see the following code, and change the path in the configfile.txt**
```
DataSet = 'R66'
```
## ATPD_algorithm
**Copy the csv files in result fold of data_process package to the data fold of ATPD_algorithm package, configure the path in the configfile.txt**
```
configuration_file = './configfile.txt'
```
**Set the values of parameters for each dataset, and run the test.py in ATPD_algorithm package**
```
python test.py
```
