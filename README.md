# Airport Delay Analysis (Power BI Dashboard)

This repository contains the technical materials for a case study conducted as part of CST2102, analyzing U.S. airline delays in 2018 using SQL Server and Power BI.

## Project Overview

Flight delays impact airline efficiency, passenger satisfaction, and operational costs. This project uses the 2018 U.S. Airline Delays and Cancellations dataset to uncover patterns related to flight punctuality, customer satisfaction, and airport operations. It supports airport authorities and airline companies in making informed, data-driven decisions.

The interactive Power BI dashboard visualizes trends across multiple dimensions, offering a user-friendly platform to explore and interpret operational bottlenecks.

## Objectives

- Visualize delays by flight, airline, and airport
- Analyze seasonal trends and their impact on ground processing time
- Identify peaks in customer dissatisfaction
- Filter by airport, date, and carrier for detailed drill-down analysis

## Tools & Technologies

- Microsoft SQL Server (data preprocessing and modeling)
- Microsoft Power BI (dashboard creation)
- Microsoft Excel (dataset)
- Power Query, DAX

## Data Source

- [Airline Delays and Cancellations Dataset (Kaggle, 2018)](https://www.kaggle.com/)
- External airport data from [OpenFlights](https://openflights.org/data.html)
- Weather insights from NCAR and BTS reports

## Files Included

- `dataset/airline_delay_2018.xlsx`: Cleaned 2018 airline delay dataset
- `report/airport_delay_analysis_report.pdf`: Technical report including dashboard screenshots and methodology
- `dashboard/airport_delay_dashboard.pbix`: Power BI dashboard file *(to be uploaded separately due to size)*

## Key Insights

- **Ground processing times and delays** peaked during **June–August** and **November–January**, aligning with summer vacations and winter holidays.
- **Customer satisfaction** declined in peak months, especially at **SFO**.
- **Weather events** like thunderstorms and snowstorms played a key role in flight delays.

## Authors

James Benjamin Cole, Long Ho Mak, Mary Grace Lunar, Sirjan Bhalla  
Course: CST2102_010  
Instructor: Yasser Jafer  
Submission Date: March 7, 2025

## License

This project is for academic purposes. Please cite the authors if reused or adapted.
