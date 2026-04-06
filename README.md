# Analyzing-Smart-City-Bike-Sharing-Data-using-Power-BI
## 📖 Table of Contents
- [Project Overview](#-project-overview)
- [Tools & Technologies](#-tools--technologies)
- [Data Cleaning & Preparation](#-data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [Key Insights](#-key-insights)
- [Recommendations](#-recommendations)
- [How to Use](#-how-to-use)

## 📊 Project Overview
To analyze bike station performance, usage efficiency, and operational patterns
across different locations and time periods using Power BI, and to provide data-
driven insights to improve bike availability, optimize resource distribution, and
enhance overall system efficiency.Create Interactive dashboards and to support
decision making.

## 🛠️ Tools & Technologies
- **Visualization:** Power BI
- **Documentation:** Mircrosoft Word

## 🧹 Data Cleaning & Preparation

✔ Imported dataset into Power Query

 Cleaned data by:

o Removing duplicates

o Handling missing values

o Trimming text fields

 ✔ Split Date and Time from “Last Update” column

 ✔ Extracted Latitude and Longitude from position field

## 🔍 Exploratory Data Analysis (EDA)
Relationships (Star Schema)

 Fact Table → StaƟon Dimension (Station ID)

 Fact Table → Contract Dimension (Contract ID)

 Fact Table → Date Dimension (Date ID)

Some stations have no bikes (empty) while others have more bikes

 Low occupancy rate indicates underutilization of stations

 Uneven distribution of bikes affects system efficiency

 Usage patterns vary by time and month, causing demand fluctuations

 Performance differs across locations/contracts (cities)

 Presence of closed stations impacts service availability

 Lack of proper monitoring can lead to poor decision-making

## 💡 Key Insights

 Total Bikes = ~19K

 Empty Stations = ~500

 Occupancy Rate = 0.36

“The dashboard shows current system status, including total bikes, empty
stations, and occupancy rate.”

 Some stations show 0 bikes (highlighted in red)

 Low occupancy stations identified

 More Demand in November Month

“Stations with zero bikes indicate high demand or poor bike distribution,
which explains the imbalance in the system.”

 Time chart (Bikes vs Time)
 Monthly trend chart


“Based on time trends, bike usage increases during peak hours, so
similar demand is expected in the future.”

## 🚀 Recommendations

 Low occupancy stations

 Bonus & banking data

“To improve the system, bikes can be redistributed to empty stations and
more bonus and banking stations can be added to increase usage.”


