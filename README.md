# Real-Time Uber & Lyft Dynamic Pricing (Hybrid Dynamic)

In this repository, I worked with two dynamic pricing datasets The first one real-timeuber-dynamic-pricing is based on real-time data and uses a broader range of features making it a hybrid dynamic pricing model. This model takes into account more factors reflecting real-world complexities.The second dataset contains fewer features but is built on similar principles.

For both datasets I used median imputation to avoid the influence of outliers ensuring that the imputed values were more stable Additionally I removed outliers to prevent them from skewing the model and to make sure it captured more reliable trends.

Challenges and Data Insights

Data Cleaning: Both datasets had missing values and duplicates. We carefully removed duplicates and handled missing values with median imputation to ensure more reliable predictions.

Outliers: Removing outliers was critical, as they can significantly affect the model's predictions. They were handled to improve model accuracy by ensuring the data reflected general trends rather than extreme cases.

Feature Selection=  In the real-time dataset, more features like surge multipliers, real-time traffic, and weather data were included. These additional features brought more complexity and required careful consideration to ensure relevant data was being used. In contrast, the second dataset had fewer features, focusing more on time and location-based data.

Surge Pricing: Lyft showed surge multipliers above 1.0, unlike Uber, which only used 1.0. This was an interesting distinction in how the companies handle surge pricing.

This hybrid dynamic pricing model leverages real-time data to better reflect the complexities of pricing, while the other dataset offers a simpler but effective approach.
