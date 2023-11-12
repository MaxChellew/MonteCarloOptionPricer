# Monte Carlo Option Pricer

This project was a self-set project that looked into the implementation of a Monte Carlo simulation to price exotic options. The theoretical basis behind this program was to use Brownian motion to simulate the change in the underlying stock's price over time. Then multiple simulations of the stocks price could be mapped and the payoffs of an option could be calculated for each simulation. The payoffs for each simulation could then be averaged and discounted to give the value of the option at time zero. Please find the C++ file in the repository to explore the exotic option pricer program.

## Table of contents
* [Objective](##objective)
* [Key Takeaways](#key_takeaways)
* [Reflection](#reflection)

## Objectives
Following is a list of objectives for this project:
- Perform a monte-carlo simulation of a stock price
- Calculate the Payoff for different types of options (Put or Call)
- Calculate the payoff for different styles of options 
- Calculate the average of the payoff's of the option for each stock price simulation
- Discount the average payoff to give value of option at time zero
- Option check list: Put & Call options, American & European options and Non-exotic, Asian & barrier Options
- Implement a UI into the program
	
## Key Takeaways
Following is a list of the knowledge I acquired from completing this project:
- Coding in C++
- Peforming Monte Carlo simulation
- Calculating discount factors
- finding payoff function for Non-exotic european put & call options
- finding payoff fucntion for Non-exotic american put & call options
- finding payoff function for asian european put & call options
- finding payoff function for asian american put & call options
- finding payoff function for barrier european put & call options
- findin payoff function for barrier american put & call options

## Reflection
Following is a list of the constructive cristism i would give my self for this project to improve:
- To implement sing Points
- To perform testing of convergence for different N and n values
