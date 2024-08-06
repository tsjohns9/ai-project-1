# Congress Stock Trades Analysis

## Overview

Pull CSV data from quiverquant for trades of congress members to analyze and predict future trends.

The goal the analysis was to identify patterns in excess returns within the years of 2019-2021. The trades are analyzed from multiple perspectives.
* Analyze the overall volume of trades for the top 3 most traded representatives from each party.
* Identify the most commonly traded companies from 2019-2021 for the top trading representatives.
* Identify the average excess return from 2019-2021 for each top trading representative.
* Identify the party with the highest excess return from 2019-2021 based on the top performing representatives.
* Find the top 3 performing representatives with the highest excess return from each party for all years, and predict future returns.
* Find the top performing politician overall for all years and predict future returns.
* Figure out if it is worth making investments based on the performance of a given politician, or a given party.
* Identify the top traded healthcare stock from 2019-2021.
* Identify if it is worth making investments into healthcare stock based on political party.

## Getting Started

Open the project and run the command below

```bash
jupyter notebook
```

Then, run the cells to install the dependencies and see the output for the work.

## Analysis

**Top Traders** *Shayne*

Filtering the data to fit specific needs, this  portion of the data focuses mainly on the top 6 politicians
that made the most trades overall. These traders happened to be:
* Josh Gottheimer (D)
* Lois Frankel (D)
* Susie Lee (D)
* Thomas Macarthur (R)
* David Perdue (R)
* Greg Gianforte (R)

With the knowledge of who the top 6 politician traders were, I filtered the data to only depict the
trade information within the time-span of 2019-2021. Once this content was filtered I 
identified which Company was traded with the most for each of the politicians. I took this
a step further by calculating the average excess return for each of these companies.
* JG-- Microsoft Corporation-- 156 total trades
* LF-- Dupont De Nemoours, Inc.-- 10 total trades
* SL-- Ball Corporation-- 21 total trades

![alt text](images/2A.png)

* TM-- Interactive Brokers Group Inc.-- 1 total trade
* DP-- Caesars Entertainment Corporation-- 33 total trades
* GG-- AMN Healthcare Services Inc.-- 15 total trades

![alt text](images/1A.png)

When first determining the top companies traded within the filtered time span, I was surprised
that only one of the politicians really invested in a Healthcare service the most. Though the 
average excess returns for said healthcare incorporation explains why. Greg's trades with
AMN Healthcare Services Inc. accrued him an excess return average of -48.22 when I expected
the excess return in this timeframe to be positive.

Furthering this information, I had expected at least 2/3rds of the politicians for each party
to have a positive average excess rate for their top traded company, however, that was only true 
for the top 3 republicans.

![alt text](images/1B.png)

COMPARED TO

![alt text](images/2B.png)

These results may appear shocking... though what shocked me the most was when I found the
average excess returns overall for the top 6 traders. It was a lot more negative than 
one would expect.

![alt text](images/3A.png)
![alt text](images/4A.png)

Only Thomas Macarthur from the Republican party and Josh Gottheimer of the Democratic party
resulted with positive excess return averages, though, due to an oversight made when originally gathering the
data, Thomas Macarthur only had a positive excess return average out of circumstance as he was only in office
for one trade during 2019.

![alt text](images/3B.png)
![alt text](<images/Screen Shot 2024-08-02 at 11.27.45 AM.png>)

When push comes to shove, during the years of 2019-2021, excess return averages were 3/5ths negative. So it is
safe for one to assume that investing in certain companies or trades in general during the prior mentioned years
was clearly not the best idea, and the Democratic Party's results provide proof for that assumption in my collection
of top traders.
