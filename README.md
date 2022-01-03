## Variable selection for regression using Mixed Integer Quadratic Programming

One of the most common problems in predictive analytics is variable selection for regression. Direct variable selection using optimization has long been dismissed by the statistics/analytics community because of computational difficulties.  This computational issue was part of the motivation for the development of LASSO and ridge regression.  However, in the recent past there have been tremendous advancements in optimization software, specifically the ability to 
solve mixed integer quadratic programs (MIQP).  This project will pose the variable selection problem for regression as an MIQP which we will solve using gurobi.  We will compare the results to LASSO to see if the additional ‘shrinkage’ component of LASSO really is more beneficial than finding the ‘best’ set of variables to include in the regression. 

