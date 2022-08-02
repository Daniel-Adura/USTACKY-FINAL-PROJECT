# Nigeria-COVID-19-Data-Analysis-Using-Python
Oyeleye Daniel's {Data Science Microdegree Capstone Project}

In this project, Data were obtained from three primary sources and these data were cleaned, visualized and analyzed.

There are a number of dependences that should be present to run the codes so as to get the correct result.
they are: requests, numpy, pandas, BeautifulSoup, seaborn, matplotlib.pyplot, warnings, datetime and the lxml parser.

The first thing I did was to scrap data from the NCDC official website using the beautiful soup library, the lxml parser and the request library whic helped me accessed the data on the official website.

I also obtained data from the other sources. like the John Hopkins website provided.

The data from the NCDC website had some format issues. I then wrote a series of codes for each column to clean them.

THE ANALYSIS/VISUALIZATION
1. The topTENLAB chart is the chart that shows the top 10 states with the highest Lab-confirmed COVID 19 cases. From the chart, we saw that they rank in this order: Lagos, Abuja, Rivers, Kaduna, Oyo, Plateau, Edo, Ogun, Delta, and Ondo.

2. The topTENDischarged chart is the chart that shows the top 10 states with the highest number of discharges. From the chart, we saw that they rank in this order: Lagos, Edo, FCT, Oyo, Rivers, Kano, Delta, Ondo, Osun, and Kaduna.

3. The line plot shows how the cases changes overtime, how the deaths, and recoveries changes overtime.

4. Here, the derivative was calculated to know each day's additional covid19 cases.

5. From the Derivative calculated above, the day with the highest additional cases was show in the subsequent chart as 22nd of December 2021.

6. Note that the heatmap shows an overall negative relationship between the variables. This is bacause the dataset contains extreme values like the number of covid 19 cases in Lagos. For Lagos, there is an inverse relationship between the CCVI and the number of Covid cases. Kaduna, however seems to have a somewhat positive relationship between the CCVI and the number of cases confirmed.

7. The regression_plot shows that there is a direct relationship between the Number of cases confirmed and the population. This is to say that as the population rises(along the y axis) the number of cases also increases (along the x axis). 

8. In my additional analysis, I included a new column which calculates the number of deaths per the cases confirmed. Then I compared this with the health system. The expectation here is that where a state scores high in its health system, the number of deaths per case confirmed should be low. And that's what the above chart depicts. where the health system is high, the death per case is small.

9. Finally, the RealGDP_Bars chart shows that the COVID19 pandemic had a negative effect on the country's real GDP, as it took it to the lowest it had ever been in the years under review.