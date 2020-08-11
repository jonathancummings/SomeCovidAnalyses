---
title: "COVID Analysis"
author: "Jonathan Cummings"
date: "8/10/2020"
output:
  html_document: 
    keep_md: yes
  fig_caption: true
---





# COVID-19 Analyses, August 10th edition

*What follows are the statistics and visualizations regarding COVID-19 that I find informative, important, or were just interesting to me to create as I learn more about data visualization. There are plenty of other analyses available, and analyses that come from disease experts, which I am not, so I encourage you to read and look at those as well!
The analyses use data last updated on 8/9/2020.*

## Global Analyses

### Recent Milestones & Statistics of Note
The number of comfirmed cases around the world recently passed 20 million. The 7-day average of daily cases peaked at 260 thousand on July 31st. The 7-day average of daily deaths has not reached a second peak, but appears to be leveling off. The number of active cases worldwide has not yet peaked. There are currently 6.4 million active cases.

### Global Total Cases
Currently the nation with the fewest per capita confirmed cases is Laos at 1 in every 364,331 individuals.  
The nation with the most per capita confirmed cases is Qatar at 1 in every 25.  
The global prevalence is 1 in every 384 individuals have had a confirmed case of COVID-19, an increase from 1 in 544 on 7/17/2020.

![\label Distribution of national confirmed COVID-19 case prevalence.](COVID-Analysis_files/figure-html/figure 1-1.png)

![Global Daily New Cases](figure/Global Daily Cases.PNG)  

### Global Deaths
There are 24 nations that have not had a COVID-19 fatality.  
Currently the nation with the fewest per capita deaths is Burundi at 1 in every 11,925,131 individuals.  
The nation with the most per capita deaths is San Marino at 1 in every 808 individuals.  
Globally  1 in every 10,531 individuals have died from COVID-19, an increase from 1 in 12,908 on 7/17/2020.  
1 in every 27 individuals who have contracted COVID-19 have died, a death rate of 3.65%, a decrease from 4.22% on 7/17/2020.  

If the current death rate in each nation remains the same, based on the number of currently active cases, i.e. without additional infections, the current global death toll of 737,453 would be expected to increase to 846,319.

![\label Distribution of national COVID-19 death prevalence.](COVID-Analysis_files/figure-html/figure 3-1.png)

![Global Daily New Deaths](figure/Global Daily Deaths.PNG)  

![Financial Times COVID-19 Tracker - Deaths*](figure/7 Day Death Trend.PNG)  

*[Financial Times COVID-19 Tracker link](https://www.ft.com/content/a26fbf7e-48f8-11ea-aeb3-955839e06441?fbclid=IwAR20L3uTETAJCy5X2qYMeyR_X6T8asbacJIgJ3zLnQXKszY-fcbl88V2ppM)  

![Financial Times COVID-19 Tracker - Deaths in Selected Nations*](figure/Selected National Death Trend.PNG)

### Global Active Cases
Currently their are 13 nations without any active cases of COVID-19, a decrease from 15 on 7/17/2020. The most populous nation without any active cases is Mauritius.  
The nation with the most per capita active cases is USA at 1 in every 138 individuals.  
The global prevalence is 1 in every 1,310 individuals with an active case of COVID-19, an increase from 1 in 1,648 on 7/17/2020.

![\label Distribution of national active COVID-19 case prevalence.](COVID-Analysis_files/figure-html/figure 2-1.png)

![Financial Times COVID-19 Tracker - New Cases Selected Nations*](figure/Selected National Cases Trend.PNG)  

## United States of America Analyses

### Recent Milestones & Statistics of Note
In the USA, the number of confirmed cases in the USA recently passed 5 million and the number of deaths surpassed 1 in every 2,000 individuals. The second peak of 7-day average daily cases occurred on July 25th at 69k cases, and the second peak of 7-day average number of deaths occurred on August 2nd at 1,130 cases. The number of active cases has not peaked and currently there are 2.37 million active cases.

### National Status
In the USA 1 in every 63 people has had a confirmed case of COVID-19 (1 in 87 on 7/17/2020), 1 in every 138 has an active case (1 in 174 on /17/2020), and 1 in every 1,995 individuals have died (1 in 2325 on 7/17/2020).  The USA in ranked in position 9 (11th on 7/17/2020) for per capita cases, position 1 (2nd on 7/17/2020) for per capita active cases, and position 10 (10 on 7/17/2020) for per capita deaths.







### USA Total Cases
Currently the state with the fewest per capita confirmed cases is Vermont at 1 in every 427 individuals.  
The state with the most per capita confirmed cases is Louisiana at 1 in every 35.  

![\label Map of Per Capita Confirmed Case Prevalence by State](COVID-Analysis_files/figure-html/figure 4-1.png)
![\label Prevalence of Active Cases by State](COVID-Analysis_files/figure-html/figure 5-1.png)


### USA Deaths
Currently the state with the fewest per capita deaths is Hawaii at 1 in every 41,667 individuals.  
The state with the most per capita deaths is New Jersey at 1 in every 557 individuals.  

In the USA 1 in every 32 individuals who have contracted COVID-19 have died, a death rate of 3.17% (3.77% on 7/17/2020). If the current death rate remains the same, then based on the number of currently active cases, i.e. without additional infections, the current national death toll of 166,053 would be expected to increase to 241,853.  

![\label Map of Per Capita Deaths by State](COVID-Analysis_files/figure-html/figure 6-1.png)
![\label Prevalence of Deaths by State](COVID-Analysis_files/figure-html/figure 7-1.png)

![Death Trends by State](figure/Selected State Deaths.PNG)  

### USA Active Cases
Currently the state with the fewest per capita active cases is Vermont at 1 in every 5,115 individuals, a change from Hawaii at 1 in 4,467 on 7/17/2020.  
The state with the most per capita active cases is Florida at 1 in every 45 individuals (1 in 60 on 7/17/2020).

![\label Map of Per Capita Active Case Prevalence  by State](COVID-Analysis_files/figure-html/figure 8-1.png)
![\label Prevalence of Active Cases by State](COVID-Analysis_files/figure-html/figure 9-1.png)

![Case Trends by State](figure/Selected State Cases.PNG)  

### Regional Analyses
![](COVID-Analysis_files/figure-html/regional-1.png)<!-- -->

![New England Case Trends by State](figure/New England Case Trend.PNG)  

![New England Death Trends by State](figure/New England Death Trend.PNG)


  
### Local Exposure Risk
There are also a number of resources available that are tracking how well COVID-19 is being controlled and the current status at a more local level. Two examples are [CovidActNow](https://covidactnow.org/) and [The Path to Zero](https://globalepidemics.org/key-metrics-for-covid-suppression/)  

![Path to Zero county level risk](figure/New England County Risk.PNG)  

![NH COVID Act Now status](figure/NH COVID Act Now Status.png)  

![Number of active cases per town in southeastern NH by town](figure/NH Map of Active Cases zoomed.png)

#### Status of Cases in the North versus the South
One question I've become curious about is the status of cases in the North versus the South. I defined states in the north as those with major population centers north of D.C. and Kansas City, and those with population centers south of those cities as southern states.  

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
   <td style="text-align:right;"> 535,384 </td>
   <td style="text-align:right;"> 2,005,312 </td>
   <td style="text-align:right;"> 105,842 </td>
   <td style="text-align:right;"> 322 </td>
   <td style="text-align:right;"> 86 </td>
   <td style="text-align:right;"> 2,079 </td>
   <td style="text-align:right;"> 26.7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> south </td>
   <td style="text-align:right;"> 1,797,557 </td>
   <td style="text-align:right;"> 3,093,960 </td>
   <td style="text-align:right;"> 56,920 </td>
   <td style="text-align:right;"> 102 </td>
   <td style="text-align:right;"> 59 </td>
   <td style="text-align:right;"> 2,959 </td>
   <td style="text-align:right;"> 58.1 </td>
  </tr>
</tbody>
</table>

# Sources:  
**Global, National and State Data** <https://www.worldometers.info/coronavirus/>  
**New Hampshire Data** [NHPR COVID-19 data tracking](https://www.nhpr.org/post/explore-data-tracking-covid-19-new-hampshire#stream/0)  
**Financial Times Images ** [Global Tracking](https://www.ft.com/content/a26fbf7e-48f8-11ea-aeb3-955839e06441) & [Trends](https://ig.ft.com/coronavirus-chart)  
**Risk Status** [CovidActNow](https://covidactnow.org/) and [The Path to Zero](https://globalepidemics.org/key-metrics-for-covid-suppression/)
