# TTC delay forecasting project

This repository focuses on forecasting delays in the Toronto Transit Commission (TTC) network. By analyzing transit data, we aim to predict the occurrence, location, and duration of delays across streetcars, subways, and buses. Our model provides insights to optimize transit operations and improve service reliability, supporting a more efficient and sustainable transportation system in Toronto.

# Problem statement
The TTC serves as a lifeline for Toronto's urban mobility, offering millions of daily trips across streetcars, subways, and buses. However, recurring delays across various routes hinder the TTC's ability to deliver consistent service. This issue undermines public confidence and complicates efforts to promote sustainable transportation, crucial for reducing the city's carbon footprint by encouraging fewer car journeys. Addressing these challenges is vital for the TTC to fulfill its mandate of providing an incentive to alternative transit solutions. 

# Objective
Develop a solution to forecast the occurrence, location, and during of delays within the TTC network. By accurately predicting when and where delays are most likely to occur, as well as estimating their length, the model will provide valuable insights for optimizing transit operations and enhancing the reliability of service across the city.

## Reproducibility

### Dependencies
To reproduce the analysis, ensure you have the following python packages imported:

- `polars`
- 'pandas'
- 'matplotlib.pyplot'
- 'seaborn'
- 'numpy'
- 'xlsxwriter'

You can install these packages using the following command:

```Python
import polars as pl
import xlsxwriter
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
import pandas as pd
```

### Code Execution
The analysis is performed in python, and the code is available in the `scripts` directory. To execute the code, follow these steps:

1. Load the required libraries.
2. Read the cleaned data from the CSV/xlsx file.
3. Perform data filtering and manipulation for specific analyses.
4. Generate tables and graphs to visualize trends.


## File Structure

The repo is structured as:

-   `input/data` contains the data sources used in analysis including the raw data.
-   `outputs/paper` contains the files used to generate the paper, including EDA report, reference bibliography file.
-   `scripts` contains the python scripts used to clean, model and test data.
  


## Code and Data Availability

The entire codebase and datasets used for this analysis are available in this repository. You can reproduce the analysis by following the instructions provided in the README.

For any questions or clarifications, feel free to reach out to the repository owner.

*Code and data supporting this analysis is available at: https://github.com/Chay-HyunminPark/TTC-Delay.git

## Statement on LLM Usage
Certain sections of the code were generated with the assistance of ChatGPT4o. The complete chat history is available in `inputs/llms/usage.txt`. 
