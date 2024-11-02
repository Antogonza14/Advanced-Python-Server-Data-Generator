# Advanced-Python-Server-Data-Generator
A Python project to generate synthetic server data, organize it in a DataFrame, and create visual analytics. Includes functions for hostname generation, OS/environment/country classification, and visualizations using Pandas and Matplotlib

This repository contains the practice project for the **Advanced Python Programming** . The objective of this is to develop a Python script that generates a dataset of random server names (hostnames), organizes them in a DataFrame, and creates visualizations based on the data.

## Requirements

The following libraries are used in this project:
- **Pandas**
- **Matplotlib**

Ensure your environment is set up to import these libraries.

## Objectives

1. **Data Generation**: Create a dataset of randomly generated hostnames based on specific rules.
2. **DataFrame Manipulation**: Organize and manipulate this data in a DataFrame using Pandas.
3. **Data Visualization**: Generate plots to visualize different aspects of the data.

## Features

1. **Hostname Generation**:
   - The `set_hostnames` function generates hostnames following predefined rules regarding operating system, environment, and country.
   
2. **Auxiliary Functions**:
   - `get_os`: Extracts the operating system from a hostname.
   - `get_environment`: Identifies the environment from the hostname.
   - `get_country`: Extracts the country from the hostname.
   
3. **DataFrame Creation**:
   - The `set_dataframe` function builds a DataFrame with a list of dictionaries based on the generated hostnames.
   
4. **CSV Storage**:
   - Saves the DataFrame to a CSV file named `hosts.csv`.

5. **Data Visualization**:
   - Generates several plots to analyze the distribution of operating systems, environments, and countries.


