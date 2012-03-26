# MATLAB FS12 – Research Plan (Template)
(text between brackets to be removed)

> * Group Name: V For Venture Capital 
> * Group participants names: Kevin Najjar, Felix Renaut, Maximilian Taillandier
> * Project Title: Simulation & Comparison of Investment Strategies in Venture Capital Industry 

## General Introduction

Start-ups are a great way of creating new jobs and reshaping a land’s economy. Only at ETH Zürich,
237 start-ups have been founded since 1996 ! The problem is that these start-ups often need a starting capital,
which can’t always be provided by a university, as it is the case here. Another option therefore is the use of
venture capital investors, who are specialized in financing start-ups. The aim of those investors is to choose
the right companies, i.e. the ones that will succeed. 
For this, they are using different methods based on their estimation of the success probability of a start-up. 

## The Model

The aim is to model different ways of investing in start-ups as it is done in venture capital investments. We would therefore implement a start-up randomizer which creates start-ups with a certain amount of money needed and a certain probability of fulfilling its aims (which would mean a gain of money for the investor). Different venture capital investors would invest on these start-ups with their own methods : one would base its choices only on experience of previous investments, others  using different fractions of the criterion described by Kelly in his article.
In a second step, we could add noise representing the judgment errors of the investors about the chances of a certain start-up’s success, and see how each model reacts to these errors, which model is safer, and if you can obtain similar results only with your experience than you would using the Kelly criterion.


## Fundamental Questions

The goal of our simulation is to differentiate the ways for a venture capital investor to make money. Therefore our fundamental questions would be, which of the two models described previously leads to better results, and if there is none (or slightly similar), it is of any interest for the investor to couple the two methods in order to optimize its earnings? Given some (realistic) initial conditions described in the upper paragraph, how is our simulation going to react after adding an additional "noise information" (in our case, a misinformation that includes a variation, either positively or negatively of the needer’s success probability)? The last point that arises from the last idea is the importance of this "noise information": we will try to simulate the moment at which the noise becomes either to big and induces a big loss for the investor or the opposite.


## Expected Results

-  if our start-up randomizer has some tangible initial parameters, the model using the Kelly criterion should lead us (for a time t->∞) to a maximum benefit for the investor
-	Compare/judge our results and see which model is better/safer 


## References 

- Medium Term Simulations of The Full Kelly and Fractional Kelly Investment Strategies, Leonard C. MacLean, Edward O. Thorp, Yonggan Zhao and William T. Ziemba
- A New Interpretation of  Information Rate, by J.L. Kelly  
- The Kelly Criterion in Blackjack, Sports Betting, and the Stock Market, by Edward O. Thorp
- Calculating A Start-Up’s Odds Of Success, by Scott Austin in WSJ’s Venture Capital Blog




## Research Methods

(Cellular Automata, Agent-Based Model, Continuous Modeling...) (If you are not sure here: 1. Consult your colleagues, 2. ask the teachers, 3. remember that you can change it afterwards)


## Other

(mention datasets you are going to use)
