# Obesity in adults - Data package

This data package contains the data that powers the chart ["Obesity in adults"](https://ourworldindata.org/grapher/share-of-adults-defined-as-obese?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website. It was downloaded on November 27, 2024.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The final column is the data column, which is the time series that powers the chart. If the CSV data is downloaded using the "full data" option, then the column corresponds to the time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data column is transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

## Detailed information about the data


## Prevalence of obesity among adults, BMI >= 30 (crude estimate) (%) - Sex: both sexes - Age group: 18+  years
Percentage of adults aged 18+ years with a body mass index (BMI) of 30 kg/m2 or higher.
Last updated: January 3, 2024  
Next update: January 2025  
Date range: 1975–2016  
Unit: %  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
World Health Organization - Global Health Observatory (2024) – processed by Our World in Data

#### Full citation
World Health Organization - Global Health Observatory (2024) – processed by Our World in Data. “Prevalence of obesity among adults, BMI >= 30 (crude estimate) (%) - Sex: both sexes - Age group: 18+  years” [dataset]. World Health Organization, “Global Health Observatory” [original data].
Source: World Health Organization - Global Health Observatory (2024) – processed by Our World In Data

### What you should know about this data

### How is this data described by its producer - World Health Organization - Global Health Observatory (2024)?
##### Definition
Percentage of adults aged 18+ years with a body mass index (BMI) of 30 kg/m2 or higher.

##### Method of measurement
Based on measured height and weight.

##### Method of estimation
Input data and methods are described here: NCD-RisC. Worldwide trends in body-mass index, underweight, overweight, and obesity from 1975 to 2016: a pooled analysis of 2416 population-based measurement studies with 128.9 million participants. Lancet 2017. DOI: http://dx.doi.org/10.1016/S0140-6736(17)32129-3.

### Source

#### World Health Organization – Global Health Observatory
Retrieved on: 2024-01-03  
Retrieved from: https://www.who.int/data/gho  


    