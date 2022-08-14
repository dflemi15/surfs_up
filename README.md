Oahu Temperature Analysis for June and December

Overview
The purpose of this analysis is to provide a detailed look into the environmental conditions of Oahu, Hawaii for the sake of business development. The business that is being explored is a surfing and ice cream shop which would require stable temperatures and consistent foot traffic. An SQLite database that holds temperature trends in Oahu, provides a detailed look into the annual fluctuations for the months of June and December. This analysis was conducted with the use of Python packages (Pandas, SQLAlchemy, matplotlib, etc.).

Results
The first step of the analysis was to obtain basic summary statistics for both June and December. The results are as follows:

<img width="385" alt="image" src="https://user-images.githubusercontent.com/107585908/184536215-10155440-b3d9-45d3-885d-6e8c0e6778d0.png">

-	According to the results, June has a higher average temperature than December of approximately four degrees. Both months are very similar in temperature throughout the months which further indicates this location being great a place to establish this type of business from a temperature stability standpoint.  
-	The temperature in December appears to have a much lower minimum temperature than in June. This indicates that temperatures could drop below 60 degrees during this month which could have a negative impact on sales. The 25th percentile of temperatures fall below 69 degrees in December which is a four-degree difference of the same percentile in June.
-	The distribution of the data in both months appear to be normally distributed which would indicate the temperatures in both months remain relatively stable throughout both months.     

Summary
The results indicate that the temperature trend in the months of June and December appear to stay consistent throughout each month. June has a higher overall average temperature while December appears to be cooler. Sales may be impacted in the month of December as the temperature can fall below 70 degrees making it less ideal for water activities and the consumption of cold items.
To provide further visualization of the summary statistics, a histogram was developed for each month. The histogram for June and December is as follows:

<img width="447" alt="image" src="https://user-images.githubusercontent.com/107585908/184536236-9a1227f9-cda3-455d-ab6e-472e0006b4bc.png">

The histograms provide a visual understanding of the temperature trends in both months and makes it easier to decipher the distribution of the data. As indicated previously, December appears to have a lower average temperature that should be noted. Sales in this month are anticipated to be negatively impacted due to the cooler weather.  
