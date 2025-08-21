## Overview
During the Vietnam War, a lottery based on birth dates was conducted by the U.S. Selective Service System on December 1, 1969, to determine the draft order for men born between January 1, 1944, and December 31, 1950. *This repository analyses the likelihood of someone being selected based on their birthday.*

<br>

Interactive Tableau Dashboard: [Vietnam War Birthday Lotteries](https://public.tableau.com/app/profile/fermin.ramos/viz/VietnamWarBirthdayLotteries/Dashboard1)

<br>

## The Vietnam Lotteries
***The United States conducted seven draft lotteries for the Vietnam War between 1969 and 1975:***
### Drafted
* December 1, 1969 – For men born between 1944 and 1950 (the first and most widely known lottery)(leap-year).
* July 1, 1970 – For men born in 1951.
* August 5, 1971 – For men born in 1952 (leap-year).
* February 2, 1972 – For men born in 1953.

### Precautionary lotteries (in case they needed to draft)
* February 5, 1973 – For men born in 1954.
* March 20, 1974 – For men born in 1955.
* March 20, 1975 – For men born in 1956 (leap-year).

RAW Data from the Selected Service Website: [https://www.sss.gov/history-and-records/vietnam-lotteries](https://www.sss.gov/history-and-records/vietnam-lotteries/)


<br>

## Understanding the Data
A “hit” is when a date has “drafted” as “Y”. Every day is randomly marked with a number 1-365. If a draft is needed, the government would select the date with the number 1, then the date with the number 2, and so on. Not all dates were selected for the draft. The highest number called each year is the APN. These are the highest APN’s called for each year:

Table 1970 = 195

Table 1971 = 125

Table 1972 = 95

Table 1973 = 95


<br>

## The Best Month to have been born in is March.
![Monthly Draft Hit Ratios by Dataset](https://github.com/FerminRamos/Vietnam-Birthday-Lottery/blob/main/Graphics/Monthly%20Draft%20Hit%20Ratios%20by%20Dataset.png)

March has a hit rate of only `27.4%`, with it's lowest hit rate coming from the 1972 lottery, featuring the second lowest draft rate of only `9.7%`.

## The Worst Month to have been born in is December.
![Monthly Draft Hit Ratios by Dataset](https://github.com/FerminRamos/Vietnam-Birthday-Lottery/blob/main/Graphics/Monthly%20Draft%20Hit%20Ratios%20by%20Dataset.png)

December has a hit rate of `43.5%`, with it's highest hit rate coming from the 1970 lottery, featuring the highest draft rate of `83.9%`.

## Smaller Months Had a Slight Edge Over Larger Months.
![Avg Draft Prob by Month Size](https://github.com/FerminRamos/Vietnam-Birthday-Lottery/blob/main/Graphics/Avg%20Draft%20Prob%20by%20Month%20Size.png)

Contrary to popular belief, smaller months actually performed better than larger months. Smaller months averaged `1.42%` lower draft rates compared to their counter-parts.

## Full Graphic
![Hits and Misses Complete](https://github.com/FerminRamos/Vietnam-Birthday-Lottery/blob/main/Graphics/Hits%20and%20Misses%20Complete.png)
