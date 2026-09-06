# How Far Does Treatment Go?

### A Global Analysis of ART Treatment Coverage and HIV Mortality Patterns

## Overview

This project examines the relationship between antiretroviral therapy (ART) coverage and HIV/AIDS mortality across countries. Using country-level data, we investigated whether higher ART coverage is associated with lower HIV/AIDS death counts while accounting for differences in the number of people living with HIV.

## Research Question

**Is higher antiretroviral therapy (ART) coverage associated with lower HIV/AIDS death counts across countries?**

## Methods

* Combined country-level data on HIV/AIDS deaths, HIV population, and ART coverage
* Cleaned and standardized data from multiple sources
* Conducted correlation analysis
* Built simple and multiple linear regression models
* Applied log transformations to account for skewness in the data
* Evaluated model assumptions using residual diagnostics
* Created visualizations to compare model results and relationships between variables

## Key Findings

The log-transformed regression model showed a significant negative association between ART coverage and HIV/AIDS deaths after controlling for HIV population size. Each 1 percentage point increase in ART coverage was associated with approximately a **1.4% decrease in expected HIV/AIDS deaths**. The log-transformed model also explained approximately 90% of the variation in log HIV/AIDS deaths.

## Tools

* R
* Statistical regression
* Data visualization
* Exploratory data analysis

## Data Sources

The analysis used publicly available country-level HIV/AIDS data derived from sources including the **World Health Organization (WHO)**, **UNESCO**, and **Kaggle**. The original dataset was accessed through the [HIV AIDS – Data Analysis and Visualization](https://github.com/srivi15/HIV-AIDS---Data-Analysis) GitHub repository.

## Limitations

This analysis uses observational, country-level data, so the results cannot establish a causal relationship between ART coverage and HIV mortality. Missing data and other factors, including healthcare infrastructure and economic conditions, may also influence the observed relationship.

