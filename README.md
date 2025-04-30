# BUA451-FinalProject-ThomasBartolotta

## Summary
This project explores consumer data about Citibike usage in NYC. CitiBikes is the #1 bike share option in NY, and many use it to travel for work, exercise, or simple leasure. Citi offers a subscription based plan for people who regularly use their bikes.

##  Data
The data comes from BigQuery's public dataset: `[new_york_citibike.citibike_trips]`

##  Methods
- SQL querying with BigQuery
- Data wrangling and visualization in Python (Pandas, Matplotlib, Plotly, Seaborn, OneHotEncoder)
- Classification predictive modeling using Logistic Regression
- Github for doccumentation and organization

##  Key Insights
1. After observing the average duration of trips between their normal customers and their subscribers, it can be seen that the normal customers tend to ride for longer durations than the subscribers. This can be attributed due to the fact that the majority of Subscribers are NYC residents, and use the bikes for their commutes to work. Additionally, Customers usually tend to be tourists or just 1 time customers who. Becasue of this, 
2. The peak hours for riders include the hours of 7am-10am, as well as 12pm-4pm. This can be attributed to workers going to their shifts in the morning, as well as tourists/casual riders using them in the after noon. 4pm and 5pm have the highest amount of active riders in a day, due to both consumer groups using them at the same time; Subscribers going home from work and Customers continuing to explore the city
3. Logistic regression successfully predicted rider type with an F1-score of ~0.85, after accounting for class imbalance, using behavioral and demographic features.

##  Files
- `BUA451-FinalProject-ThomasBartolotta-CitiBike Analysis.ipynb`: Jupyter Notebook with all analysis and modeling
- `README.md`: This file

