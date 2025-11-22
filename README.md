# Cleaned List of All Scrapped Ships

This project processes and combines annual lists of scrapped ships from the [NGO Shipbreaking Platform](https://shipbreakingplatform.org/annual-lists/) into a single, standardized dataset covering the years 2012-2024.

## What This Project Does

The NGO Shipbreaking Platform publishes annual Excel files documenting ships that were scrapped around the world. However, these files use different column names, formats, and structures across different years, adding a little difficulty when trying to process all published data.

This project:

- **Normalizes** the data from all annual reports (2012-2024) into a consistent format
- **Combines** all years into a single dataset
- **Cleans** the data by standardizing column names, handling missing values, and fixing inconsistencies
- **Preserves** all original data without manual modifications, ensuring full reproducibility

The result is a unified dataset that makes it easy to analyze published shipbreaking data.

## Output

The cleaned and combined dataset is available as:

**[`2012_2024_dismantled_ships.csv`](2012_2024_dismantled_ships.csv)**

This file contains **10,062 ships** with standardized information including:

- Ship identification (IMO number, name, type)
- Technical specifications (gross tonnage, light displacement tonnage, build year)
- Ownership information (beneficial owner, registered owner, commercial operator)
- Flag information (current flag, previous flag)
- Dismantling location (country, place)
- Arrival date at the shipbreaking yard

## Data Source

All original data comes from the [NGO Shipbreaking Platform's annual lists](https://shipbreakingplatform.org/annual-lists/). No manual changes have been made to the original Excel files. The data can be independently verified and reproduced.

For definitions of terms and acronyms used in the dataset, see the [NGO Shipbreaking Platform's Glossary](https://shipbreakingplatform.org/our-work/glossary/).
