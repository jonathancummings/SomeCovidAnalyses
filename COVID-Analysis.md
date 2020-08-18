---
title: "COVID Analysis"
author: "Jonathan Cummings"
date: "8/17/2020"
output:
  html_document: 
    keep_md: yes
  fig_caption: true
---





# COVID-19 Analyses, August 17th edition

*What follows are the statistics and visualizations regarding COVID-19 that I find informative, important, or were just interesting to me to create as I learn more about data visualization. There are plenty of other analyses available, and analyses that come from disease experts, which I am not, so I encourage you to read and look at those as well!*  
**For a summary of format changes since the last update see the footnote at the bottom of the post.**  
*The analyses use data last updated on 8/16/2020.*  

## Global Analyses

### Recent Milestones & Statistics of Note
The number of comfirmed cases around the world is nearly 22 million. After peaking at 260 thousand on July 31st, the 7-day average of daily cases increased again and peaked at 261 thousand on August 14th. The 7-day average of daily deaths reached a second peak of 5871 on August 13th. The number of active cases worldwide may have peaked on Augsut 15th at a bit more than 6.5 million active cases. See https://www.worldometers.info/coronavirus/worldwide-graphs/ for visualizations of this data.

### Global Total Cases
Currently the nation with the fewest per capita confirmed cases is Laos at 1 in every 331,302 individuals.  
The nation with the most per capita confirmed cases is Qatar at 1 in every 24 individuals.  
The global prevalence is 1 in every 354 individuals with a confirmed case of COVID-19, an increase from 1 in 544 on 7/17/2020.

![\label Distribution of national confirmed COVID-19 case prevalence.](COVID-Analysis_files/figure-html/figure 1-1.png)

### Global Deaths
There are 24 nations that have not reported a COVID-19 fatality.  
Currently the nation with the fewest per capita deaths is Burundi at 1 in every 11,931,934 individuals.  
The nation with the most per capita deaths is San Marino at 1 in every 808 individuals.  
Globally  1 in every 10,016 individuals have died from COVID-19, an increase from 1 in 12,908 on 7/17/2020.  
1 in every 28 individuals who have contracted COVID-19 have died, a death rate of 3.53%, a decrease from 4.22% on 7/17/2020.  

If the current death rate in each nation remains the same, based on the number of currently active cases, i.e. without additional infections, the current global death toll of 775,510 would be expected to increase to 890,854.

![\label Distribution of national COVID-19 death prevalence.](COVID-Analysis_files/figure-html/figure 3-1.png)

For visualizations of the trend in global COVID-19 deaths, the relative proportion of deaths by region, and trends and national and state trends see the Financial Times COVID-19 Tracker: [Financial Times COVID-19 Tracker link](https://www.ft.com/content/a26fbf7e-48f8-11ea-aeb3-955839e06441?fbclid=IwAR20L3uTETAJCy5X2qYMeyR_X6T8asbacJIgJ3zLnQXKszY-fcbl88V2ppM)

### Global Active Cases
Currently their are 13 nations without any active cases of COVID-19, a decrease from 15 on 7/17/2020. The most populous nation without any active cases is Macao.  
The nation with the most per capita active cases is Aruba at 1 in every 118 individuals.  
The global prevalence is 1 in every 1,302 individuals with an active case of COVID-19, an increase from 1 in 1,648 on 7/17/2020.

![\label Distribution of national active COVID-19 case prevalence.](COVID-Analysis_files/figure-html/figure 2-1.png)

## United States of America Analyses

### Recent Milestones & Statistics of Note
In the USA, the number of confirmed cases in the USA recently passed 5.6 million and the total number of deaths is likely two days away from passing 175 thousand. The second peak of 7-day average daily cases occurred on July 25th at 69k cases, and the second peak of 7-day average number of deaths occurred on August 2nd at 1,130 cases. The number of active cases has not peaked and currently there are 2.47 million active cases.

### National Status
In the USA 1 in every 59 people has had a confirmed case of COVID-19 , 1 in every 133 has an active case , and 1 in every 1,910 individuals have died.  Thesea are changes from 1 in 87, 1 in 174, and 1 in 2,325 respectively on 7/17/2020. The USA in ranked in position 8 for per capita cases, position 2 for per capita active cases, and position 10 for per capita deaths. These are changes from 11th, 2nd, and 10th respectively on 7/17/2020.









### USA Total Cases
Currently the state with the fewest per capita confirmed cases is Vermont at 1 in every 409 individuals.  
The state with the most per capita confirmed cases is Louisiana at 1 in every 34.  

![\label Map of Per Capita Confirmed Case Prevalence by State](COVID-Analysis_files/figure-html/figure 4-1.png)
![\label Prevalence of Active Cases by State](COVID-Analysis_files/figure-html/figure 5-1.png)

![Animation of Total Confirmed Case Counts in the USA](US_Cases.gif)

![Animated Map of Total Confirmed Case Counts in the USA](US_Cases_Map.gif)

### USA Deaths
Currently the state with the fewest per capita deaths is Hawaii at 1 in every 35,397 individuals.  
The state with the most per capita deaths is New Jersey at 1 in every 555 individuals.  

In the USA 1 in every 32 individuals who have contracted COVID-19 have died, a death rate of 3.11% (3.77% on 7/17/2020). If the current death rate remains the same, then based on the number of currently active cases, i.e. without additional infections, the current national death toll of 173,469 would be expected to increase to 250,476.  

![\label Map of Per Capita Deaths by State](COVID-Analysis_files/figure-html/figure 6-1.png)

![\label Prevalence of Deaths by State](COVID-Analysis_files/figure-html/figure 7-1.png)

![Animation of Total Deaths in the USA](US_Deaths.gif)

![Animated Map of Total Deaths in the USA](US_Deaths_Map.gif)

### USA Active Cases
Currently the state with the fewest per capita active cases is Vermont at 1 in every 4,952 individuals, a change from Hawaii at 1 in 4,467 on 7/17/2020.  
The state with the most per capita active cases is Florida at 1 in every 42 individuals (1 in 60 on 7/17/2020).

![\label Map of Per Capita Active Case Prevalence  by State](COVID-Analysis_files/figure-html/figure 8-1.png)

![\label Prevalence of Active Cases by State](COVID-Analysis_files/figure-html/figure 9-1.png)

![Animatied Map of New Cases in the USA](US_New_Cases_Map.gif)

![Animatied Map of New Deaths in the USA](US_New_Deaths_Map.gif)

### Regional Analyses


The following animations display the progression of COVID-19 in New England at the county level. 

#### Cases
##### Total Cases
![](NE_Cases_Map.gif)

##### 7-Day Running Average of New Cases
![](NE_New_Cases_Map.gif)

##### New Cases Over the Past 2 Weeks
![](NE_Recent_Cases_Map.gif)  

#### Deaths
##### Total Deaths
![](NE_Deaths_Map.gif)  

##### Seven Day Running Average of New Deaths
![](NE_New_Deaths_Map.gif)

##### New Deaths Over the Past 2 Weeks
![Animatied Map of Recent Deaths in New England](NE_Recent_Deaths_Map.gif)

### Local Exposure Risk
There are also a number of resources available that are tracking how well COVID-19 is being controlled and the current status at a more local level. Two examples are [CovidActNow](https://covidactnow.org/) and [The Path to Zero](https://globalepidemics.org/key-metrics-for-covid-suppression/). I check Covid Act Now like I check the weather. Red is kind of like going out into a class 5 hurricane, Orange a tropical storm, Yellow a thunderstorm, and Green some rain. Regardless probably good to have your umbrella.  

![NH COVID Act Now status](figure/NH COVID Act Now Status.png)  

![Number of active cases per town in southeastern NH by town](figure/NH Map of Active Cases zoomed.png)

#### Status of Cases in the North versus the South
One question I've become curious about is the status of cases in the North versus the South. I defined states in the north as those with major population centers north of D.C. and Kansas City, and those with population centers south of those cities as southern states.  
Whether a state is categorized as northern or southern is undoubtedly a very poor proxy for the percentage of time people spend indoors, and the measures taken to reduce COVID-19 spread. We do see differences between the regions, and the difference has grown over the course of the summer.

![](COVID-Analysis_files/figure-html/NorthSouth-1.png)<!-- -->![](COVID-Analysis_files/figure-html/NorthSouth-2.png)<!-- --><table class="table" style="margin-left: auto; margin-right: auto;">
 <thead>
  <tr>
   <th style="text-align:left;"> NorthOrSouth </th>
   <th style="text-align:right;"> Active </th>
   <th style="text-align:right;"> Cases </th>
   <th style="text-align:right;"> Deaths </th>
   <th style="text-align:right;"> Active_Prevalence </th>
   <th style="text-align:right;"> Prevalence </th>
   <th style="text-align:right;"> Death_Prevalence </th>
   <th style="text-align:right;"> PercentActive </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> north </td>
   <td style="text-align:right;"> 535,807 </td>
   <td style="text-align:right;"> 2,091,295 </td>
   <td style="text-align:right;"> 107,143 </td>
   <td style="text-align:right;"> 320 </td>
   <td style="text-align:right;"> 82 </td>
   <td style="text-align:right;"> 2,043 </td>
   <td style="text-align:right;"> 25.62 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> south </td>
   <td style="text-align:right;"> 1,880,248 </td>
   <td style="text-align:right;"> 3,347,408 </td>
   <td style="text-align:right;"> 62,792 </td>
   <td style="text-align:right;"> 98 </td>
   <td style="text-align:right;"> 55 </td>
   <td style="text-align:right;"> 2,721 </td>
   <td style="text-align:right;"> 56.17 </td>
  </tr>
</tbody>
</table>

# Footnote:  
I've added some new visualizations. I hope you find the new animations I've produced informative. I think they present the trend and status of the pandemic well.
To save me time and to better direct web traffic to visualization sources I'm no longer clipping images from most other pages. I've included links to those pages throughout if you still want to go see those visualizations.

# Sources:  
**Global, National and State Data** 
[Worldometer](https://www.worldometers.info/coronavirus/)  
*This is my go to site for the raw data on current COVID-19 status at the global and state level*  
[Our World in Data](https://ourworldindata.org/coronavirus?fbclid=IwAR07yo3cNGS_ntGDjaLXjvPM-0mkmdaMP8GfJR62UtlxVa2jLHJmjsE4gDU)   
*I don't go here as often, but this site has the most in depth analysis and includes interactive and customizable visualizations*  
[Financial Times Global Deaths Tracking](https://www.ft.com/content/a26fbf7e-48f8-11ea-aeb3-955839e06441) & [Financial Times Trends](https://ig.ft.com/coronavirus-chart)  
*Good visualization for trends through time and comparing regions, nations, and states*  

**New Hampshire Data** [NHPR COVID-19 data tracking](https://www.nhpr.org/post/explore-data-tracking-covid-19-new-hampshire#stream/0)  *My go to site for NH data*  

**Risk Status** [CovidActNow](https://covidactnow.org/) and [The Path to Zero](https://globalepidemics.org/key-metrics-for-covid-suppression/)
