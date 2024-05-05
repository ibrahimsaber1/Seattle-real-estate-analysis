# Seattle Real Estate Analysis

This repository contains SQL scripts for cleaning and preprocessing the Seattle real estate dataset. The dataset includes housing-related information such as sale dates, property addresses, owner addresses, and more.

## Purpose

The purpose of this project is to analyze Seattle's real estate market by cleaning and preprocessing the dataset to ensure data consistency, accuracy, and completeness.

## Steps Taken

1. **Inspecting Data**: We started by examining the Seattle real estate dataset to understand its structure and contents.

2. **Standardizing Data Format (SaleDate)**: The SaleDate column was converted to a standard date format for consistency.

3. **Populating Property Address Data**: Missing PropertyAddress values were populated by matching ParcelID.

4. **Breaking Property Address into Individual Columns**: PropertyAddress was split into Address and City columns for better organization.

5. **Breaking Owner Address into Individual Columns**: Similarly, OwnerAddress was split into Address, City, and State columns.

6. **Changing 'Y' and 'N' to 'YES' and 'NO'**: Values in the SoldAsVacant column were standardized to 'YES' and 'NO' for consistency.

7. **Removing Duplicates**: Duplicate rows were removed based on specific columns to ensure data integrity.

8. **Deleting Unused Columns**: Unused columns such as OwnerAddress, PropertyAddress, TaxDistrict, and saledate were removed to streamline the dataset.

9. **Changing Column Names**: Column names were modified for clarity and consistency.

## Data Visualization with Tableau

- **Visualization**: The data was visualized using Tableau to gain insights into Seattle's real estate market.

  - **Dashboard Contents**:
    - Average Price Per Bedroom chart
    - Distribution of Bedrooms chart
    - Price Per Zip Code in Seattle map
    - Price Per Zip Code chart
    - Revenue for Year

![Tableau Dashboard Screenshot](https://github.com/ibrahimsaber1/Seattle-real-estate-analysis/blob/main/Dashboard%201.png)

## Usage

1. **Clone the Repository**: Clone this repository to your local machine using the following command:
  git clone https://github.com/ibrahimsaber1/Seattle-real-estate-analysis.git


2. **Execute SQL Scripts**: Execute the SQL scripts provided in the repository on your SQL database containing the Seattle real estate dataset.

3. **Review Results**: After executing each script, review the results to ensure that the data cleaning operations were successful.

## Contributions

Contributions to improve and extend the data cleaning process are welcome. Feel free to open an issue or submit a pull request with your suggestions or enhancements.

## Tableau Dashboard

- **Tableau File**: The Tableau dashboard file ![AriBnB Full Project.twbx](https://github.com/ibrahimsaber1/Seattle-real-estate-analysis/blob/main/AriBnB%20Full%20Project.twbx)is included in the repository.

## License

This project is licensed under the [MIT License](https://github.com/ibrahimsaber1/Seattle-real-estate-analysis/blob/main/License.md).

