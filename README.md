# ✈️ Indian Airlines Power BI Dashboard

An interactive Power BI dashboard to compare Indian airlines on passenger traffic, customer ratings, fuel efficiency, CO₂ emissions, flight duration and estimated profit.

![Dashboard Preview](images/dashboard-preview.png)

## 📌 Overview
This project analyses data for five airlines: **Air India, Akasa Air, IndiGo, SpiceJet and Star Air**. Users can switch between airlines and filter by route and destination city to see how each carrier performs.

## 📊 Dashboard Features
- **Airline selector:** switch the whole report between airlines
- **Route and Destination City slicers:** drill into specific routes (e.g. AMD → CCU, Kolkata)
- **KPI callouts:** Total Passengers, Passenger Capacity, CO₂ per Passenger (kg), Fuel Efficiency, Avg. Flight Duration
- **Airline Ratings:** average customer rating out of 5
- **Monthly Passenger Trend:** passenger movement over time
- **Passengers by Airline:** total passengers compared across airlines
- **Estimated Profit by Airline:** profit share by airline (donut chart)

## 🛠️ Tools Used
- Power BI Desktop
- DAX (measures and calculations)
- Power Query (data cleaning)
- Microsoft Excel (data source)

## 📁 Repository Structure
| Folder | Contents |
|---|---|
| `dashboard/` | Power BI report (`.pbix`) and template (`.pbit`) |
| `data/` | Source dataset (`Indian_Airlines_Dataset.xlsx`) |
| `images/` | Dashboard preview and background templates |

## 🚀 How to Use
1. Download `Airline_analysis.pbix` from the `dashboard` folder.
2. Open it in **Power BI Desktop**.
3. If the data does not load, go to **Transform data → Data source settings** and point it to `data/Indian_Airlines_Dataset.xlsx`.
4. To use the template instead, open the `.pbit` file and select your own dataset.

## 💡 Key Insights
- *(Add 3 to 4 findings from your dashboard, e.g. which airline carries the most passengers, which has the best rating, which has the largest profit share.)*

## 👤 Author
**Aryan Bhardwaj**
[GitHub](https://github.com/aryanbhardwaj-tech)
