# Pricing-European-Option-and-Greeks (Python)
Pricing European options and Greeks
This is simple explanation for calculating the price of an European call option for a non dividend paying stock using both Black-Scholes Merton and Monte Carlo Simulation method. The payoff of the call option is 𝑪 = 𝐦𝐚𝐱{𝑺 − 𝑲, 𝟎} where 𝑺 is the stock price at the end of Time.

Assuming continuous frequency (= daily simulation). Assuming the following model parameters: 𝑆0 = 100 , 𝑟 = 5%, 𝑇 = 1 𝑦𝑒𝑎𝑟, 𝐾 = 100, 𝜎 = 20%. Greeks are also computed using both Black-Scholes Merton and Monte Carlo Simulation method

Theory for generating Monte Carlo Paths - Stock Prices are assumed to follow Geometric Brownian Motion (GBM). Research the Internet or John C Hull's book on Derivatives for more

Theory for generating Black - Scholes Merton Price - It is a closed form solution. Research the Internet John C Hull's book on Derivatives for more
