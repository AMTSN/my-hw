### ***Design Write-up Feedback***

***Nico Van de Bovenkamp***

***

***Project Plan:***  
This is a perfect approach to your problem! It is akin to a time series, type, regression, but you don't *have* to approach it in this way. We won't cover this in class, so what you can do is have a matrix, X, to be input into your model that includes an indicator of the data (ie. 1/2/1955 = 1 and all other dates columns = 0) and the stage of the retrograde (R = 1 and all others columns are 0) and then a y of the price (or range or standard deviation or any other metric of volatility) on that day. This can then be fed into a model.

***Adding other variables***  
When performing regression analysis, very often the goal is to infer or reject the importance of a variable/feature on an outcome. To demonstrate that a variable is not predictive, or indicative, of the outcome, what is often done is adding in other variables. In other words, say you find that there is some weak relationship in your model between the retrograde state and volatility. What happens if you then add an indicator for, as an odd example, political instability (ie. an indicator that on that day some news broke out that was some political issue in the world or the US). If that variable becomes significant, or better predicts the outcome of volatility, then you can demonstrate that there is no relationship, it's actually other things in the world! The process of finding those variables is tedious, and takes a bit of domain knowledge, but most economic indicators and other external factors should do. Let me know if this is clear!
