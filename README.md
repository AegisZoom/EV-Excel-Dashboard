# Excel Project: Electric Vehicle Adoption in Washington [WIP]

## Personal Project

### Grade: N/A

## Introduction

This repository contains one of my custom proper data projects, which I had done shortly after my Graduate Diploma of Data Science. Using my online reasearch and
self-teaching skills along with my already strong experience using Microsoft Excel, I constructed a dashboard on Electric Vehicle (EV) adoption across Washington State in
the United States. This required employing rigorous data cleaning and exploration procedures before creating the final dashboard, which consisted of a choropleth map, a 
heat map, and an interactive bar chart.

## Skills Used

- 🔠 **Microsoft Excel**: Conducted all operations, analysis, cleaning, visualisation and dashboard design using Excel features. This included the use of formulas, filters, Power Query, Power Pivot, conditional formatting, and advanced charting features.
- 📈 **Data Analysis**: Performed statistical measures and constructed visualisations to identify trends in variables. Performed univariate and multivariate analyses to find trends and relationships in data.
- 📊 **Data Visualisation/Dashboard Design**: Used visualisation design principles to design a dashboard that highlights the significance of individual data visualisations using position and size, and guided users to naturally view them in the intended order.
Selected appropriate usage of visualisations and colours that presented relevant information clearly without creating confusion.
- 🧼 **Data Cleaning**: Used Power Query to reduce data dimensionality and remove unused features. Used functions, filters, pivot tables, and scatter plots to identify outliers, missing values, impossible values, and univariate and multivariate errors to prevent low-quality data from affecting final project output.
- 📧 **Data Retrieval**: Identified suitable dataset of interest, and used Power Query operations to extract, load and transform the dataset for the project.
- 📐 **Problem-Solving**: Selected appropriate techniques for processing and analysis using a mixture of strong theoretical knowledge and a natural intuition based on real life experience.
- 🔍 **Attention to Detail**: Identified the presence and implications of trends, relationships, and outliers in the data.
- 🔬 **Research/Self-Learning**: Performed background research in electric vehicles and American geography to better understand relationships between features and help check coherence between location variables.

## Data Retrieval

I first encountered this dataset when I was looking for a suitable example to use in an assessment during my studies. Unfortunately it lacked the complexity to satisfy all elements of the rubric for the assessment, but I always had an interest to investigate it. In 2025 I made use of this dataset for my personal Excel project, and it had been updated with 2025 data. I formally reference and acknowledge the dataset below.

State of Washington (2025), *Electriv Vehicle Population Data* [data set], Data Gov website, accessed 13/03/2025. [https://catalog.data.gov/dataset/electric-vehicle-population-data](https://catalog.data.gov/dataset/electric-vehicle-population-data)

Contains information from [State of Washington Open Data](https://data.wa.gov/), which is made available here under the [Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/1-0/).

The following features were included in this dataset, along with explanations of their meaning. Features marked with * were not used for the project and were discarded, while features marked with ^ were used for preprocessing and analysis but were removed in the final version to satisfy GitHub's file size constraints.

- VIN (1-10) | (Text): Vehicle Identification Number - Used to identify different vehicle models (not unique per record) [REMOVE]
- County | (Text/Factor): The terriory that outlines a political division in a state of the US where the vehicle was registered
- City | (Text): The town where the vehicle was registered
- State | (Text/Factor): The US State where the vehicle was registered. It should only be Washington, but other states also appear.
- Postal Code | (Integer): The postal code of the town where the vehicle was registered
- Model Year | (Integer): The year the registered vehicle was constructed (1999-2025)
- Make | (Text/Factor): The company that constructed the registered vehicle
- Model | (Text): The specific model of the registered vehicle
- Electric Vehicle Type | (Text/Factor): Battery Electric Vehicle (BEV) vs Plug-In Hybrid (PHEV)
- Clean Alternative Fuel Vehicle (CAFV) Eligibility | (Text/Factor): Indicates if it benefits in renewable scheme from satisfying renewable sources and sufficient battery range.
- Electric Range | (Integer): The distance the vehicle can travel (miles) on one full battery charge
- Base MSRP | (Integer): Manufacturer's Suggested Retail Price [REMOVE]
- Legislative District | (Integer/Factor): The group of counties that share the legislative district for vehicle legislation.
- DOL Vehicle ID | (Integer): Washington State Department of Licensing ID (Unique per record, can use as ID column)
- Vehicle Location | (Geo Point): Geospatial coordinates of the registration of the vehicle
- Electric Utility | (Text): Supplier of Energy in location of registration
- 2020 Census Tract | (Integer): Likely some ID that uniquely identifies Electric Utility values [REMOVE]

##
