# wa-covid-19
Washington State Novel Coronavirus Outbreak (COVID-19) Data

The goal of repository is to capture the official data from the Washington State Department of Health
and publish it in a more convenient (parseable) format, with documentation that traces all values back to the original source.

summary-data.csv is a summary data file with the following fields:
* Date - in ISO format, YYYY-MM-DD
* Positive - cumulative number of positive/confirmed cases
* Negative - cumulative negative cases (tests that came back negative), available from 2020-03-08 onward.
* Deaths - cumulative number of deaths

One can calculate the number of tests run by adding the Positive and Negative fields together.

## Source Data
The wa-doh-source-data folder contains captures of official data released by the Washington State Department of Health.
This allows users of the dataset to trace everything back to the original, official state government data source.

The original data source at the official Washington State Department of Health is located at
https://www.doh.wa.gov/Emergencies/Coronavirus.

*This repository is not published by nor affiliated with the Washington State Department of Health.*
