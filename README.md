# Excess Google Searches for Child Abuse and Intimate Partner Violence During the Covid-19 Pandemic: An Infoveillance Approach
### Corinne A. Riddell, Krista Neumann, N. Jeanie Santaularia, Kriszta Farkas, Jennifer Ahern, Susan M. Mason

This repository contains the code used to conduct an analysis estimating excess Google searches in the United States related to intimate partner violence and child abuse during the COVID-19 pandemic. 

Importantly, the data is not included in this repository because it is restricted by the data provider. Thus, to replicate these analyses, please fill out a form to access the data from [here](https://docs.google.com/forms/d/e/1FAIpQLSenHdGiGl1YF-7rVDDmmulN8R-ra9MnGLLs7gIIaAX9VHPdPg/viewform).

### File Description

The 01-Pull0Data-From-API.py file contains a generalized version of the python code used to pull the data for this project (The API key and file path will need to be supplied). The queries, geographic region, temporal scale and study period used for our analysis have been pre-populated. Please see comments in the file for additional code that may need to be updated before use.

The 02-Data-Cleaning-Analysis-Viz.rmd file details the steps used to clean and analyze the data obtained from the API (via 01-Pull0Data-From-API.py). It also includes code for checking model assumptions and creating the descriptive statistics and data visualizations (see folder called "Plots" for output from our project). File paths will need to be updated in order to run this code as it. It also assumes files have been named according to the convention described therein.

The optional 03-Excess-Search-Fig-Annotations.indd is the InDesign file used to add annotations to the main plot (See Weekly_Trends_Combined.png in the "Plots" folder). This file is useful if the time period and geo-temporal scales remain the same as in our analysis and the following policy dates are relevant: the beginning of shelter-in-place (SIP) orders, the date the first Economic Impact Payment (EIP) began to be distributed, and the end of Pandemic Unemployment Compensation (PUC). 

