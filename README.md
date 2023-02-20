## Mission-to-Mars Challenge
This challenge pulled together several weeks of learning in HTML, Web_scraping and data analysis and plotting.

### Overview 
Web scraping pulled in from two different websites about the Mission to Mars.  Each site provided different information that could be accessed and stored for data analysis.  


### Results
#### Part 1 :  Webscraping exercise of the [MRS Planet Sciece site](https://redplanetscience.com/).
* Titles and Previews were scrapped for each of the home page topics and saved into a CSV file which can be found here: [mars_data.csv](https://github.com/SusanFair/Mission-to-Mars/blob/main/mars_data.csv)

 #### Part 2 : This is a webscraping exercise using the [Mars Temperature Date site](https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html)
 Table data was scraped and Pandas was used to perform data analysis on the date.  This analysis resulted in several charts:
 

 * Mars average minimum temperatures by month :
![Avg Min Temp](https://github.com/SusanFair/Mission-to-Mars/blob/main/Resources/avg_min_temp.png)

* Mars average pressure by month :
    ![Avg Pressure](https://github.com/SusanFair/Mission-to-Mars/blob/main/Resources/avg_pressure.PNG)

* Mars yearly cycles based on minimum temperatures :
    ![Alt text](https://github.com/SusanFair/Mission-to-Mars/blob/main/Resources/Mars_temp_cycles.PNG)

#### Details
For detailed information and review the analysis please see the 2 working files:
* [Part 1 Jupyter Notebook](https://github.com/SusanFair/Mission-to-Mars/blob/main/part_1_mars_news.ipynb)
* [Part 2 Jupyter Notebooklabel](https://github.com/SusanFair/Mission-to-Mars/blob/main/part_2_mars_weather.ipynb)