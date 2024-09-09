# Phase_1_DS_Project
This is a project on risk assessment in the Aviation Industry.

## Overview
The repository explores risks associated with aircraft Models, Make in terms of accidents occurrence. It also evaluates aviation business segments by comparing between commercial and private which poses a lower risk.

## Business Problem
A company is expanding into a new venture and would like to have all their facts together before making decisions on purchasing aircrafts and nailing down on the segment to enter into.The key problem is this is a new business for them, meaning they do not have any data whatsoever. Since data is king in making smart business decision, you are tasked with exploring risks associated with the new venture using historical data and coming up with findings that can be transformed to actionable results.

## Data Source
The data is pulled from: (https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses).
This dataset is  derived from the National Transportation Safety Board that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.

## Business Questions to Consider
- Determine trends of aircraft safety over the years
- What is the accident frequency comparison between commercial and private aircraft?
- What is the safety performance of different aircraft models ovetime?
- Which aircraft models have the highest and lowest accident rates?
- What other factors contribute to accident rates?

## Data description
pandas library for data manipulation and analysis for tabular data
import pandas as pd
numpy library for high level mathematical functions and arrays
import numpy as np
Visualization libraries
import seaborn as sns
import matplotlib.pyplot as plt
%matplotlib inline

## Loading your data
data_source = pd.read_csv("AviationData.csv", encoding='latin1')

## Cleaning data
Cleaning (df1)

## Visualization
![alt text](image.png)

![alt text](image-1.png)

![alt text](image-2.png)

![alt text](image-3.png)

![alt text](image-4.png)

![alt text](image-5.png)

![alt text](image-6.png)

## Conclusion
- Project considered the USA for analysis as it had most of the records
- From the analysis, we learn that number of engines poses a risk to the aircraft getting an accident or incident but does not necessarily correlate to injury or no injuries when the events occur.
- The purpose of flight  may be one of the factors attributing to accidents and incidents, however additional factors such as make and model may also influence depending on what aircraft is purchase for what purpose and the safety mechanism during the engineering process which we have not delved in.
