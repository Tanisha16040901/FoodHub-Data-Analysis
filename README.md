# Food Delivery Marketplace Optimization: FoodHub Data Analysis 📊🍲

## Project Context
The food delivery market in New York is rapidly expanding, with students and busy professionals relying heavily on delivery platforms due to demanding lifestyles. FoodHub is a food aggregator company that offers users seamless access to multiple restaurants through a single smartphone app. 

The platform handles the complete order cycle: matching customers with restaurants, orchestrating delivery logistics via a dedicated fleet, collecting customer ratings, and generating revenue by collecting a fixed margin from each completed order.

## Project Objective
As a Data Scientist, the goal of this project is to analyze the historical transaction and delivery logs stored by FoodHub. By evaluating demand patterns, operational fulfillment windows, and customer satisfaction metrics, this analysis provides actionable, data-backed strategic insights to optimize the marketplace framework, boost platform efficiency, and enhance user experience.

## Data Dictionary
The dataset encapsulates full transactional data points for each order:
- `order_id`: Unique identifier of the order.
- `customer_id`: Unique identifier of the customer.
- `restaurant_name`: Name of the restaurant vendor.
- `cuisine_type`: Category of cuisine ordered.
- `cost`: Total cost of the individual order (USD).
- `day_of_the_week`: Contextual placement of the order (Weekday vs. Weekend).
- `rating`: Customer satisfaction rating scored out of 5 (or 'Not given').
- `food_preparation_time`: Core kitchen turnaround time (from restaurant confirmation to driver pickup, in minutes).
- `delivery_time`: Logistics transit window (from driver pickup to drop-off confirmation, in minutes).

## Tech Stack
- **Language:** Python 3.x
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

## Key Insights & Actionable Business Recommendations
1. **Demand and Visibility Mapping:** High-demand cuisines and top-performing cluster vendors (e.g., Shake Shack) should be prioritized via premium featured listings or dynamic advertising during peak operational hours to maximize marketplace transaction volume.
2. **Systemic Feedback Enhancements:** To address data gaps caused by a high volume of unsubmitted ("Not given") customer feedback, the platform should introduce user engagement mechanics (such as a point-accumulation or gamification reward loop) to stabilize data ingestion for recommendation engines.
3. **Logistical Strategy:** Correlate total transit metrics (`food_preparation_time` + `delivery_time`) against regional customer retention levels to identify operational choke points and optimize delivery-partner driver routing.
