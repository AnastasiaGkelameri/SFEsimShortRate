# ------------------------------------------------------------------------------
# Book:         SFE - Statistics of Financial Markets
# ------------------------------------------------------------------------------
# Quantlet:     SFEsimShortRate
# ------------------------------------------------------------------------------
# Description:  Simulation and plots of different One Factor Short Rate Models. 
#               Used Models: Vasicek, Cox-Ingersoll-Ross, Hull-White, Ho-Lee
# ------------------------------------------------------------------------------
# Inputs:       T     - Time Period
#               dt    - length of each time interval 
#               a     - reversion rate
#               b     - long term level
#               sigma - volatility
#				        delta - deterministic function of time
#				        r[1]  - initial short-rate value
# ------------------------------------------------------------------------------
# Output:       Plots of the Instantaneous Short Rate 
#               simulated by different Short Rate Models 
# ------------------------------------------------------------------------------
# Keywords:     simulation, interest-rate, short-rate, wiener-process, vasicek, 
#               hull-white, cox-ingersoll-ross, ho-lee,
# ------------------------------------------------------------------------------
# See also:     SFEsimOU, SFEsimCIR, SFEsimGBM, SFEWienerProcess, SFEustb
# ------------------------------------------------------------------------------
# Author:       Anastasia Gkelameri, Nils Hinrichs  2015/12/14
# ------------------------------------------------------------------------------
