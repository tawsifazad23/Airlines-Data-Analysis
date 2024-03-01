# Airline Data Analysis Project 

## Overview

This project involves a comprehensive analysis of a diverse fleet airline company's data, focusing on increasing occupancy rates and average profit per seat. The airline is dealing with several challenges such as stricter environmental regulations, higher flight taxes, increased interest rates, rising fuel prices, and a tight labor market. Our primary objectives are to increase occupancy rates, improve pricing strategies, and enhance customer experience.

## Data Sources

The analysis utilizes data from a `travel.sqlite` database, containing the following tables:

1. `aircrafts_data`
2. `airports_data`
3. `boarding_passes`
4. `bookings`
5. `flights`
6. `seats`
7. `ticket_flights`
8. `tickets`

## Methodology

### Data Exploration

Initial exploration involves querying the database to understand the structure and contents of each table. This is followed by identifying null values and ensuring data integrity.

### Basic Analysis

- **Aircraft with More Than 100 Seats**: Identifying larger aircraft in the fleet.
- **Ticket Bookings and Total Amount Earned Over Time**: Analyzing trends in ticket sales and revenue, using line chart visualizations.
- **Average Charges per Aircraft with Different Fare Conditions**: Comparing average costs for business, economy, and comfort classes across different aircraft.

### Analyzing Occupancy Rate

- **Total Revenue and Average Revenue Per Ticket**: Calculating these metrics for each aircraft type to identify the most profitable models.
- **Average Occupancy Per Aircraft**: Understanding how effectively seats are filled and identifying opportunities to increase occupancy rates.
- **Impact of a 10% Increase in Occupancy Rate**: Estimating the financial benefits of increasing occupancy rates across the fleet.

## Key Findings

- **Occupancy Rates**: Some aircraft have higher occupancy rates, suggesting a more efficient utilization of capacity.
- **Revenue Trends**: Correlation between ticket bookings and revenue, with potential to optimize during peak booking periods.
- **Pricing Strategy**: Variations in average fares across different classes and aircraft types, indicating scope for pricing optimization.

## Conclusions and Recommendations

- **Pricing Strategy**: Adjust prices based on aircraft type and class to balance demand and profitability.
- **Increase Occupancy Rates**: Focus on underperforming flights and implement strategies to boost occupancy without compromising customer satisfaction.
- **Customer Experience**: Enhance service quality to increase customer loyalty and attract new passengers, potentially through personalized offers or improved onboard experiences.

## Technical Details

- **Libraries Used**: sqlite3, pandas, matplotlib, seaborn
- **Database Connection**: Established using sqlite3, querying with pandas.

## Conclusion

By leveraging data-driven insights, the airline can effectively navigate through current challenges, optimize operations, and improve profitability.
