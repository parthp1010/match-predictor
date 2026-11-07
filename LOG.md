# Learning log

## Day 1 (27.10.26)
Today, I just set up my GitHub Repository and Google Colab. I found football-data.co.uk which publishes the data of every Premier League match, and I loaded the 2025-2026 season with pandas. I also learnt to read a DataFrame and the columns of the CSV file downloaded.

## Day 2 (28.10.26)
Today, I started by learning about base rates, which are how often an outcome occurs before having any information about the specific match. I also practiced filtering rows with a few conditions, created new columns and grouped using groupby.

## Day 3 (29.10.26)
Today, I loaded 10 seasons from 2016-17 to 2025-26 and combined them into a single table of matches. I also converted the date into a format through which it can be sorted better. Additionally, I made a decision and only kept those parameters that were relevant to me for now and cleared the rest. I also saved everything to Google Drive as matches.csv.

## Day 4 (02.11.26)
Today, I compared the home goals scored to the Poisson formula and checked the prediction with a graph and found that it fitted the real data closely. I also, looked at the trends of results over the season and noticed that in 20-21 there were more away wins than home, which could be because there were no crowds due to Covid-19. The results trend helps look at the home advantage's effect on the result for every season.

## Day 5 (03.11.26)
Today, I learnt about the bookmaker's odds and their profit margins. I converted Bet365's odds into probabilities and removed the bookmaker's margin by dividing each one by their total. I also calibrated these values and divided them into categories according to whether the result was actually true and plotted this on a graph, after splitting them into bins.

## Day 6 (04.11.26)
Today, I learnt about what the different baselines could be for the prediction and that accuracy is not enough due to the magnitude of probabilites. Therefore, I learnt about logloss and how to calculate that and found that the bookmakers had the least since they had almost all information before making their pick.

## Day 7 (05.11.26)
Today, I just did some cleaning up with the notebook to make it more presentable, and published the Google Colab file to my GitHub repository.

## Day 8 (07.11.26)
Today, I learnt about features of prediction and how they are the things known before every match. I also tried to predict using shots on target but ran into a problem where the current data was also being used so I shifted everything down by 1 row. 

