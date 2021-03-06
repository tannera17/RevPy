# RevPy

[![Build Status](https://travis-ci.org/flix-tech/RevPy.svg?branch=master)](https://travis-ci.org/flix-tech/RevPy)

Collection of some revenue management tools for Python 3. 

## Features

- Single leg optimizer (EMSRb)
- Fare transformation for unrestricted fare structures
- EMSRb for unrestricted fare structures (EMSRb-MR)
- A multi-flight recapture method (MFRM) for estimating unconstrained demand from sales transaction data
- Linear programming (LP) solver for calculating static bid prices and partitioned allocations

## TODO
 - Implement dynamic programming (DP) optimizer to model time-dependent arrival rates
 - Implement network heuristics (DAVN, DP-LP decomposition)
 - Integrate customer choice model into optimizers
 

## Literature
1. Talluri and van Ryzin: "The Theory and Practice of Revenue Management", _Springer_ (2004)
2. Fiig et al.: "Optimization of mixed fare structures: Theory and applications", _Journal of Revenue and Pricing Management_ (2010)
3. Ratliff et al.: "A multi-flight recapture heuristic for estimating unconstrained demand from airline bookings", _Journal of Revenue and Pricing Management_ (2008)


