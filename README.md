#  Cyclistic Bike Share Analysis
### Google Data Analytics Certificate: Capstone Project

##  Project Overview
Analysis of 5.6 million Cyclistic bike rides to answer:
**"How do annual members and casual riders use Cyclistic bikes differently?"**

This is my capstone project for the Google Data Analytics Certificate,
following the Ask → Prepare → Process → Analyze → Share → Act framework.

##  Key Finding
| Members | Casual Riders |
|---------|--------------|
| Commuters  | Leisure riders  |
| Shorter rides (8.77 mins) | Longer rides (11.74 mins) |
| Peak on weekdays | Peak on weekends (+51%) |
| Active year-round | Almost disappear in winter (-92.6%) |
| Spike at 8am + 5pm | Gradual afternoon build |

##  Tools Used
- **Python** (Pandas, Matplotlib, Seaborn) → cleaning & analysis
- **Jupyter Notebook** → documentation
- **Tableau** → interactive dashboard

##  Data Source
- **Provider:** Motivate International Inc. (now Lyft Bikes and Scooters LLC)
- **Owner:** City of Chicago
- **License:** [Divvy Data License Agreement](https://divvybikes.com/data-license-agreement)
- **Download:** https://divvy-tripdata.s3.amazonaws.com/index.html
- **Period:** June 2025 - May 2026 (12 months)
- **Privacy:** Riders' personally identifiable informations are excluded

##  Repository Contents
```
├── Cyclistic_Bike_Share_Analysis.ipynb  ← Main analysis notebook
├── chart1_ride_length.png               ← Ride duration comparison
├── chart2_day_of_week.png               ← Weekly riding patterns
├── chart3_monthly.png                   ← Seasonal patterns
├── chart5_bike_type.png                 ← Bike type preferences
├── hourly_index.png                     ← Hourly index chart
├── hourly_pattern.png                   ← Raw count hourly pattern
├── summary_by_day.csv                   ← Daily ride summary
├── summary_by_month.csv                 ← Monthly ride summary
├── summary_bike_type.csv                ← Bike type summary
├── summary_ride_length.csv              ← Ride duration summary
├── summary_casual_hourly_index.csv      ← Casual hourly index data
└── summary_member_hourly_index.csv      ← Member hourly index data
```

##  Analysis Summary

### 1. Ride Length
Casuals ride **34% longer** than members (median: 11.74 vs 8.77 mins)
→ Suggests leisure/exploratory riding vs quick commutes

### 2. Day of Week
- Casuals: **+51%** more rides on weekends
- Members: **-23%** fewer rides on weekends
→ Opposite patterns confirm commuter vs leisure behavior

### 3. Monthly/Seasonal
- Casuals drop **92.6%** from summer peak to winter low
- Members drop only **75.2%**
→ Casuals are weather-dependent leisure riders

### 4. Hour of Day
- Members spike at **8am** (index 1.75) and **5pm** (index 2.60)
- Casuals show one smooth afternoon hill, no morning spike
→ Classic commute pattern vs flexible leisure schedule

### 5. Bike Type
- Both groups prefer electric bikes (~66-67%)
→ No meaningful difference here!

##  Top 3 Recommendations

**1. Target Casuals at Peak Times**
Run membership campaigns on weekend afternoons in summer
when casual ridership is highest!

**2. Create Flexible Membership Options**
Weekend-only or seasonal summer passes lower the barrier
for casual riders who only ride recreationally!

**3. Show Value of Year-Round Riding**
Market winter cycling routes, weather tips, and cost savings
to convert casual riders' mindset from seasonal to year-round!

##  Limitations
Data cannot distinguish between tourist casual riders
(who will never buy membership) and local casual riders
(our actual conversion targets). A future analysis could
filter repeat casual riders to identify locals specifically!

##  About
Capstone project completed as part of the
**Google Data Analytics Professional Certificate**
*By Krishma Dubadi*
