# Quant-Finance-Codebook

This repository serves as a codebook for various quantitative finance models and algorithms implemented in Python. It contains implementations of the Markowitz portfolio optimization model and the Black-Scholes-Merton option pricing model. The implementations are optimized using gradient descent, Particle Swarm Optimization (PSO), and Monte Carlo simulations.

## Contents

1. [Markowitz Portfolio Optimization](#markowitz-portfolio-optimization)
2. [Black-Scholes-Merton Option Pricing](#black-scholes-merton-option-pricing)
3. [Usage](#usage)
4. [Installation](#installation)


## Markowitz Portfolio Optimization

The Markowitz model is used to optimize a portfolio of assets to achieve a desired return with minimum risk. This implementation includes functions to calculate the optimal weights for a given set of assets, considering their expected returns and covariance matrix.

Optimization techniques used:
- Gradient Descent
- Particle Swarm Optimization (PSO)
  
![alt text](/images/mkwtz.png)

## Black-Scholes-Merton Option Pricing

The Black-Scholes-Merton model is used to price European options. This implementation includes functions to calculate the price of a European call or put option using Monte Carlo simulations.

![alt text](/images/bsm.png)

## Usage

To use the functions in this repository, clone the repository to your local machine and import the relevant modules into your Python scripts. You can then use the provided functions to perform portfolio optimization or option pricing in your own projects.

## Installation

To install the required dependencies, run:

```bash
pip install -r requirements.txt
