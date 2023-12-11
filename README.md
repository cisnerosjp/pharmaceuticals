# Pymaceuticals, Inc.


## The Study
At Pymaceuticals Inc. We were tasked to take identify how 249 mice were affected by different cancer treats regimens that we offer. Over 45 days they were provided these different treatment and the effects of the treaments were monitored for tumor development as well as the weight of the mice over the course of the experiment.

## The Analysis
With the data for 249 mice, and 10 drug regimens as well as different timepoints and other factors we were tasked to create different visuals that breakdown just how the treaments were proceeding for the study. With an in-depth analysis on Capomulin specifically.

- Summary Statistics DF
![image](https://github.com/cisnerosjp/pharmaceuticals/assets/97692681/8e4c178d-c632-438c-be09-5dc6cb7688ce)
- Bar plot with the timepoints for each druge regimen over the course of the study
![image](https://github.com/cisnerosjp/pharmaceuticals/assets/97692681/6dc252a0-0344-4f90-8cfe-d4c72977dc87)
- The gender distribution of the mice in the study
![image](https://github.com/cisnerosjp/pharmaceuticals/assets/97692681/f2debd9c-dbc9-4707-a794-fe6dfb854fa5)
- A box plot that show the distribution of the tumor volume for each treatement group
![image](https://github.com/cisnerosjp/pharmaceuticals/assets/97692681/699f3eba-c936-47be-8ebf-48997c020c9e)
- A line plot of tumor volume vs. timepoints for Mouse x401
![image](https://github.com/cisnerosjp/pharmaceuticals/assets/97692681/c2047a45-1203-4aee-bcc6-bca966965620)
-and more!

## Key Takeaways from this Analysis

1. Both Capomulin and Ramicane were the most tested on mice against all of the other Drug Regimens with Propiva having the least testing.
2. Capomulin and Ramicane have the lowest average tumor size amongst all of the other Drug Regimens.
3. Capomulin specifically should be used to reduce the size of tumors. Ramicane should also be used.

## Data Provided
The data that was provided for the experiment can be found in the folder "data", which can be found in the folder "pymaceuticals". From there it is arranged in two different CSV documents entitled, "Mouse_metadata.csv" and "Study_results.csv". Through the course of the analysis it was required of us to merge the data of the two documents into a single dataframe. That dataframe is held in "pymaceuticals_final.ipynb" where the code for the analysis is located as well.

## Code Sources

The code in this repository was sourced from starter code provided by the bootcamp as well as from in-class work and activities, stack overflow, different documentation libraries for matplotlib, scypy, and pandas for certain aspects of this challenge. 
