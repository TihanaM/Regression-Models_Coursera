###**Executive Summary**

The *Motor Trend* magazine is interested in exploring the relationship between a number of variables and miles per gallon (MPG) (outcome), for a number of different automobiles (1973-1974 models). The data is found in the source file `mtcars`, which was originally extracted from the 1974 edition of the *Motor Trend* US magazine. It is comprised of fuel consumption (MPG) and 10 aspects of automobile design and performance for 32 automobiles.

In particular, in this analysis, two questions are going to be addressed:

```
- "Is an automatic or manual transmission better for MPG"
- "Quantify the MPG difference between automatic and manual transmissions"
```
Hypothesis  testing and linear regression confirmed a statistical differences between the means of MPG values for cars with **automatic** (am = 0) and **manual** (am = 1) transmission, where cars with a manual transmission have scored 7.2 MPG higher than those with an automatic transmission. Multivariable regression analysis was then employed to analyze the impact of confounding variables, such as weight and qsec, on the dependence of the transmission type on MPG. The best model, with the highest R-squared value, indicates that in addition to qsec, it is primarily the weight parameter that has a significant impact when quantifying the MPG difference between cars with automatic and manual transmissions, as lighter cars, are mostly associated with a manual transmission, are also characterized with a higher MPG value.
