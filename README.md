# Dynamic_Pricing
Dynamic pricing is a strategy where cab fares change in real-time based on factors like demand, traffic, weather, and availability of drivers. It ensures optimal pricing by increasing fares during peak hours and lowering them when demand is low. 

Key Insights
# Driver Availability & Ride Cost
0-20 drivers (Low) → Highest ride cost due to low supply.
20-40 drivers (Medium) → Cost decreases as availability improves.
40-60 drivers (High) → Further drop in ride cost.
60+ drivers (Very High) → Lowest ride cost due to high supply.
# Ride Duration & Cost
Strong linear correlation (0.92) → Longer rides lead to higher costs.
# Booking Time Impact
Morning & Afternoon → Ride costs tend to be higher.
Other time slots → Minor variations in cost.
# Area Type & Cost
Slight but meaningful cost differences across Urban, Suburban, and Rural areas.
Rural areas → Ride costs are notably higher in the Morning.
Model Performance & Selection
# Linear Regression (Best Choice)

Train R²: 0.8763 | Test R²: 0.8730
RMSE: Train → 0.3497 | Test → 0.3637
Performs well on both training and test data.
# Gradient Boosting (Overfitting Slightly)

Train R²: 0.8850 | Test R²: 0.8621
RMSE: Train → 0.3371 | Test → 0.3789
Slight overfitting and doesn’t significantly outperform Linear Regression.
Conclusion
Linear Regression is the most reliable choice for this dataset (~1000 rows).
More data & real-time updates can help optimize pricing strategies further.
