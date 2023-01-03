# R Workshop
Dataset  associated with Rworkshop assignment 2
Fertility and Women's Labor Supply
Description
Cross-section data from the 1980 US Census on married women aged 21–35 with two or more children.

Usage
data("Fertility")
data("Fertility2")
Format
A data frame containing 254,654 (and 30,000, respectively) observations on 8 variables.

morekids
factor. Does the mother have more than 2 children?

gender1
factor indicating gender of first child.

gender2
factor indicating gender of second child.

age
age of mother at census.

afam
factor. Is the mother African-American?

hispanic
factor. Is the mother Hispanic?

other
factor. Is the mother's ethnicity neither African-American nor Hispanic, nor Caucasian? (see below)

work
number of weeks in which the mother worked in 1979.

Details
Fertility2 is a random subset of Fertility with 30,000 observations.

There are conflicts in the ethnicity coding (see also examples). Hence, it was not possible to create a single factor and the original three indicator variables have been retained.

Not all variables from Angrist and Evans (1998) have been included.

Source
Online complements to Stock and Watson (2007).

References
Angrist, J.D., and Evans, W.N. (1998). Children and Their Parents' Labor Supply: Evidence from Exogenous Variation in Family Size American Economic Review, 88, 450–477.

Stock, J.H. and Watson, M.W. (2007). Introduction to Econometrics, 2nd ed. Boston: Addison Wesley.
