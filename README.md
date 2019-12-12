## Worried about Flight Delays? Decide the Airline for your next Trip in the US.
In this project, I analyzed the airline data for delays in 2015 from __[here](https://github.com/sparkletiti/Lambda_Function_Project/blob/master/US_DoT_dataset_Jan_2015.csv)__. The dataset has information about 201664 flights giving flight date, carrier, flight number, origin, destination, arrival delay, distance covered by the flight, whether it was cancelled, reason for delay and the actual travel time of the flight. Some values for arrival delay are negative indicating that the flight arrived early.

This analysis will help flight carriers understand the proportion of delay in their flights and the reasons for delay using which they can plan measures to avoid these delays and ensure that their customers reach their destinations on time. Also, when you are planning to book your next flight, using this analysis, you can make a better choice at the carrier selection and anticipate whether chances of delay from your origin are high or low. Also, looking at the data, you will know the destinations you should try to avoid flying to in or out in particular seasons!

### Summary of Results
1. Delayed flight percentage was 49.76% in 2015. Majority of the flights were delayed upto 10-30 minutes.
2. Southwest Airlines is the most popular airline with maximum number of flights and has an equal proportion of delayed and non-delayed flights.
3. Majority of Delta Airlines flights have arrived on time without delay, while Envoy Airlines has the maximun delays with the highest delay proportion of 71%.
4. Vast majority of Southwest and Envoy flights weren’t more than 30 minutes late. Most of the delayed Southwest flights were from Las Vegas and Phoenix and Envoy flights were from DWF(Dallas) and ORD(Chicago, IL - O'Hare).
5. Delays in Chicago were almost double, compared to every other high volume airport. Maximum delays happened in Chicago due to snow delays in January! You will (almost certainly) be delayed if you are flying out of Chicago in January, based on 2015 data. If possible, avoid connecting flights in Chicago.
6. Long distance flights (distance of > 3000) are not getting delayed as much as short distance flights.
7. Origin cities of Atlanta, Salt Lake City, Boston and Washington D.C. have the highest arrival delays to their destinations because of weather conditions.

To view the code and graphs accurately, please __[click on this link](https://nbviewer.jupyter.org/github/phtelang/Worried-about-Flight-Delays-Decide-the-Airline-for-your-next-trip-in-the-US./blob/master/Worried%20about%20Flight%20Delays%2C%20decide%20the%20Airline%20for%20your%20next%20trip%20in%20the%20US..ipynb)__ as some of the Plotly graphs are not displayed directly on Github.

### Installation
- Download the source csv file on your local folder.
- Download the .ipynb (Jupyter file) and place it in the same folder as the source files.
- Install the requirements using pip install -r requirements.txt. (Make sure you use Python 3.)
