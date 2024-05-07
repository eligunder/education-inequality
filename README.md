# Education Inequality Project

### This project is to determine if school performance is predicted by socioeconomic factors
#### The secondary research question is if there is a relationship between Geographic location and ACT score, within the United States

# Data
Data for this project is taken from EdGap.org. The data includes SAT and ACT scores from 2016, and the socioeconomic factors with the respective school districts. The secondary data set includes basic information about each school and is taken from the National Center for Education Statistics. Socioeconomic data is taken from the Census Bureau's American Community survey. SAT and ACT score data is taken from public data releases, and from each state's Department of Education.

The EdGap data can be found here: https://www.edgap.org/#5/37.892/-95.977

The secondary data set is linked here: https://drive.google.com/file/d/1HvW2w-o2XZzCm4KTvnb1Bb3BvoAa14BP/view?usp=sharing. and can be found here: https://nces.ed.gov/ccd/pubschuniv.asp.

## Additional Question Data

Data for the secondary research question was taken from the United States Census Bureau and the United States Zip code Database. It can be found here: https://www.census.gov/data/tables/time-series/demo/popest/2020s-state-total.html#v2022
and here: https://www.unitedstateszipcodes.org/zip-code-database/

# Requirements

All Data Analysis was completed using Python in Google Colab notebooks









# Data Preparation

To prepare the data, erroneous and missing values were imputed, and unnecessary columns were removed. The two data frames were merged into one data frame, then separated into training and test csv's. For the secondary research question, simalar steps were taken and the two additional csv files were merged with educ_data_merged.csv. 

## Data preparation file titled "educ_data_prep.ipynb"

## Training Data file titled "educ_train_data.csv"

## Test Data frame titled "educ_test_data.csv"

# Methods

To Investigate the research question, standard data visualization such were used in Python to measure the relationship between different variables and average ACT. Python was also used to create linear regressions, attempting to predict average ACT scores given socioeconomic factors. 

## The analysis for the primary research question can be found in the files titled 'Education_Analysis.ipynb', and for the secondary research question at 'additional_step.ipynb'. 


## A powerpoint containing a summary of the project is located in the file titled 'Effect of Socioeconomic Factors on Academic Performance.pptx'


# Conclusions

School performance can be predicted by socioeconomic factors. Furthermore, there is a strong linear relationship between ACT score and socioeconomic factors. While there is some relationship between geographic location and ACT score, there are indicators that this is due to collinearity with socioeconomic factors. No linear relationship was found between geographic location and ACT score. 

# Author(s)

This project was created by Eli Gunderman as part of his Methodology of Data Science course. LinkedIn profile can be found here: https://www.linkedin.com/in/eli-gunderman/. The second research question was formulated and data for its investigation located with help from David Stanko. 

# License

No license is required to use any materials included in this project. 



