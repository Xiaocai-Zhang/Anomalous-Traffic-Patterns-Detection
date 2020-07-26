# Anomalous-Traffic-Patterns-Detection
## Requirements
- Pandas=='0.25.0'
- Scikit-learn=='0.20.3'
- Numpy=='1.16.4'
## Data Process
**Run the test.py file in the data_process package**
```
python test.py
```
**Change the DataSet to 'R50' or 'R18' for processing other datasets, see the following line in the test.py**
```
DataSet = 'R66'
```
## OFF-ATPD Algorithm
**Copy the csv files in the result fold of data_process package to the data fold of OFF_ATPD_algorithm package. Set the parameters for each dataset, like the following parameters for R66 dataset**
```
#parameters for R66
DataSet = 'R66'
Nc = 450
r = 50
rho = 2.0
```
**Run the test.py in OFF-ATPD_algorithm package**
```
python test.py
```
## ON-ATPD Algorithm
**Copy the csv files in the result fold of data_process package to the data fold of ON_ATPD_algorithm package. Set the parameters for each dataset, like the following parameters for R66 dataset**
```
DataSet = 'R66'
seqtime = 18
Nc = 450
r = 50
rho = 2.0
epsilon = 0.01
n = 1
```
**Run the test.py in ON-ATPD_algorithm package**
```
python test.py
```
