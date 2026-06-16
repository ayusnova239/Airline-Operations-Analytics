# Airline Operations Analytics

## Dashboard Preview

![Dashboard](dashboard/Dashboard_screenshot.png)

## Overview

This project is an end-to-end data analytics solution built using Python, Pandas, and Power BI to analyze airline operations and performance.

The project involved cleaning and transforming airline operational data using Pandas, performing exploratory analysis, engineering additional features, and developing an interactive Power BI dashboard for performance monitoring.

## Objectives

* Analyze airline operational performance
* Monitor passenger traffic trends
* Evaluate flight delay patterns
* Compare airline performance
* Identify high-demand routes
* Track revenue and operational costs
* Create interactive business intelligence dashboards

## Dataset

The dataset contains airline operational information including:

* Airline Name
* Origin and Destination Airports
* Passenger Volume
* Ticket Prices
* Flight Delays
* Fuel Costs
* Aircraft Types
* Weather Conditions
* Flight Duration

## Data Processing

### Python (Pandas)

* Data cleaning and preprocessing
* Missing value analysis
* Datetime conversion
* Outlier detection using IQR
* Feature engineering

### Engineered Features

* Route
* Month
* Day
* Delayed_Flag
* Fuel_Cost_Per_KM
* Price_Per_Hour

## Exploratory Data Analysis

The analysis focuses on:

* Airline-wise passenger trends
* Flight delay analysis
* Route performance analysis
* Ticket price distribution
* Operational cost analysis
* Delay percentage evaluation

## Power BI Dashboard

The interactive dashboard includes:

### KPI Cards

* Total Flights
* Total Passengers
* Average Delay (Min)
* Total Revenue
* Total Fuel Cost
* Delayed Flight Percentage

### Visualizations

* Passenger Volume by Airline
* Average Delay by Airline
* Delayed Flight Percentage
* Monthly Passenger Trends
* Route Performance Analysis
* Ticket Price Analysis

## Key Insights

* GoAir and Air India recorded the highest passenger volumes, each serving approximately 2.3 million passengers during the analyzed period.

* Average flight delays were relatively consistent across airlines, ranging between 22 and 23 minutes, indicating industry-wide operational challenges rather than issues isolated to a single carrier.

* IndiGo experienced the highest delayed flight percentage (59%), while Air India and SpiceJet reported comparatively lower delay rates (57%).

* Vistara had the highest average ticket price (₹4.4K), whereas GoAir offered the lowest average ticket price (₹2.7K), highlighting distinct pricing strategies among airlines.


## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Power BI
* DAX
* Power Query
* Git & GitHub

## Project Structure

```text
airline-operations-analytics/
│
├── data/
├── notebooks/
└── dashboard/
```
