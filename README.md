# HelioCentrics 

Welcome to HelioCentrics, a comprehensive analysis project for solar energy production. This project leverages Excel to perform detailed data analysis on solar power generation metrics.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Analysis Tasks](#analysis-tasks)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

HelioCentrics aims to analyze and visualize solar energy production data to provide valuable insights into power generation trends, efficiency, and performance metrics. This project includes various Excel-based data analysis tasks that are relevant to the role of a Residential Energy Analyst at Tesla.

## Dataset Description

The dataset used in this project includes the following columns:

- `DATE_TIME`: Timestamp of the data entry
- `PLANT_ID`: Unique identifier for the plant
- `SOURCE_KEY`: Source identifier
- `DC_POWER`: Direct Current power generated
- `AC_POWER`: Alternating Current power generated
- `DAILY_YIELD`: Daily energy yield
- `TOTAL_YIELD`: Total energy yield

## Analysis Tasks

### Data Validation
- Set up a data validation rule for the `DC_POWER` and `AC_POWER` columns to ensure only positive numbers can be entered.

### Sorting and Filtering
- Sort the dataset by `PLANT_ID` and then by `DATE_TIME` in ascending order.
- Apply filters to display data for specific `PLANT_ID`s.

### Pivot Table
- Create a pivot table to summarize the total `DAILY_YIELD` and `TOTAL_YIELD` for each `PLANT_ID`.
- Add a slicer to filter the pivot table data by `DATE_TIME`.

### Conditional Formatting
- Apply conditional formatting to the `DC_POWER` column to highlight values greater than a certain threshold.
- Use color scales to visualize the `AC_POWER` column values.

### Line Chart
- Create a line chart showing the trend of `DAILY_YIELD` over time for a specific `PLANT_ID`.
- Add a trendline to the chart to visualize the general production trend.

### Max/Min Values
- Identify the maximum and minimum values in the `DAILY_YIELD` column.
- Use the `MAXIFS` and `MINIFS` functions to find the maximum and minimum `DAILY_YIELD` for each `PLANT_ID`.

### Calculate Days Since Installation
- Calculate the number of days since installation for each entry using the `DATEDIF` function (if `INSTALLATION_DATE` is available).

### VLOOKUP
- Use `VLOOKUP` to find the `SOURCE_KEY` for a specific `PLANT_ID`.

### Cumulative Yield Calculation
- Calculate the cumulative `DAILY_YIELD` for each `PLANT_ID` over time using the `SUMIF` function.

### Summary Report
- Create a summary report showing total `DAILY_YIELD`, total `TOTAL_YIELD`, and average `DAILY_YIELD` per entry for each `PLANT_ID`.

## Getting Started

### Prerequisites
- Microsoft Excel or a compatible spreadsheet software.

### Installation
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/PPathole/heliocentrics.git
   ```
2. Open the Excel file located in the cloned repository.

## Usage

1. Open the Excel workbook.
2. Review the dataset and ensure it is properly formatted.
3. Perform the analysis tasks outlined in the [Analysis Tasks](#analysis-tasks) section.
4. Use the results to gain insights into solar energy production trends and performance.

## Results

The results of the analysis include visualizations, summary reports, and insights into the solar energy production data. These results can help in identifying trends, optimizing performance, and ensuring efficient energy production.

![Solar Production Chart](https://github.com/PPathole/heliometrics/blob/main/Screenshot%202024-07-11%20at%2019.39.01.png)

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact:

Pranay Pathole
- GitHub: [PPathole](https://github.com/PPathole)
- Email: ppathole@outlook.com

---

Thank you for using HelioCentrics! We hope this project helps you gain valuable insights into solar energy production.
