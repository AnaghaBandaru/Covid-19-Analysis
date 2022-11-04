# Covid-19-Analysis 

## Goal

The goal of this assignment is to collaborate and analyze the effect of mask policies on the progression of Covid-19 from February 2020 to October 2021. I analyzed the data for Hennepin County, Minnesota.

## Data Source

- The confirmed cases of covid by county is available in this [Kaggle repository](https://www.kaggle.com/datasets/antgoldbloom/covid19-data-from-john-hopkins-university). This data is updated daily and is from John Hopkins University COVID-19 data. 
- The masking mandates by county data is provided by the [CDC](https://data.cdc.gov/Policy-Surveillance/U-S-State-and-Territorial-Public-Mask-Mandates-Fro/62d6-pm5i)
- The mask compliance survey data is from [New York Times](https://github.com/nytimes/covid-19-data/tree/master/mask-use)

## Project Structure

```bash
covid-19-analysis
├── LICENSE
├── README.md
├── Reflection.md
├── Visualization_Explanation.md
├── covid_19_analysis.ipynb
├── data
│   ├── RAW_us_confirmed_cases.csv
│   ├── U.S._State_and_Territorial_Public_Mask_Mandates_From_April_10__2020_through_August_15__2021_by_County_by_Day.csv
│   └── mask-use-by-county.csv
└── outputs
    ├── maskPolicy.png
    ├── maskSurvey.png
    ├── progressionOfCovid.png
    └── twoWeekRateOfChange.png
2 directories, 12 files
 ```

## File Descriptions

**data** : 

- *RAW_us_confirmed_cases.csv* : Daily confirmed cases by county.
- *mask-use-by-county.csv* : Survey for mask adherence by county.
- *U.S._State_and_Territorial_Public_Mask_Mandates_From_April_10__2020_through_August_15__2021_by_County_by_Day.csv* : Mask policy in affect by county. (This file was too big to save in the repository)
- *finalDataset.csv* : This is the final dataset I used for the analysis, it has the confirmed cases and mask policy data for Hennepin County, Minnesota.


**output** :

- *maskPolicy.png* : Change in mask policy from Feb 2020 to October 2022
- *progressionOfCovid.png* : Change of covid-19 progression from Feb2020 to October 2022
- *maskSurvey.png* : Proportion of population in Hennepin County, Minnesota adhereing to different levels of mask wearing.
- *twoWeekRateOfChange.png* : The change in the rate of daily cases of covid-19

**Analysis Files**:

- *covid_19_analysis.ipynb* : Contains all the data acquisition, cleaning, visualizations and analysis for affect of masking policies on covid-19 for Hennepin County, Minnesota.
- *Visualization_Explanation.md* : Contains the required explanation for compelling visualizations in the analysis.
- *Reflection.md* : Contains a description of my experience collaborating for this assignment.
