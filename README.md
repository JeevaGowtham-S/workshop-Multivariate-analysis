## workshop-Multivariate-analysis
 
## AIM:
To perform multivarient analysis on the given data set.

## ALGORITHM:
## STEP1
## 1.Clean the data

## STEP2
## 2.Remove outliers

## STEP3
## 3.Apply the skew function and Kurtosis

## STEP4
## 4.Apply Bivariate analysis on numerical and categorical

## STEP5
## 5 .Apply Multivariate analysis

## CODE: DETECTING NULL AS PD:


## INFO:


REMOVING NULL DATA:


KURTOSIS:
image

SKEW:
image

NUMERICAL & NUMERICAL:
image

NUMERICAL & CATEGORIAL:
BOX PLOT:
image

BAR PLOT:
image

DIST PLOT:
image

MULTIVARIENT ANALYSIS:
CORRELATION:
image

HEAT MAP:
import numpy as np

import seaborn as sn

import matpIotIib.pypIot as pit

data= pd.read_csv("/content/Data_set.csv")

data = np.random.randint(low = 1, high = 100, size = (10, 10)) print("The data to be plotted:\n")

print(data)

hm = sn.heatmap(data = data)

pit.show()
image

Result :
Thus we applied Bivariate/Multivariate Analysis Successfully.
