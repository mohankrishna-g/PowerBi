# Oil reserves - Data package

This data package contains the data that powers the chart ["Oil reserves"](https://ourworldindata.org/grapher/oil-proved-reserves?v=1&csvType=full&useColumnShortNames=false&utm_source=chatgpt.com) on the Our World in Data website. It was downloaded on November 01, 2025.

### Active Filters

A filtered subset of the full data was downloaded. The following filters were applied:

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


## Oil proved reserves
Last updated: June 27, 2025  
Next update: June 2026  
Date range: 1980–2020  
Unit: tonnes  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Energy Institute - Statistical Review of World Energy (2025) – with major processing by Our World in Data

#### Full citation
Energy Institute - Statistical Review of World Energy (2025) – with major processing by Our World in Data. “Oil proved reserves” [dataset]. Energy Institute, “Statistical Review of World Energy” [original data].
Source: Energy Institute - Statistical Review of World Energy (2025) – with major processing by Our World In Data

### What you should know about this data
* Estimates have been compiled using a combination of primary official sources, third-party data from the OPEC Secretariat, World Oil, Oil & Gas Journal and Chinese reserves based on official data and information in the public domain. Canadian oil sands 'under active development' are an official estimate. Venezuelan Orinoco Belt reserves are based on the OPEC Secretariat and government announcements. Reserves and R/P ratio for Canada includes Canadian oil sands. Reserves and R/P ratio for Venezuela includes the Orinoco Belt. Saudi Arabia's oil reserves include NGLs from 2017. Total proved reserves of oil are generally taken to be those quantities that geological and engineering information indicates with reasonable certainty can be recovered in the future from known reservoirs under existing economic and operating conditions. The data series for total proved oil reserves does not necessarily meet the definitions, guidelines and practices used for determining proved reserves at company level, for instance as published by the US Securities and Exchange Commission, nor does it necessarily represent BP's view of proved reserves by country. Reserves-to-production (R/P) ratio: If the reserves remaining at the end of any year are divided by the production in that year, the result is the length of time that those remaining reserves would last if production were to continue at that rate. Reserves include gas condensate and natural gas liquids (NGLs) as well as crude oil.

### Source

#### Energy Institute – Statistical Review of World Energy
Retrieved on: 2025-06-27  
Retrieved from: https://www.energyinst.org/statistical-review/  


    