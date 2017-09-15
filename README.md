# Amex-Analyize-this-2017
## Data science challenge

 * #### Team Name: Data_Targaryens
 * #### Team Members: Harsh Singhal | Gaurav Jindal
 * #### Achievement: 3rd Rank
 * #### Public LB Score: 44300

## Problem Statement:

In this challenge, we have to predict the top 1000 potential customer ids which are more likely to accept the card offered by the company and predict which card should be offered to whom.

The main operational expense for the bank is each call made to customers. One call increases expense by $6. On each call the bank advises only one card offer: Elite card, Supplementary card or Credit Card.

With a budget of $6,000, you can maximize the bank’s profit by suggesting calls to the right customers and extending the right offers. If the bank advises the wrong offer to a customer who ends up inquiring and then still accepting an alternate card offer, it costs $12 for the call since double the time is spent in explaining the two offers. 

Your leader board submission will be evaluated as:
1. You start with a budget of $6000. 
2. Each call will reduce the remaining budget by $6 or $12 as explained below. 
3. Evaluation will be done in the order of your submission file. 
4. Evaluation will stop once the budget runs out.
5. For every call advised the scoring logic is:
a. If you advise the correct offer to a customer, it costs $6 for the call and the score for that call will be 100.
b. If you advise a call to a customer who is not interested in any one of the offers, it costs $6 for the call and the score for the call will be 0.
c. If you advise the wrong offer to a customer who ends up accepting an alternate card offer, it costs $12 for the call and the score for the call will be 100.



Few points to note:
As the budget is $6,000, you can make a maximum of 1000 calls. 
The order of the cm_keys is critical as that is the order in which the evaluation will occur.
The submission will be scored in the order of list provided by you and will stop at the point where you will be left with no budget and the score at that point will be the leaderboard score for that submission.
