# 1st-Year-C-Language-Data-Organization-Project
# Great Lakes Ice Concentration Data Analysis

## Overview

This project analyzes daily ice concentration data from the six Great Lakes over three consecutive years. The program was developed in **C** to process large datasets, calculate averages, identify maximum and minimum ice concentrations, and generate data files for monthly analysis and visualization.

The project demonstrates the use of C programming concepts including arrays, 2D arrays, functions, loops, conditional statements, file input/output, and data processing.

## Features

* Reads Great Lakes ice concentration data from input files.
* Separates data by year for analysis.
* Calculates average ice concentration for each Great Lake.
* Identifies the highest and lowest average ice concentrations.
* Finds the highest recorded ice concentration for each lake.
* Identifies the date and year associated with maximum ice concentrations.
* Calculates monthly average ice concentrations.
* Processes data for all six Great Lakes.
* Outputs processed data to files for further analysis and visualization.

## Great Lakes Analyzed

The program processes data for:

* Lake Superior
* Lake Michigan
* Lake Huron
* Lake Erie
* Lake Ontario
* Lake St. Clair

## Technologies Used

* **C**
* **GNUPlot** for data visualization
* File I/O
* Arrays and 2D arrays
* Functions
* Loops and conditional statements
* Data processing and analysis

## Program Structure

The program is organized into several functions:

### `avg1()`

Calculates the sum of ice concentration values within a specified range of the dataset.

### `avg2()`

Calculates the sum of values beginning at a specified index. This is used to process different portions of the dataset.

### `highest_lake()`

Finds the highest recorded ice concentration for an individual Great Lake and displays the corresponding year and day.

### `overall()`

Searches the complete dataset to identify the overall highest ice concentration recorded across the Great Lakes.

### `monthly_avg()`

Reads processed lake data, groups measurements into approximately 30-day periods, calculates monthly averages, and writes the results to an output file.

## Data Processing

The program processes three datasets representing:

* **2023–2024**
* **2022–2023**
* **2021–2022**

For each dataset, the program:

1. Reads the input data file.
2. Stores the years, days, and ice concentration values in arrays.
3. Separates measurements by year.
4. Calculates average ice concentration values.
5. Identifies maximum and minimum values.
6. Determines the highest concentration for each lake.
7. Creates processed output files.
8. Calculates monthly averages from the processed data.

## Output

The program generates processed data files that can be used for additional analysis and visualization. Monthly average data is also written to separate output files for each dataset.

These outputs can be visualized using **GNUPlot** to compare ice concentration trends across different lakes and years.

## Skills Demonstrated

This project demonstrates experience with:

* C programming
* Data structures and arrays
* 2D array processing
* File input/output
* Data analysis
* Statistical calculations
* Modular programming using functions
* Algorithm development
* Data visualization with GNUPlot
* Processing large datasets


## Purpose

The purpose of this project was to apply C programming and data-processing techniques to a real-world dataset. By analyzing ice concentration across the Great Lakes, the program demonstrates how raw data can be organized, processed, and converted into useful statistical information and visualizations.
