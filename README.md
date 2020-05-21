# Modeling the Mean Sea Level in Guam
**ORCID:** <div itemscope itemtype="https://schema.org/Person"><a itemprop="sameAs" content="https://orcid.org/0000-0003-4470-4037" href="https://orcid.org/0000-0003-4470-4037" target="orcid.widget" rel="noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon">https://orcid.org/0000-0003-4470-4037</a></div>

**OpenID:https://esgf-node.llnl.gov/esgf-idp/openid/amanakta **


# Purpose of the Project 

This project was created to act as a final project submission for the EAPS507 course Introduction to Analysis and Computing with Geoscience Data offered by Purdue University for the Fall 2019-2020 semester. This project focuses on understanding the performance of different models in forecasting mean sea level changes. 

# Introduction 

Climate change is a problem that is affecting every part of our world today. While it's effects include soaring temperatures and extreme weather, small islands, such as Guam are most concerned with the implications sea level change has on it's coastal areas. Guam is surrounded by coral reef ecosystems that protect the island from flooding and typhoons *(USEPA, August 2016)*, and the sea level rise along with the increased acidity of the water is destroying these ecosystems and exposing the island to the threats of climate change. 

While the sea level is expected to rise by 3 feet over the next century *(USEPA, August 2016)*, it is important to be prepared for extreme changes. It is therefore important to be prepared and anticipate changes in the monthly mean sea level so sufficient preparation can be done to protect the island's coastal regions from damage from flooding. Creating an accurate model of monthly mean sea level will provide a preview of the changes that could be expected over the next few years.

This project will evaluate the performance of several models so an informed decision can be made on which type of model should be used to further study the mean sea level data.

# The Data

The data that will be examined for this evaluation is the mean sea level data for Guam recorded by **National Oceanic and Atmospheric Administration (NOAA)** for since 1948. The details for the data are as follows:

*Station number: 1630000

*Location: Apra Harbour, Guam 

*Date Station was Established: March 11, 1948

*Latitude of Station:     13° 26.6' N

*Longitude of Station: 144° 39.4' E

*Data Source: [Click Here for Data Source](https://tidesandcurrents.noaa.gov/sltrends/sltrends_station.shtml?id=1630000)

All information from this site is accurate as of December 5th 2019. 

# Metadata 

This evaluation was created to understand what is the best type of model that should be used to accurately predict monthly mean sea level changes. This is so that the coastal land use changes can accurately be predicted to prepare small islands, such as Guam, for the impacts of sea level rise cause by climate change. For the purpose of this study, data from the Apra Harbor in Guam was used to create this model and therefore the result of this study is limited to this location. 

The data used for creating this model was collected from the NOAA website for station number 1630000, Apra Harbor Guam, and it is accurate as of December 5th 2019 which is when this evaluation was performed. The program used for the generation of this model was R Studio Version 1.2.1335 which is an integrated development environment for the R programming language which is freely available for download with an open source license from this [link](https://rstudio.com/products/rstudio/download/). This software has been used to process the data collected from the NOAA using several statistical techniques to create linear, loess and the kNN method of Statistical Machine Learning. 

# Description of Files

'GuamMSLcode.Rmd': Source Code for the Project.

'1630000_meantrend.csv': Source file used for developing the code.
