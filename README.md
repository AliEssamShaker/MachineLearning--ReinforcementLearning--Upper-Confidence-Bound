# MachineLearning--ReinforcementLearning--Upper-Confidence-Bound

A little project where I apply Upper confidence Bound algorithm on a dataset of 10 different advirtisements(the rows) and 10,000 online users (the columns). The goal is to know which of the advertisements is the most successful and attracted users the most. 

This is a hypothetical scenario where we have a car company that wants to determine which advertising will be the most successful by showing each
advertising online to an equal amount of users and if the user clicks on the advertising then the result will be recorded as 1, otherwise, it will be recorded as 0.

Here is how the Upper Confidence Bound algorithm work:


At each user n, we consider two numbers for each ad i.

N  -  the number of times the ad I was selected up to the user n
R   -  the sum of rewards of the ad i up to the user n

Then we compute the average reward of ad I yp to the user n:
Average_reward = R/N 

Then we would compute the confidence interval by taking the square root of ( 3log(n) / 2N )



