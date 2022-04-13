# Coupons
“Will a customer accept the coupon?” The goal of this project is to use visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

# Data
This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, passenger, etc., and then asks people whether they will accept the coupon if they are the driver. Answers given that the users will drive there “right away” or “later before the coupon expires” are labeled as “Y = 1”, and answers “no, I do not want the coupon” are labeled as “Y = 0”. There are five different types of coupons—less expensive restaurants (under $20), coffee houses, carry out and take away, bars, and more expensive restaurants ($20–$50).

# Deliverables
assignment.5.1.Aykan.ipynb contains visualization and solution of whether customer is accepting a coupon or not. The Jupyter notebook uses a data file in data directory.

# Results
## Bar
Apparently, frequent bar-goers play signifcant role in accepting bar coupons, there seems other factors affecting this decision by age group and whom they are accompanied by in the car which means they are younger people who are single and crusing with friend(s). Also, from the heatmap, 'expiration' has positive correlation may affect the decision and 'has_children' numeric feature has a negative correlation on bar goers but seem negligible affect on coupon acceptance. On the other hand, visiting other establishments frequently does not seem an influencer on bar-goers.

## Coffee House
Apparently, frequent coffee house-goers play signifcant role in accepting coffee house coupons, age is affecting and whom they are accompanied by in the car which means whomever accepting coupons are younger people and driving with friend(s) or partners. Also, from the heatmap, coupon 'expiration' has a positive correlation may affect the decision and 'has_children' numeric feature has a negative correlation on coffee house goers but seem negligible affect on coupon acceptance. However, time of the day is important on accepting or declining a coupon because coffee store goers are midday people as their peak is 10AM and 2PM. Interestingly temperature play another significant role here on younger people whether to accept a coupon. On the other hand, visiting other establishments frequently does not seem an influencer on coffee house-goers.
