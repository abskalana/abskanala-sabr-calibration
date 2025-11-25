# SABR Model Calibration Using Swaption Volatility in Python

This project implements the **SABR (Stochastic Alpha, Beta, Rho) model calibration** using market **swaption implied volatilities**. The goal is to reproduce the market volatility smile for interest rate derivatives by calibrating the SABR parameters α, ρ, and ν for a given β.

## Features

- Compute the **initial volatility parameter α** from ATM swaption volatility.  
- Calibrate **ρ and ν** to fit the full market volatility smile.  
- Supports **different expiries and tenors** of swaptions.  
- Implemented in **Python** using `numpy` and `scipy.optimize`.  
- Robust cubic inversion with positive root selection for α.
