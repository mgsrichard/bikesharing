# bikesharing
Bikesharing with Tableau

## Overview
Our theoretical client wants to explore the idea of starting a bike sharing business like NYC's Citi Bike in her city of Des Moines, IA. To that end, we have downloaded a data file from Citi Bike with details on all bike trips taken during the month of August, 2019.  We want to look at the data and see whether the business model could be tenable for Des Moines. Below are pictures of the slides from the Tableau story I developed, NYC Results, in the Tableau file BikeShare Challenge. In the free version of Tableau, files must be saved on their public website, so this project can be viewed at [NYC Results]( https://public.tableau.com/app/profile/martha.richardson/viz/BikeshareChallenge_16454614958360/NYCResults?publish=yes). Click on the arrow at the top to advance through the slides. I have examined who rides the bikes, by gender and subscriber/non-subscriber, trip length, age of rider, time of day of trips, and frequency of trips per individual bike.

## Results of Analysis
Below you can view the slides from the Tableau Story I created, with some analysis for each slide. This readme file could serve as a good script for presenting the story to the client.


 ### Most Users are Subscribers
 
In the pie chart below, you can see that over 75% of users are subscribers. The large tourist population in NYC seems not to contribute an outsized share of customers. The subscribers almost certainly are locals, and since Des Moines likely has way fewer tourists than NYC, this is good news. Des Moines Citi Bike can focus its business and outreach on locals.

![Most Users are Subscribers](https://github.com/mgsrichard/bikesharing/blob/main/Resources/1%20Customer%20Type.png)



### Trips are Pretty Short

Trips are usually less than an hour long, and a large majority of them are less than 30 minutes long. These bikes get people where they want to go pretty quickly. Fast trips means potentially more rides per bike per day, more business, and more income.


![Trips are short](https://github.com/mgsrichard/bikesharing/blob/main/Resources/2%20Trips%20are%20Short.png)

### Women's Trips are Similar to Men's Trips

In the graph below, you can see that men make up a majority of riders. Women are still 1/4 to 1/3 of the population of the riders. Women's trips are fairly short just like men's trips. 

![Trips by Gender](https://github.com/mgsrichard/bikesharing/blob/main/Resources/3%20Trips%20by%20Gender.png)

### Do customers take longer trips?

Below you can see that subscribers and customers (non-subscribers) have very similar trip length. Being a subscriber or not doesn't seem to impact the duration of the trips.

![Trip Length by Type](https://github.com/mgsrichard/bikesharing/blob/main/Resources/4%20Trip%20length%20by%20type.png)

### Rush Hour

A single glance at this heatmap shows you when rush hour is. The implication is that the bikes are frequently used by commuters. Des Moines needs to make sure that they plan bike locations in residential areas where commuters are likely to live as well as around business districts close to places of employment.

![Rush Hour](https://github.com/mgsrichard/bikesharing/blob/main/Resources/5%20Rush%20Hour.png)

### Women and Men both commute

You can see below that women and men are both commuting by bike. Another thing you can see in the chart is that on the weekends, women are a larger percentage of riders, up to 50% during some parts of the day. Families and couples are probably using the bikes for fun outings. Commuting and family outings are not uniquely New York, so there's no reason people wouldn't use the bikes for similar trips in Des Moines.

![Weekdays Heatmap by Hour and Gender](https://github.com/mgsrichard/bikesharing/blob/main/Resources/6%20Weekdays%20Heatmap%20by%20hour%20and%20gender.png)

### Daily Use by Subscribers and Customers

In this chart, it's easier to see the larger proportion of women riders on the weekends in both groups. Among customers, women make up a larger share of the riders than among subscribers on all days, around 50%. There is no obvious rush hour in the data either for customers/non-subscribers.  The larger share of women every day and the lack of rush hour are both consistent with customers being tourists or families and couples on outings. 

![Daily Use by Type and Gender](https://github.com/mgsrichard/bikesharing/blob/main/Resources/7%20Daily%20use%20by%20type%20and%20gender.png)

### Some Bikes are Used Alot

Here you can see that some bikes are used more than others. You can move the cursor under where it says "Count of bikeshare" to see how many bikes are used a lot and how many are used only a little. This sort of information would be useful in identifying which bikes are more likely to need maintenance. In general, though, it seems like bike usage is generally fairly spread out among the bikes, and it's not the case that a minority of bikes are used for a majority of the rides. Another takeaway here is that NYC seems to have the bike distribution well balanced so that the use of the bikes is well balanced, and that ought to be a consideration in the selection of locations and numbers of bikes deployed at locations in Des Moines.

![Some bikes are used alot](https://github.com/mgsrichard/bikesharing/blob/main/Resources/8%20Some%20bikes%20are%20used%20a%20lot.png)

### How Old are the Riders/What is Happening with Date of Birth in the Data?

In the graph below you can see that generally, riders are mostly 50 and younger. However, there's a big anomaly in the data for date of birth. Firstly, a disproportionate number of people have 1/1/1969 as their date of birth. Is there some sort of auto-fill happening when people rent bikes where if they don't enter their date of birth properly then it is filled in with that date? I don't know. Also, there's a small but non-zero population of people whose reported date of birth makes them over 90, up to 135, which is clearly not correct. In a real life situation, a data glitch like this would make me call the client and figure out what's happening there. I wouldn't wait until we were presenting results at a meeting to find out what is going on.

![How old are riders](https://github.com/mgsrichard/bikesharing/blob/main/Resources/9%20How%20old%20are%20riders.png)

### Are Customers Younger than Subscribers?

The chart below demonstrates that subscribers and non-subscribers have the same basic age distribution. 

![Age by Subscriber Type](https://github.com/mgsrichard/bikesharing/blob/main/Resources/10%20Age%20by%20Subscriber%20type.png)


## Summary

Get ready, Des Moines!  There's nothing in the NYC data that indicates that the success of Citi Bike there is a purely NY thing.  Real people commute by bike, and use them for outings. People of all ages and genders use the bikes. On the weekends they are a fun addition to a day trip.  These things can all work in Des Moines. The research indicates that Des Moines Citi Bike should choose wisely where to place bike stations, near where commuters and tourists are likely to use them, and study their use pattern or predicted use pattern to put the right number of bikes in the right places. Advertising campaigns can target commuters, men, women, and tourists. A visualization that could be helpful for future analysis would be to analyze where bikes stop and start the day, to figure out if the matrix of bike locations will balance itself or if the company would need to relocate bikes during times of low usage back to high usage areas. Another good visulization would be to figure out the most popular locations and what they are possibly being used for, to help Des Moines choose some initial bike locations with a high probabillity of success to help the business have a strong launch.
