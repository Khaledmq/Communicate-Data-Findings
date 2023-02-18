# Udacity communicate-data-findings-project

This project is divided into two sections that demonstrate the significance and utility of data visualization techniques in the data analysis process. In the first section, I used Python visualization libraries to systematically explore a selected dataset, beginning with single variable plots and progressing to multiple variable plots. In the second part, I created a brief presentation that highlights interesting properties, trends, and relationships discovered in my New York go bike 2019 dataset. My findings will be communicated primarily through the transformation of my exploratory visualizations from the first part into polished, explanatory visualizations.



## Dataset

Bay Wheels is a regional public bicycle sharing system in the San Francisco Bay Area of California. Bay Wheels is the first regional and large-scale bicycle sharing system in California and the United States' West Coast.
In collaboration with Ford Motor Company, the system was officially relaunched as Ford GoBike in June 2017.
The system will eventually have 7,000 bicycles and 540 stations in San Francisco, Oakland, Berkeley, Emeryville, and San Jose.
I chose to work on New York Ford Go Bike data for my dataset in this project. 

## Summary of Findings
* Monthly rides fall from January to February, then steadily increase to nearly 50000 in September, then fall back to around 20000 in December. This evolution is not surprising given that weather influences whether or not people bike, which is why the winter and fall seasons had the lowest number of bike rides throughout the year.
* the distribution per hour shows that most trips occur at 8 am with a total that depasses 40000 trips , followed by 6pm , 5pm and 7am . these results are no surprise , trips at 8am are more likely trips to school or workplace , meanwhile trips at 5 and 6pm are more likely trips from school and workplace . It is worth noting that the least trips occurs at night between midnight and 4am , which is pretty expected , you can't take a bike trip when you're asleep !
* people tend to take shorter rides, with most rides lasting less than 10 minutes and even less than 5 minutes, and the number of trips decreases with duration, which is also pretty expected! * surprisingly, the vast majority of bikers are male, with a dominating percentage of 70.7%, while women make up only 22.8% of total bikers, the rest is unknown due to missing data or possibly people who do not identify as male or female.
* in my analysis , I choosed to set the following values with their respective age range :

Teen : 12-17 , Young adult : 18-35 ,Middle adult: 36-55 ,Old adult: 56-65 , Elderly: 66+ .

it is no surprise that Young adults take the most trips since Young adults tend to be the strongest and the healthiest , what is surprising though , is that Teens take the least trips , which tells me that the majority of these trips are taken more to workforce and even colleges , than high schools
* the number of subscribers is nearly 7 times the number of customers ! I think that this may mean that the vast majority of the users are taking bike trips regularly , which also reinforces my theory that most bike rides are taken to work or college , somewhere we go to on a daily basis !
* customers spend more time on trips than subscribers , interesting !
* that
it comes as no surprise that people would often spend more time outside when it's nice and sunny , the average trip duration is increasing steadily in spring season reaching more than 16 minutes average , to decrease a bit in summer to increase again near september than decrease steadily to december where trip duration doesn't exceed 10 minutes for the whole winter. 
* it seems like we have many outlirs that cause the average trip duration to be extremely high in the early hours of the day , perhaps this data belongs to people who take really long trips and have to wake up early , the average duration is higher in the early hours , around 5am , it decreases maintaining values under 20 minute sall day long .
* middle and young adults spend longer time in trips in contrary to elderly and old adults , which is very reasonable as it is always related to health and strength , to endure such long trips . surprisingly , and even though they make a small portion of the dataset , teens are taking relatively longer trips than others !
* judging by the boxplot above , we can see that there is no huge difference in men and women trip durations , even though females tend to take slightly longer rides.
* as we saw in the bivariate section , teens , followed by middle adults and young adults have the longer trips , but it seems that teens tend to have even longer trips in june and in spring/seasons !
* and while teens take longer trips in the spring/summer seasons, middle, followed by young adults, take longer trips in the early hours, while elderly, teens, and older adults take shorter trips at these hours, as mentioned earlier, this can be attributed to adults driving long distances to work.
* an unexpected turn of events! Females take longer trips in the early hours, with trips lasting up to 4 hours, compared to males' trips lasting nearly an hour and a half! which could explain


## Key Insights for Presentation

My three key insights for the presentation will be the distribution of gender and its relationship with trip duration in time, the distribution of usertype and its relationship with trip duration in time, and the distribution of age group and its relationship with trip duration in time.