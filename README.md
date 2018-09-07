# Statistical Simulation

This is to provide some references on simulation in statistical modeling and methods research.

# Books & Educational Materials

[SAS and R: Data Management, Statistical Analysis, and Graphics](https://nhorton.people.amherst.edu/sasr2/) by Ken Kleinman and Nicholas J. Horton

- Chapter 10 in 2nd edition 2014; [link (behind paywall/works on OHSU campus)](https://www.taylorfrancis.com/books/9781466584501); [chapter preview](https://nhorton.people.amherst.edu/sasr2/simulation_generation.pdf)
- Chapter 6 in 1st edition 2009, simulation-based power calculations, generate data from generalized linear effects model, generate correlated binary data, missing data multiple imputation: [link (behind paywall/works on OHSU campus)](https://www.taylorfrancis.com/books/9781420070590)

Givens, G. H. and Hoeting, J. A. (2013). Simulation and Monte Carlo Integration. In Computational Statistics (eds G. H. Givens and J. A. Hoeting). doi:10.1002/9781118555552.ch6 

- [book](https://onlinelibrary.wiley.com/doi/book/10.1002/9781118555552); [chapter 6 link](https://onlinelibrary.wiley.com/doi/10.1002/9781118555552.ch6#)
- introduces Monte Carlo methods

## Other references

W. J. Braun and D. J. Murdoch, A First Course in Statistical Programming with R. Cambridge: Cambridge University Press, 2007.

M. L. Rizzo.Statistical Computing with R.  CRC Press, Boca Raton, FL, 2007.

O. Jones, R. Maillardet, and A. Robinson, Introduction to Scientific Programming and Simulation Using R. Boca Raton: Chapman and Hall, 2009. [pdf](http://www.tf.uns.ac.rs/~omorr/radovan_omorjan_003_prII/r-examples/spuRs/spuRs-2ed.pdf) - Chapter 20: Simulation

Gentle, J. E. (2013). Random number generation and Monte Carlo methods. Springer Science & Business Media. [google books](https://books.google.com/books?id=MYnqBwAAQBAJ&lpg=PA1&ots=UjTeYvjOft&dq=Random%20Number%20Generation%20and%20Monte%20Carlo%20Methods&lr&pg=PA1#v=onepage&q&f=false)

[Slides by C. Robert and G. Casella on Monte Carlo methods with R.](https://www.researchgate.net/publication/41222435_Monte_Carlo_Statistical_Method), related to their book [Monte Carlo Statistical Methods](https://www.springer.com/us/book/9780387212395)



# Practical Examples

## Very useful blog posts by [Ariel Muldoon](https://twitter.com/aosmith16) - Simulation in R

[Getting started simulating data in R: some helpful functions and how to use them](https://aosmith.rbind.io/2018/08/29/getting-started-simulating-data/)



- [full PDF version](https://github.com/aosmith16/simulation-helper-functions/blob/master/functions_for_simulations_detailed.pdf)
- discussion on random number generation
- overview of many useful functions for simulating data
- simulating character/string data
- simulate differences between/among groups

[Simulate! Simulate! Part 1: A linear model](https://aosmith.rbind.io/2018/01/09/simulate-simulate-part1/)

- Simulation from a linear model
- Using `tidyverse` and `broom` to extract results from simulations
- Estimating standard deviation from simulations

[Simulate! Simulate! Part 2: A linear mixed model](https://aosmith.rbind.io/2018/04/23/simulate-simulate-part-2/)

- Simulation from a linear mixed model

[Simulate! Simulate! Part3: The Poisson edition](https://aosmith.rbind.io/2018/07/18/simulate-poisson-edition/)

- Simulation from Poisson regression

[Using DHARMa for residual checks of unsupported models](https://aosmith.rbind.io/2017/12/21/using-dharma-for-residual-checks-of-unsupported-models/)

- Using simulations for model checking, examples of simulating from zero-inflated negative binomial model

[A closer look at replicate() and purrr::map() for simulations](https://aosmith.rbind.io/2018/06/05/a-closer-look-at-replicate-and-purrr/)

- deep dive on `replicate()` and `map()` methods for simulation

## UCLA Simulation Code Examples - STATA & R

[RUNNING A SIMULATION | STATA CODE FRAGMENTS](https://stats.idre.ucla.edu/stata/code/running-a-simulation/)

[MONTE CARLO POWER SIMULATION OF A MULTILEVEL MODEL | STATA FAQ](https://stats.idre.ucla.edu/stata/faq/monte-carlo-power-simulation-of-a-multilevel-model/)

[MONTE CARLO SIMULATION FOR FACTORIAL ANOVA | STATA FAQ](https://stats.idre.ucla.edu/stata/faq/monte-carlo-simulation-for-factorial-anova/)

[R ADVANCED: SIMULATING THE HOSPITAL DOCTOR PATIENT DATASET | R CODE FRAGMENTS](https://stats.idre.ucla.edu/r/codefragments/mesimulation/)

- Useful simulation example of complex data with multiple predictors and a three-level hierarchical structure
