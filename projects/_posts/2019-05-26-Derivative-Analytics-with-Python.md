---
layout: post
title: "Derivative Analytics with Python"
description: All results are based on the above book by Yves Hilpisch
total_time: "5 min"
---

My current project is to brush up my knowledge of derivatives using python. For this, I will be reading two books – Derivatives Analytics with Python by Yves Hilpisch from Wiley Financial Series and the classic Options, Futures and Other Derivatives by John C. Hull.


I will be posting the results from exercises from the book on the blog. The code is available in the book and on [github](https://github.com/yhilpisch/dawp). At the end of it, I will also try to work on a project of my own using the concepts learned in the book. This should be fun!


Broadly, the scope of this book is to: 
* characterize a market model
* study a few theoretical market models and the calibrate them to market-determined prices
* understand how to value and hedge exotic products based on market models


Below are a few results from the textbook:


* Intrinsic Value of Call Option: The payoff of a call option at time 'T' having Strike price of $8000:
 

![alt text](https://github.com/meghanayerabati/meghanayerabati.github.io/raw/master/Projects/_posts/call_option_payoff.PNG "Call option intrinsic value")

* Time Value of Option

![alt text](https://github.com/meghanayerabati/meghanayerabati.github.io/raw/master/projects/_posts/call_option_time_value.PNG "Call option present value")

* Brownian Motion Model
![alt text](https://github.com/meghanayerabati/meghanayerabati.github.io/raw/master/projects/_posts/simulate%20gbm.PNG "Brownian Motion Model Simulation")
![alt text](https://github.com/meghanayerabati/meghanayerabati.github.io/raw/master/projects/_posts/log%20returns%20gbm.PNG "Log returns based on Brownian Motion Market Model")
![alt text](https://github.com/meghanayerabati/meghanayerabati.github.io/raw/master/projects/_posts/realized%20volatility%20gbm.PNG "Realized volatility for  a Brownian Motion Market Model")
![alt text](https://github.com/meghanayerabati/meghanayerabati.github.io/raw/master/projects/_posts/mean%20returns%20volatility%20gbm.PNG "Mean returns and volatility for Brownian Motion Market Model")
![alt text](https://github.com/meghanayerabati/meghanayerabati.github.io/raw/master/projects/_posts/qq%20plot%20gbm.PNG "Quantile-Quantile plot for Brownian Motion Model Returns")


* Comparison of theoretical model with market model
![alt text](https://github.com/meghanayerabati/meghanayerabati.github.io/raw/master/projects/_posts/DAX%20returns.PNG "Market Returns for DAX Index")
![alt text](https://github.com/meghanayerabati/meghanayerabati.github.io/raw/master/projects/_posts/log%20returns%20DAX.PNG "Log returns for DAX Index")
![alt text](https://github.com/meghanayerabati/meghanayerabati.github.io/raw/master/projects/_posts/realized%20volatility%20DAX.PNG "Realized volatility for DAX Index")
![alt text](https://github.com/meghanayerabati/meghanayerabati.github.io/raw/master/projects/_posts/mean%20returns%20volatility%20DAX.PNG "Mean returns and volatility for DAX Index")
![alt text](https://github.com/meghanayerabati/meghanayerabati.github.io/raw/master/projects/_posts/qq%20plot%20DAX.PNG "Quantile-Quantile plot for DAX Index")

* Implied Volatility based on Black Scholes Model 
//To be updated