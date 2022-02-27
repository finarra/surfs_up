# Surf's Up!
The puropose of this analysis, is to determine the average weather conditions, through the information provided by US weather stations, in the island of Oahu, in order to determine the feasability of a surf and ice cream shop being profitable.

In particular, temperature comparisons were made between the months of June and December, since these months set apart summer and winter. This information may help to predict if this will be a year-round or seasonal bussiness.

# Results
By writing SQLAlchemy queries on the Hawaii sqlite database, we were able to extract the temperature measurements for the months of June and December, from 2010 up to 2017.

 

 - A significant amount of measurements were obtained: 1700 measurements for June and 1510 for December.
 - The average temperature in June was 75°F and 71°F in December.
 - The temperature range for June was 64°F to 85°F and in December the temperature range was 56°F to 83°F.

The rest of the descriptive statistics for both months can be found in the tables below.

June:

![june](https://user-images.githubusercontent.com/95982833/155898609-25b4e2b1-48bc-4c14-a0f2-b2b0a113fb3d.png)


December:


![december](https://user-images.githubusercontent.com/95982833/155898621-c0b64066-7b47-4a4f-9e25-6d9b94527fde.png)

# Summary
As it can ve expected for a tropical island such as Oahu, there is not a very significant difference in mean temperatures between summer and winter. This "stable" temperature all year round may be favorable for an ice cream shop, since ice cream sales are expected to be high in warm temperatures.. 
A warm temperature may be attractive for surfers also.
However I strongly advise to perform two additional queries, in order to determine if the weather is amenable for surfing or eating ice cream, as a good temperature is not a good surrogate for good weather.

 - Precipitation should be taken into account, as rain may blunt ice cream sales, as people will prefer to stay indoors.
 - Wind speed is also an important factor, because adecaute wind speed is needed for good waves.
With these additional queries, added to the temperature, a more precise estimation of the propability of succes for both shops can be made, and may impact on the bussiness model selected (year-round vs. seasonal).
