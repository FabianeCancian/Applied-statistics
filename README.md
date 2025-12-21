# Applied Statistics 

### Overview

This repository contains solutions for the Applied Statistics assessment, inspired by the course materials from Ian McLoughlin’s Applied Statistics series. It includes simulations, analyses, and visualizations for problems involving normal distributions, t-tests, combinatorial probability experiments, and ANOVA, such as the Lady Tasting Tea experiment.

The repository demonstrates:
- Monte Carlo simulations
- Exact combinatorial calculations
- Comparisons between simulation and theoretical probabilities
- Visualizations with Matplotlib

*******

### Key Experiments

1. Lady Tasting Tea
- Original 8-cup experiment and extended 12-cup design
- Monte Carlo simulation of random guessing
- Exact combinatorial probability calculation
- Comparison plot of simulated vs exact probabilities
- Discussion of implications for significance testing

2. t-Tests
- Simulation of Type II error rates for varying mean differences
- Comparison between Student t-test and Welch t-test
- Power calculations as a function of sample size and variance

3. Normal Distribution Exploration
- Sampling from the standard normal distribution
- Calculation of sample (ddof=1) and population (ddof=0) standard deviations
- Visualization of distribution and Q-Q plots
- Effect of increasing sample size on SD estimates

4. ANOVA 
- Generation of three independent samples from normal distributions
- One-way ANOVA to test equality of means
- Three independent two-sample t-tests for pairwise comparisons
- Comparison of conclusions between ANOVA and t-tests
- Discussion of why ANOVA is preferred over multiple t-tests

*****

### Requirements

The notebooks are implemented in Python 3. The following libraries are required:

- numpy
- scipy
- matplotlib
- itertools
- random
- pandas
- statsmodels

You can install missing packages using pip:
pip install numpy scipy matplotlib pandas statsmodels

****

### Usage

git clone https://github.com/FabianeCancian/Applied-statistics
cd repository Applied-statistics
jupyter notebook

Run each notebook sequentially.

****

### References

- [Code Base](https://github.com/ianmcloughlin/applied-statistics/blob/main/materials/lady-tasting-tea.ipynb)
- [Random](https://docs.python.org/3/library/random.html#random.sample)
- [Sets](https://docs.python.org/3/tutorial/datastructures.html#sets)
- [Base Code](https://github.com/ianmcloughlin/applied-statistics/blob/main/materials/normal-distribution.ipynb)
- [Numpy.std](https://numpy.org/doc/stable/reference/generated/numpy.std.html)
- [Numpy Random Normal](https://numpy.org/doc/stable/reference/random/generated/numpy.random.normal.html)
- [ddof](https://stackoverflow.com/questions/27600207/why-does-numpy-std-give-a-different-result-to-matlab-std)
- [T-tests code example](https://github.com/ianmcloughlin/applied-statistics/blob/main/materials/t-tests.ipynb)
- [Student vs Welsh t-test](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html)
- [Power Curve](https://matplotlib.org/stable/tutorials/pyplot.html)
- [Anova Statistics](https://statistics.laerd.com/spss-tutorials/one-way-anova-using-spss-statistics.php)
- [Base Code](https://github.com/ianmcloughlin/applied-statistics/blob/main/materials/anova.ipynb)
- [Anova Stasmodel](https://www.geeksforgeeks.org/data-analysis/how-to-obtain-anova-table-with-statsmodels/)
- [Anova Stasmodel Code Example](https://thequackdaddy.github.io/statsmodels.github.io/stable/generated/statsmodels.stats.anova.anova_lm.html)
- [Anova Stasmodel](https://www.statsmodels.org/dev/anova.html)
- [Generative AI - Used to code fix and gramamr check](https://chatgpt.com/)