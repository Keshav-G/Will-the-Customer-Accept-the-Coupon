# Will-the-Customer-Accept-the-Coupon
Answering if a  customer would accept a restaurant coupon delivered to their cell phone. The restaurant coupon would be delivered when they pass by said restaurant while driving. This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk.

This central portion of this analysis examins 2 coupon types - Bar coupons and Carry out & Take away coupons, and at what rate / percentage various subsets of the driver population accept these coupons. A summary of the findings for each is below, along with Next Steps and Recommendations. A link to the full analysis and report is provided at the end. Note: "Carry out & Take away" is one category of coupon. "Carry out & Take away" will also be abbreviated as "COTA".

<br/>

**Bar Coupon Hypotheses / Analysis:**

1. Drivers will accept bar coupons less than half the time overall (41.2%).

2. Drivers who go to the bar on average more than 3 times per month will accept bar coupons at more than twice the rate (76.2%) of drivers who don't (37.3%).

3. Drivers older than 25 who go to the bar on average more than once a month will accept bar coupons at a much higher rate (~68.3%) than the overall population of drivers (41.2%).

4. Drivers who go to the bar more than once a month on average, have a passanger that's not a kid, and have an occupation outside of farming, fishing, and forestry will accept bar coupons at a much higher rate (71.4%) than the overall population (41.2%).
<br/>


**Carry Out & Take Away Coupon Hypotheses / Analysis:**

1. Drivers will accept COTA coupons at a much higher rate overall than they will accept bar coupons (73.8% vs. 41.2%, respectively).
  
2. COTA coupon acceptance rate plateaus after 4 - 8 average monthly visits to COTA establishments.
   
3. Drivers who on a monthly average never visit COTA establishments will have the highest acceptance rate of COTA coupons.

4. Drivers of all income levels have at least a 65% acceptance rate for COTA coupons.

5. Drivers with kids in the car and travelling in the opposite direction of a COTA coupon's establishment are slightly less likely to accept that COTA coupon than the general population (69.7% vs. 73.8%).

6. The 50+ age group accepts COTA coupons at a higher rate than the overall population (77.0% vs 73.8%).
<br/>


**Actionable Recommendations from Current Analysis**

1. Bar coupons can be sent to all drivers, but should especially be sent to:
   
   a. Drivers who frequent bars more than 3 times per month on average
   b. Drivers 25 years of age and older who go to the bar more than once a month on average

2. Carry out & Take away coupons have very high rates of acceptance among all drivers, so should be sent out to all drivers, especially:

   a. Drivers who on average never frequent carry-out and take-away establishments
   b. Drivers age 50+

3. Income level is not a major consideration when sending out COTA coupons, so doesn't need to be factored into any algorithms.

<br/>

**Next Steps for Future Analysis**

1. Perform analyses of acceptance rates for the remaining coupon types.

2. Analyze acceptance rates based on distance from the establishment the coupon is for. Break this down by direction and whether or not the driver has an urgent destination.

3. Explore if temperature and weather have any effect on coupon acceptance rates.

4. Determine if time has any effect on coupon acceptance rates.

5. Examine if marital status and having children affects acceptance rates, even if the spouse / kids aren't in the car.

6. Does solo travel affect acceptance rates vs. having any type of passanger in the car? 

<br/>


**Link to Jupyter Notebook (Full Analysis and Report):**
<br/>
https://github.com/Keshav-G/Will-the-Customer-Accept-the-Coupon/blob/265f25e95630d25d14ad7157b31830d4a83bac63/Assignment%205.1_Will%20the%20Buyer%20Accept%20the%20Coupon_Keshav.ipynb

<br/>
