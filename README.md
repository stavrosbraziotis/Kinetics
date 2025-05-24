# Estimation of reaction rate parameters
This program was an assignment of my elective course 'Programing Languages'. The objective was to estimate the constant k and the order of reaction n, based on given data (concentration - time). It was extended so that the user can add his own data either manually or by uploading a csv file.

For the estimation, an irreversible reaction A -> B + ... was considered that was following the empirical law: r = k⋅c<sub>A</sub><sup>n</sup>. Initially the equation was solved analytically for n = 1 and n ≠ 1. Then, the variables for which in each case linear regression was formed were isolated, so that the parameters with the best fit can be calculated based on that linear model.
