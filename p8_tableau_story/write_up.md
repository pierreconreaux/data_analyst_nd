# Baseball Batting & HR performance
by Pierre Conreaux 

## Introduction

Using a data set containing 1,157 players we create a visualization of the best players performance.

***First Visualization:*** https://public.tableau.com/profile/conreaux#!/vizhome/BaseballBattingHRperformance/BaseballBattingHRperformance
***Second Visualization:*** https://public.tableau.com/profile/conreaux#!/vizhome/BaseballBattingHRperformancefinal/BaseballBattingHRperformance
## Summary

First, we create and plot categories of players (excellent, good, average, poor).

Then, we make two ranking, the 20 best HR players and the 20 best batting average players.

After that we try to understand if one of our variables has an impact on performance (weight, height,handedness).

Finaly, we propose a table to select players and compare them in a scatterplot batting average and HR in axis.
People can choose a group of players and compare their performance.

## Design

***0. Global***

We created a new dimension to represent categories, following these principles:
- A player is considered excellent if he has a better batting average than 50% of the other players and a better HR than 50% of the other players. 
- A player is considered poor if he has a worst batting average than 50% of the other players and a worst HR than 50% of the others. 
- A player is considered good if he has a  better batting average than 50% of the other players and a worst HR than 50% of the others. 
- A player is considered average if he has a worst batting average and a better HR.

We also created Heigt (bin) and Weight (bin) to be able to plot readable bar charts.


***1. Player categories***

We choosed to plot each player in a cloud of dots with HR and batting average in axis.

To clarify the categories we made two actions:
- give each categories a specific color
- add batting average median and hr median, so the quadrant is split in four.

After feedback, we corrected the filter to represent all players.

***2. TOP 20 HR players***

We represented in a bar chart the best 20 HR players by order.

***3. TOP 20 batting average players***

We represented in a bar chart the best 20 batting average players by order.

After feedback, we add a short note to explain why you can count 22 players (the last 3 have the same batting average).

***4. Impact of height and weight***

We represented four relations:
- HR median by height
- HR median by weight
- Batting average by height
- Batting average by weight

We chosen to represent graph on batting average and HR so we can compare them directly.

After feedback, we added text to decribes bar charts and explained limits.

***5. Impact of handedness***

We represented two bar charts:
- HR median by handedness.
- Batting average by handedness.

***6. Compare your players***

Compare your players is basically the same graph that player categories but we added a filter, so everybody can compare its players.


## Feedback

This a summary of the feedbacks of 4 people.


***1. Player categories***

Feedback: seems to miss some data.

Analysis: 'player categories' and 'compare your player' are interconnected.

Action: create of a new sheet to disconnect 'player categories' and 'compare your player'.

***2. TOP 20 HR players***

No action required.

***3. TOP 20 batting average players***

Feedback: 22 names

Action: explain why we have 22 names with a short text (the last 3 players have the same rating)

***4. Impact of height and weight***

Feedback: what is the conclusion?

Action: add a short text

***5. Impact of handedness***

Feedback: what is the conclusion?

Action: add a short text

***6. Compare your players***

Feedback: 
- we do not understand how it works
- why do not add more date in the bubble info.

Action:
- create a short introduction
- add all relevant information in the bubble info.

## Ressources

Udacity Data Story Telling in Udacity Data Analyst Nanodegree
