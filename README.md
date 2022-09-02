# Ford_gobike-trip Data Exploration
## by Olamilekan Omotosho


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The data was recorded in February 2019 with 183412 records and 16 features.

Before exploration the given dataset was wrangled, some of the steps taken are:
* Extracted hour and day period from the start time
* Extracted user age
* converted the duration to minutes
* some columns not needed were dropped
* some high outliers were dropped

## Summary of Findings

> Findings from the analysis include the following: 
* Most of the users are within the age of `25` and `40`
* The users base is dominated by the `Male` Gender with over `70%`
* The users categories; `Subscriber` and `Customers`, is also dominated by the Subscribers with over `90%` of them
* The analysis showed top starting and ending station with `Market St at 10th St` and `San Francisco Caltrain Station 2(Townsend St at 4th St)` leading in both and respectively.
* Most trips are taken in the morning and in the evening, further anaysis showed that the trip spike between the hour of `7` and `9` in the morning and `4PM` and `6PM` in the evening
* Majority of the trips are between `5 - 25minutes` duration, using the normal distribution `90%` of the trip duration are less than `30minutes`
* Only `10%` of the users prefer to share bike for all trips
* It was also observed that `duration` and `age` have no linear relationship or correlation
* The average `duration` for the `subscribers` is lower than that of the `customers`. 
* The `female` gender trip `duration` is higher, this is could mean they ride slower or embark on longer trip compared to the `Male` gender.
* The average `age` for the other gender is the highest and that of the `Female` is the lowest.
* Customers that do not share bike for trips spend have higher duration and the average age is higher compared to those that share
* `8am` and `5am` records the highest `Male` and `Female`. The `Male` are the highest user for all the hour of the day
* All gender experince the highest users in the `Morning` followed by `Evening`.
* The average age of customers drops from `Morning` to `Night`. Thus imples that younger customers tend to use the bike more in the night compared to the older customers
* The analysis also showed that the average `age` of the `customers` is lower than the `subscribers`, impling that the subscribers are older people and they spend lower duration on trips.


## Key Insights for Presentation

For the presentation, I focus on the member info in relation to the trip and leave out  bike info. I start by introducing the member information, followed by the station info, then the trip period and likelihood of bike sharing.

After the univariate analysis where I paid attention to member info, I introduced the bivariate analysis consisting a pairwise correlation of age and hour, plotted a boxplot of member info and trip info and other pairs on member and trip info.

Finally, the multivariate analysis, I looked at some categorical features along with the day period and trip duration. I ensured I used different color palettes and well labelled.