# wa-covid-19
Washington State Novel Coronavirus Outbreak (COVID-19) Data

summary-data.csv is a summary data file with the following fields:
* Date - in ISO format, YYYY-MM-DD
* Positive - cumulative number of positive/confirmed cases
* Negative - cumulative negative cases (tests that came back negative), available from 2020-03-08 onward.
* Deaths - cumulative number of deaths

One can calculate the number of tests run by adding the Positive and Negative fields together.

## Source Data
The wa-doh-source-data folder contains captures of official data released by the Washington State Department of Health.
This allows users of the dataset to trace everything back to the original, official state government data source.
