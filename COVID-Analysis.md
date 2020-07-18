---
title: "COVID Analysis"
author: "Jonathan Cummings"
date: "7/17/2020"
output:
  html_document: 
    keep_md: yes
  fig_caption: true
---





# Some Covid Analyses

What follows are the statistics and visualizations regarding COVID-19 that I find informative, important, or were just interesting to me to create as I learn more about data visualization. There are plenty of other analyses available, and analyses that come from disease experts, which I am not, so I encourage you to read and look at those as well!

The analyses use data last updated on 7/17/2020.

## Global Analyses

### Global Total Cases
Currently the nation with the fewest per capita confirmed cases is Papua New Guinea at 1 in every 559,608 individuals.  
The nation with the most per capita confirmed cases is Qatar at 1 in every 26.  
The global prevalence is 1 in every 544 individuals have had a confirmed case of COVID-19.

![\label Distribution of national confirmed COVID-19 case prevalence.](COVID-Analysis_files/figure-html/figure 1-1.png)

![Global Daily New Cases](figure/Global Daily Cases.PNG)  

### Global Deaths
Currently the nation with the fewest per capita deaths is Burundi at 1 in every 11,902,780 individuals.  
The nation with the most per capita deaths is San Marino at 1 in every 808 individuals.  
Globally  1 in every 12,908 individuals have died from COVID-19.  
1 in every 24 individuals who have contracted COVID-19 have died, a death rate of 4.22%.  

If the current death rate in each nation remains the same, then based on the number of currently active cases, i.e. without additional infections, the current global death toll of 604,111 would be expected to increase to 688,183.

![\label Distribution of national COVID-19 death prevalence.](COVID-Analysis_files/figure-html/figure 3-1.png)

![Global Daily New Deaths](figure/Global Daily Deaths.PNG)  

![Financial Times COVID-19 Tracker - Deaths*](figure/7 Day Death Trend.PNG)  

*[Financial Times COVID-19 Tracker link](https://www.ft.com/content/a26fbf7e-48f8-11ea-aeb3-955839e06441?fbclid=IwAR20L3uTETAJCy5X2qYMeyR_X6T8asbacJIgJ3zLnQXKszY-fcbl88V2ppM)  

![Financial Times COVID-19 Tracker - Deaths in Selected Nations*](figure/Selected National Death Trend.PNG)

### Global Active Cases
Currently their are 15 nations without any active cases of COVID-19. The most populous nation without any active cases is Laos.  
The nation with the most per capita active cases is French Guiana at 1 in every 118 individuals.  
The global prevalence is 1 in every 1,648 individuals with an active case of COVID-19.

![\label Distribution of national active COVID-19 case prevalence.](COVID-Analysis_files/figure-html/figure 2-1.png)

![Financial Times COVID-19 Tracker - New Cases Selected Nations*](figure/Selected National Cases Trend.PNG)  

## United States of America Analyses
### National Status
In the USA 1 in every 87 people has had a confirmed case of COVID-19, 1 in every 174 has an active case, and 1 in every 2,325 individuals have died.  The USA in ranked in position 11 for per capita cases, position 2 for per capita active cases, and position 10 for per capita deaths.







### USA Total Cases
Currently the state with the fewest per capita confirmed cases is Hawaii at 1 in every 1,062 individuals.  
The nation with the most per capita confirmed cases is New York at 1 in every 45.  

![\label Map of Per Capita Confirmed Case Prevalence by State](COVID-Analysis_files/figure-html/figure 4-1.png)
![\label Prevalence of Active Cases by State](COVID-Analysis_files/figure-html/figure 5-1.png)


### USA Deaths
Currently the state with the fewest per capita deaths is Hawaii at 1 in every 62,500 individuals.  
The state with the most per capita deaths is New Jersey at 1 in every 564 individuals.  

In the USA 1 in every 27 individuals who have contracted COVID-19 have died, a death rate of 3.77%. If the current death rate remains the same, then based on the number of currently active cases, i.e. without additional infections, the current national death toll of 142,379 would be expected to increase to 213,872.  

![\label Map of Per Capita Deaths by State](COVID-Analysis_files/figure-html/figure 6-1.png)
![\label Prevalence of Deaths by State](COVID-Analysis_files/figure-html/figure 7-1.png)

![Death Trends by State](figure/Selected State Deaths.PNG)  

### USA Active Cases
Currently the state with the fewest per capita active cases is Hawaii at 1 in every 4,467 individuals.  
The state with the most per capita active cases is Arizona at 1 in every 60 individuals.

![\label Map of Per Capita Active Case Prevalence  by State](COVID-Analysis_files/figure-html/figure 8-1.png)
![\label Prevalence of Active Cases by State](COVID-Analysis_files/figure-html/figure 9-1.png)

![Case Trends by State](figure/Selected State Cases.PNG)  

### Regional Analyses
![](COVID-Analysis_files/figure-html/regional-1.png)<!-- -->

![New England Case Trends by State](figure/New England Case Trend.PNG)  

![New England Death Trends by State](figure/New England Death Trend.PNG)


  
### Local Exposure Risk
There are also a number of resources available that are tracking how well COVID-19 is being controlled and the current status at a more local level. Two examples are [CovidActNow](https://covidactnow.org/) and [The Path to Zero](https://covidactnow.org/)  

![Path to Zero county level risk](figure/New England County Risk.PNG)  

![Number of active cases per town in NH](figure/NH Map of Active Cases.png)  

![Number of active cases per town in southeastern NH by town](figure/NH Map of Active Cases zoomed.png)

#### Status of Cases in the North versus the South
One question I've become curious about is the status of cases in the North versus the South. I defined states in the north as those with major populaton centers north of D.C. and Kansas City, and those with population centers south of those cities as southern states.  

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
   <td style="text-align:right;"> 588,894 </td>
   <td style="text-align:right;"> 1,693,410 </td>
   <td style="text-align:right;"> 101,595 </td>
   <td style="text-align:right;"> 308 </td>
   <td style="text-align:right;"> 107 </td>
   <td style="text-align:right;"> 2,210 </td>
   <td style="text-align:right;"> 34.78 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> south </td>
   <td style="text-align:right;"> 1,269,914 </td>
   <td style="text-align:right;"> 2,000,507 </td>
   <td style="text-align:right;"> 38,126 </td>
   <td style="text-align:right;"> 143 </td>
   <td style="text-align:right;"> 91 </td>
   <td style="text-align:right;"> 4,164 </td>
   <td style="text-align:right;"> 63.48 </td>
  </tr>
</tbody>
</table>

# Sources:  
**Global, National and State Data** <https://www.worldometers.info/coronavirus/>  
**New Hampshire Data** [NHPR COVID-19 data tracking](https://www.nhpr.org/post/explore-data-tracking-covid-19-new-hampshire#stream/0)  
**Financial Times Images ** [Global Tracking](https://www.ft.com/content/a26fbf7e-48f8-11ea-aeb3-955839e06441) & [Trends](https://ig.ft.com/coronavirus-chart)  
**Risk Status** [CovidActNow](https://covidactnow.org/) and [The Path to Zero](https://covidactnow.org/)
