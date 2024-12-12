# Car Sales Analysis

## Introduction
- This repository contains the analysis of a car sales dataset with thousands of records. The dataset includes car information including the selling price, kilometres driven, fuel type, transmission, and owner history. The objective of this analysis is to clean the data, provide descriptive statistics, and explore the relationships between various factors.

## What is the task?
The analysis requires four main tasks:
- **Data Cleaning**: remove missing data and outliers based on assigned rules.
- **Descriptive Statistics**: Summarise attributes like unique car names, seller types, and distribution of kilometres driven and selling prices.
- **Plotting and Analysis**: Determine correlations between fuel type, seller type, transmission, owner history, and car selling prices.
- **Outlier Detection**: Detect and remove outliers that don't follow specific rules.

## What kind of data is used?
- The Data used includes the name, year, selling_price, km_driven, fuel, seller_type, transmission, and owner of cars. These attributes are in the form of `float64`, `int64`, and `object`.

## What algorithms are applied?
- Data removal, outlier detection, basic statistical methods, grouped statistics, box plots, and correlations.

## How can you deploy/run the files?
- Download the repository, install the dependencies, set up the dataset, run the script, and view the output.

## What are the key takeaways or conclusions?  
- The more owners a car has had, the lower its price. Automatic cars sell at higher prices and have larger standard deviations compared to manual cars. Test Drive cars have the highest selling price. The newer the car, the higher the selling price.
