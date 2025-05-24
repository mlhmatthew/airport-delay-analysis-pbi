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

- [Airline Delays and Cancellations Dataset (Kaggle, 2018)](https://www.kaggle.com/datasets/yuanyuwendymu/airline-delay-and-cancellation-data-2009-2018?resource=download)
- External airport data from [OpenFlights](https://openflights.org/data.html)
- Weather insights from NCAR and BTS reports

## Files Included

- `report/airport_delay_analysis_report.pdf`: Technical report including dashboard screenshots and methodology
- `dashboard/airport_delay_dashboard.pbix`: *(File too large to host directly on GitHub)*

### Dashboard Previews

- [Airport Level Overview](assets/airport_level_view.png)
- [Flight Level Overview](assets/flight_level_view.png)
- [Flight Delayed and Cancelled Overview ](assets/delay_and_cancelled_flight_view.png)

### Dashboard Download

Due to GitHub’s file size limitations, the Power BI dashboard is hosted externally:

- [Download Power BI Dashboard (.pbix)](https://drive.google.com/file/d/1yV1rK773PYPTZNCY6X-ieCdXwAmx-t4J/view?usp=sharing)

**Note:** This file is large and may take time to download.

## Key Insights

- **Seasonal Congestion & Delay Trends:**
  - Ground processing times and delays spiked during **June–August** and **November–January**.
  - These periods correspond to summer vacations and winter holidays — peak travel seasons.
  - Ground processing times increased by approximately **30%**, and arrival/departure delays rose by **45–60%** compared to other months.

- **Customer Satisfaction Analysis:**
  - A derived `CustomerSatisfaction` metric showed:
    - **35%** of flights resulted in satisfied passengers,
    - **46%** neutral,
    - and **19%** dissatisfied.
  - Dissatisfaction peaked in **August**, particularly at **San Francisco International Airport (SFO)**, correlating with the highest monthly flight volume.
  - **JetBlue at SFO** had the highest monthly dissatisfaction rate of **38%** in **March**.

- **Airline and Airport Performance:**
  - Airline-specific trends revealed performance variability:
    - Some airlines consistently maintained lower delay rates.
    - Others contributed disproportionately to dissatisfaction spikes in specific months and locations.

- **Weather-Linked Delays:**
  - Late summer delays were strongly associated with thunderstorms and hurricanes (especially in Southeast and Midwest regions).
  - Winter delays (November–January) were tied to snowstorms, runway closures, and de-icing, particularly in airports like **Denver, New York, and Chicago**.
  - Based on BTS data, winter conditions accounted for **40%** of flight cancellations.

- **Operational Bottlenecks:**
  - Metrics such as `Average Ground Processing Time` and `Taxi In/Out` showed the highest strain during holiday peaks, indicating resource and runway constraints.
  - Airports with the **highest average delays** include **SFO**, **ORD**, and **ATL**, while others showed more consistent performance.


## License

This project is for academic purposes. Please cite the authors if reused or adapted.
