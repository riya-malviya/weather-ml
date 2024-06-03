# weather-ml

**Download data**<br/>
-> Go to https://www.ncdc.noaa.gov/cdo-web/search<br/>
-> Enter the years you want data for (I recommend starting with 1975), and search for the closest airport to you<br/>
-> Click add to cart on the airport you want<br/>
-> If there is no airport near you, try your city or country name instead<br/>
-> Go to the cart at https://www.ncdc.noaa.gov/cdo-web/cart<br/>
-> Select the csv format and click continue<br/>
-> Select all of the checkboxes for data types<br/>
-> Enter your email and click continue<br/>
-> You'll get an email with a link to download the data<br/>

**Here are the steps involved in building the model:**

-> Download weather data: The first step involves downloading weather data from NOAA. The link is provided above where you can download weather data for your area.<br/><br/>
-> Clean the data: After downloading the data, you will need to clean it. This involves removing columns with missing values and ensuring the data is in a format suitable for machine learning models.<br/><br/>
-> Train the model: Once the data is cleaned, you can use it to train a machine learning model. We used Ridge Regression, but you can also explore other models like XGBoost or Random Forest.<br/><br/>
-> Evaluate the model: Finally, we evaluate the performance of the model. Mean Absolute Error is one of the metrics used to measure the accuracy of the model.<br/><br/>

