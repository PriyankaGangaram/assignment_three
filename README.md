# ANA 515 Assignment 3

Author: PRIYANKA RAMESH GANGARAM  
Date: 26 June 2024

## Overview

This project focuses on cleaning and transforming weather-related storm event data retrieved from NOAA's Storm Events Database. The goal is to prepare this data for analysis and create visual representations to understand the distribution of events across states.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- R 
- RStudio (optional but recommended)

### Setup

1. **Clone the Repository**: Clone this repository to your local machine.

   ```bash
   git clone https://github.com/yourusername/ana-515-assignment-3.git
   ```

2. **Data Preparation**:
   - retrieve your `weather_data.csv` file from the link below.
     ```bash
     https://www1.ncdc.noaa.gov/pub/data/swdi/stormevents/csvfiles/StormEvents_details-ftp_v1.0_d1997_c20220425.csv.gz
     ```
   - Extract it using your preferred extraction software. I recommend using WinRAR.
   - Place your `weather_data.csv` file in the root directory of the cloned repository. Ensure it is named exactly `weather_data.csv`.

### Running the Analysis

1. **Open RStudio**:
   - Navigate to the directory where you cloned the repository.
   - Open `assignment_three.Rmd` in RStudio.

2. **Run the R Markdown File**:
   - Knit the R Markdown file (`assignment_three.Rmd`) to generate the HTML report.
   - Ignore any parsing errors related to specific rows or columns unless they affect the data cleaning process directly.

### Output

After running the R Markdown file, you will find the generated HTML report (`assignment_three.html`) in the same directory. This report includes insights from the data analysis and visualizations of storm events per state area.

## Notes

- **Data Parsing Errors**: If you encounter parsing errors, they are safe to ignore unless they disrupt the data cleaning process described in the report.

