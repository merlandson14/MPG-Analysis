# MPG-Analysis
basic model analysis on the mtcars dataset in R

Using the base R dataset, `mtcars`, we were looking at fitted linear models for predicting MPG, focusing in on variable `am` for automatic or manual transmission. We checked it against other possible variables, `cyl`, `disp`, `gears`, `hp`, `wt`, and `carb`.

As you can see from the results of investigation, `cyl` and `disp` are the biggest regressors besides `am`, but the overall p-values are not conclusive and the model has some internal shortcomings, as seen in the residual plots and global stat model fit evaluation.
