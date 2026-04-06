# Coupon-Acceptance-By-Customers
Analyze the data collected via a survey on Amazon Mechanical Turk to find out drivers acceptance of various kinds of coupons. The data is analyzed for various coupon types against drivers of a wide demography.

The respository contains the following files:

1. jupyter notebook - prompt.ipynb,
2. image files (.png) under the /images folder  - These are the files used in prompt.ipynb in the markup section
3. origina data file - coupons.csv
4. cleaned version of the original datafile - cleaned_coupons.csv. This is the data file that will used for analyzing coupon acceptance by different kids of drivers.

The data is analyzed for of two coupons types (1) Bar and (2) Coffee House. the below are the findings

### Bar Coupon coupon:
Based on the observations after analyzing Bar coupon acceptance against

  (1) frequency of visits
  (2) Age
  (3) Passenger is a kid
  (4) Cheap Restaurant visitors
    
I came to the following conclusions about who is more likely to accept bar coupons:

1. **Frequent Bar Goers**: Drivers who frequently visit bars ($\geq 3$ times per month).
2. **Younger Demographic**: People less than 30 years of age.
3. **Passenger Context**: Drivers who are **not** driving kids at the time of receiving the coupon.

Additional Insights:
* **Marital Status**: Non-widowed drivers accept bar coupons **2x more** than others.
* **Income Level**: Low-income drivers accept bar coupons at nearly the same rate as other income brackets.

> **Final Summary**: Overall, the largest group of likely coupon acceptors are **young, frequent bar-goers who do not have children as passengers.**

### Coffee House coupon:
Based on the observations after analyzing Coffee House coupon acceptance againt

(1) Age,
(2) Gender,
(3) Weather & Time
(4) Passenger type
(5) Occupation
(6) Frequency of coffee house visitors

I came to the following conclusions about who is more likely to accept bar coupons:

1. **Frequent Coffee House Visitors**: Coffee House coupon is widely accepted by drivers if they visit the coffee house at least once per month. 
2. **Weather Impack**: Coffee House coupons are accepted more on Sunny days.
3. **Occupation**: It appears people working in Healthcare industry, Students, Transportation and Building Maintenance are frequent acceptors of the coupon.

Additional Insights:
* **Younger Demographic**: Drives below 21 are the largest demographic that accepts the coupon and by and large there isn't much difference between other age groups.
* **Passenger Context**: Similarly Drivers with all kinds of passengers are equally likely to accept the coffe hosue coupons.
* **Income Level**: Income level has no impact on the coupon acceptance rate not does having or not not having kids.

> **Final Summary**: Overall, anybody who visits coffee house at least once is likely to accept the coupon on a sunny day.
