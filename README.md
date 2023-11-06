# Fifa23-AC-Milan
Scenario: We are running the player management for the club AC Milan, and we want to see how well we pay our players and if there's any salary change that needs to be made.

Goals: 
1. We want to see how well our players are being paid;
2. We want to understand the global salary status for players;
3. We would like to see if we can identify some overpaid players and if it is better to make some transfers to maximize our outcome

Process:
1. We check the null data, and remove all the duplicates.
2. We want to generate a model to predict Wage(in Euro)
3. We need to compare the predicted wage made by the model to see of we overpaid our players
4. We want to have a general idea of how we want to decide if we want to transfer the players in our club.
5. We first need to see what are having high correlation with Wage(in Euro)
6 We take into consideration of the factors that might be correlated and better not to be included in the predictors to avoid multicollinearity
7. We split the dataset into training data(the rest) and test data(AC Milan)
8. The independent variables are standardized
9. We test some models to determine which model fits better
10. We use the model to predict our players' Wage and compare it to the current wage.
11. We check the number of players being good at certain positons(generalized into 4 positions) to see if there are some players with less overall/potential values and high wage.
12. We filter the players globally to find potential players that are good at this position and less or even no release clause

   
