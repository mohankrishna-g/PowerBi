# CO₂ emissions by fuel or industry type - Data package

This data package contains the data that powers the chart ["CO₂ emissions by fuel or industry type"](https://ourworldindata.org/grapher/co2-by-source?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The remaining columns are the data columns, each of which is a time series. If the CSV data is downloaded using the "full data" option, then each column corresponds to one time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data columns are transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

### How we process data at Our World In Data
All data and visualizations on Our World in Data rely on data sourced from one or several original data providers. Preparing this original data involves several processing steps. Depending on the data, this can include standardizing country names and world region definitions, converting units, calculating derived indicators such as per capita measures, as well as adding or adapting metadata such as the name or the description given to an indicator.
[Read about our data pipeline](https://docs.owid.io/projects/etl/)

## Detailed information about each time series


## Other industry
Annual emissions of carbon dioxide (CO₂) from other industry sources, measured in tonnes.
Last updated: November 21, 2024  
Next update: November 2025  
Date range: 1750–2023  
Unit: tonnes  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Global Carbon Budget (2024) – with major processing by Our World in Data

#### Full citation
Global Carbon Budget (2024) – with major processing by Our World in Data. “Other industry” [dataset]. Global Carbon Project, “Global Carbon Budget” [original data].
Source: Global Carbon Budget (2024) – with major processing by Our World In Data

### What you should know about this data
* This data is based on territorial emissions, meaning the emissions produced within a country's borders, but not those from imported goods. For example, emissions from imported steel are counted in the country where the steel is produced. To learn more and look at emissions adjusted for trade, read our article: [How do CO₂ emissions compare when we adjust for trade?](https://ourworldindata.org/consumption-based-co2)
* Emissions from international aviation and shipping are not included in the data for any individual country or region. They are only counted in the global total.

### Source

#### Global Carbon Project – Global Carbon Budget
Retrieved on: 2024-11-21  
Retrieved from: https://globalcarbonbudget.org/  

#### Notes on our processing step for this indicator
- Global emissions are converted from tonnes of carbon to tonnes of carbon dioxide (CO₂) using a factor of 3.664. This is the conversion factor [recommended by the Global Carbon Project](https://globalcarbonbudgetdata.org/downloads/jGJH0-data/Global+Carbon+Budget+v2024+Dataset+Descriptions.pdf). It reflects that one tonne of carbon, when fully oxidized, forms 3.664 tonnes of CO₂, based on the relative molecular weights of carbon and oxygen in CO₂.
- Emissions from the 1991 Kuwaiti oil fires are included in Kuwait's emissions for that year.



## Flaring
Annual emissions of carbon dioxide (CO₂) from flaring, measured in tonnes.
Last updated: November 21, 2024  
Next update: November 2025  
Date range: 1750–2023  
Unit: tonnes  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Global Carbon Budget (2024) – with major processing by Our World in Data

#### Full citation
Global Carbon Budget (2024) – with major processing by Our World in Data. “Flaring” [dataset]. Global Carbon Project, “Global Carbon Budget” [original data].
Source: Global Carbon Budget (2024) – with major processing by Our World In Data

### What you should know about this data
* This data is based on territorial emissions, meaning the emissions produced within a country's borders, but not those from imported goods. For example, emissions from imported steel are counted in the country where the steel is produced. To learn more and look at emissions adjusted for trade, read our article: [How do CO₂ emissions compare when we adjust for trade?](https://ourworldindata.org/consumption-based-co2)
* Emissions from international aviation and shipping are not included in the data for any individual country or region. They are only counted in the global total.

### Source

#### Global Carbon Project – Global Carbon Budget
Retrieved on: 2024-11-21  
Retrieved from: https://globalcarbonbudget.org/  

#### Notes on our processing step for this indicator
- Global emissions are converted from tonnes of carbon to tonnes of carbon dioxide (CO₂) using a factor of 3.664. This is the conversion factor [recommended by the Global Carbon Project](https://globalcarbonbudgetdata.org/downloads/jGJH0-data/Global+Carbon+Budget+v2024+Dataset+Descriptions.pdf). It reflects that one tonne of carbon, when fully oxidized, forms 3.664 tonnes of CO₂, based on the relative molecular weights of carbon and oxygen in CO₂.
- Emissions from the 1991 Kuwaiti oil fires are included in Kuwait's emissions for that year.



## Cement
Annual emissions of carbon dioxide (CO₂) from cement, measured in tonnes.
Last updated: November 21, 2024  
Next update: November 2025  
Date range: 1750–2023  
Unit: tonnes  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Global Carbon Budget (2024) – with major processing by Our World in Data

#### Full citation
Global Carbon Budget (2024) – with major processing by Our World in Data. “Cement” [dataset]. Global Carbon Project, “Global Carbon Budget” [original data].
Source: Global Carbon Budget (2024) – with major processing by Our World In Data

### What you should know about this data
* This data is based on territorial emissions, meaning the emissions produced within a country's borders, but not those from imported goods. For example, emissions from imported steel are counted in the country where the steel is produced. To learn more and look at emissions adjusted for trade, read our article: [How do CO₂ emissions compare when we adjust for trade?](https://ourworldindata.org/consumption-based-co2)
* Emissions from international aviation and shipping are not included in the data for any individual country or region. They are only counted in the global total.

### Source

#### Global Carbon Project – Global Carbon Budget
Retrieved on: 2024-11-21  
Retrieved from: https://globalcarbonbudget.org/  

#### Notes on our processing step for this indicator
- Global emissions are converted from tonnes of carbon to tonnes of carbon dioxide (CO₂) using a factor of 3.664. This is the conversion factor [recommended by the Global Carbon Project](https://globalcarbonbudgetdata.org/downloads/jGJH0-data/Global+Carbon+Budget+v2024+Dataset+Descriptions.pdf). It reflects that one tonne of carbon, when fully oxidized, forms 3.664 tonnes of CO₂, based on the relative molecular weights of carbon and oxygen in CO₂.
- Emissions from the 1991 Kuwaiti oil fires are included in Kuwait's emissions for that year.



## Gas
Annual emissions of carbon dioxide (CO₂) from gas, measured in tonnes.
Last updated: November 21, 2024  
Next update: November 2025  
Date range: 1750–2023  
Unit: tonnes  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Global Carbon Budget (2024) – with major processing by Our World in Data

#### Full citation
Global Carbon Budget (2024) – with major processing by Our World in Data. “Gas” [dataset]. Global Carbon Project, “Global Carbon Budget” [original data].
Source: Global Carbon Budget (2024) – with major processing by Our World In Data

### What you should know about this data
* This data is based on territorial emissions, meaning the emissions produced within a country's borders, but not those from imported goods. For example, emissions from imported steel are counted in the country where the steel is produced. To learn more and look at emissions adjusted for trade, read our article: [How do CO₂ emissions compare when we adjust for trade?](https://ourworldindata.org/consumption-based-co2)
* Emissions from international aviation and shipping are not included in the data for any individual country or region. They are only counted in the global total.

### Source

#### Global Carbon Project – Global Carbon Budget
Retrieved on: 2024-11-21  
Retrieved from: https://globalcarbonbudget.org/  

#### Notes on our processing step for this indicator
- Global emissions are converted from tonnes of carbon to tonnes of carbon dioxide (CO₂) using a factor of 3.664. This is the conversion factor [recommended by the Global Carbon Project](https://globalcarbonbudgetdata.org/downloads/jGJH0-data/Global+Carbon+Budget+v2024+Dataset+Descriptions.pdf). It reflects that one tonne of carbon, when fully oxidized, forms 3.664 tonnes of CO₂, based on the relative molecular weights of carbon and oxygen in CO₂.
- Emissions from the 1991 Kuwaiti oil fires are included in Kuwait's emissions for that year.



## Oil
Annual emissions of carbon dioxide (CO₂) from oil, measured in tonnes.
Last updated: November 21, 2024  
Next update: November 2025  
Date range: 1750–2023  
Unit: tonnes  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Global Carbon Budget (2024) – with major processing by Our World in Data

#### Full citation
Global Carbon Budget (2024) – with major processing by Our World in Data. “Oil” [dataset]. Global Carbon Project, “Global Carbon Budget” [original data].
Source: Global Carbon Budget (2024) – with major processing by Our World In Data

### What you should know about this data
* This data is based on territorial emissions, meaning the emissions produced within a country's borders, but not those from imported goods. For example, emissions from imported steel are counted in the country where the steel is produced. To learn more and look at emissions adjusted for trade, read our article: [How do CO₂ emissions compare when we adjust for trade?](https://ourworldindata.org/consumption-based-co2)
* Emissions from international aviation and shipping are not included in the data for any individual country or region. They are only counted in the global total.

### Source

#### Global Carbon Project – Global Carbon Budget
Retrieved on: 2024-11-21  
Retrieved from: https://globalcarbonbudget.org/  

#### Notes on our processing step for this indicator
- Global emissions are converted from tonnes of carbon to tonnes of carbon dioxide (CO₂) using a factor of 3.664. This is the conversion factor [recommended by the Global Carbon Project](https://globalcarbonbudgetdata.org/downloads/jGJH0-data/Global+Carbon+Budget+v2024+Dataset+Descriptions.pdf). It reflects that one tonne of carbon, when fully oxidized, forms 3.664 tonnes of CO₂, based on the relative molecular weights of carbon and oxygen in CO₂.
- Emissions from the 1991 Kuwaiti oil fires are included in Kuwait's emissions for that year.



## Coal
Annual emissions of carbon dioxide (CO₂) from coal, measured in tonnes.
Last updated: November 21, 2024  
Next update: November 2025  
Date range: 1750–2023  
Unit: tonnes  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Global Carbon Budget (2024) – with major processing by Our World in Data

#### Full citation
Global Carbon Budget (2024) – with major processing by Our World in Data. “Coal” [dataset]. Global Carbon Project, “Global Carbon Budget” [original data].
Source: Global Carbon Budget (2024) – with major processing by Our World In Data

### What you should know about this data
* This data is based on territorial emissions, meaning the emissions produced within a country's borders, but not those from imported goods. For example, emissions from imported steel are counted in the country where the steel is produced. To learn more and look at emissions adjusted for trade, read our article: [How do CO₂ emissions compare when we adjust for trade?](https://ourworldindata.org/consumption-based-co2)
* Emissions from international aviation and shipping are not included in the data for any individual country or region. They are only counted in the global total.

### Source

#### Global Carbon Project – Global Carbon Budget
Retrieved on: 2024-11-21  
Retrieved from: https://globalcarbonbudget.org/  

#### Notes on our processing step for this indicator
- Global emissions are converted from tonnes of carbon to tonnes of carbon dioxide (CO₂) using a factor of 3.664. This is the conversion factor [recommended by the Global Carbon Project](https://globalcarbonbudgetdata.org/downloads/jGJH0-data/Global+Carbon+Budget+v2024+Dataset+Descriptions.pdf). It reflects that one tonne of carbon, when fully oxidized, forms 3.664 tonnes of CO₂, based on the relative molecular weights of carbon and oxygen in CO₂.
- Emissions from the 1991 Kuwaiti oil fires are included in Kuwait's emissions for that year.



    