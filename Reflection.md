# Reflection

- This assignment was very open ended due to a lack of many variables in the available data. We did not have a lot of information such as vaccinations, hospitalizations etc which could have been very beneficial for the analysis but because of this we were able to gain a lot from collaboration and learning from each other.
- I was incredibly fascinated by the different approaches all of my classmates came up with, Some of which I would have never explored if not for the collaboration aspect of this project.

- I also needed to take some time off collaborating with my classmates, as it was more difficult to think in different perspectives because I was only able to build on the exisiting shared ideas instead of contributing to it with a novel/different approach. 

I had two main experiences :

1. I had a very productive conversations with one of my classmates about the limitations and possibilities from the data we had access to for this project.

Here is a summary of that discussion :
* We discussed the possible factors that could affect the progression of covid as follows :
    - Vaccinations
    - Hospitalizations
    - Public Masking
    - Holidays and other cultural events
* We are only focused on one factor for this assignment - Masking mandates. How did the mandates affect the progression of covid-19?
    - We instantly realized that rather than masking mandates affecting the covid-19 progression, the current and potential progression of covid-19 drive the issuance of maskig policies. We noticed that when mask mandates are in effect, there are higher cases which is counterintuitive but makes sense if we follow the above logic.
* We also noticed that it would be very difficult to include the mask survey data from New York times in our analysis as it provides the survey from only one point in time and we cannot effectively understand the change in this sentiment for the period for which we were conducting the analysis. Nevertheless, this data gave us an insight into the kind of mask adherence that gave rise to the existing trends. This does support the idea that masking did not have as big of an impact as vaccinations and improving recovery rate due to the low adherence, in all my visualizations we do not see a clear impact of the masking policy on the rate of change of covid-19 cases.
+ This data does not give us enough information to conclude causality or even correlation. We need access to more data to make these inferences.

2. There were many fruitful discussion on discord about various approaches that my fellow classmates followed and one I was fascinated by was - change point detection in time series data. 

- Numerous approaches to change point discussion were discussed such as Facebook Prophet and Ruptures, but essentially these libraries ann find significant or insignificant changes (depends on the penalty) in the trend of a time series. These change points could then be used in collaboration with the points in time when mask policy was changed to see if mask policy had any effect in this trend.

- I reused the implementation shared by Tharun Reddy and this is the reference he provided - [Change points in a Time Series](https://medium.com/dataman-in-ai/finding-the-change-points-in-a-time-series-95a308207012). In my implementation, I noticed a lag in the change point detected by the algorithm and the mask policy change. Generally, the predicted change point succeded the mask policy change by about 3 months, this could be due to the misguided confidence on masks (because most people are not adhereing to the policy). 

