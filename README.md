# How to Use Survival to Predict Churn (in R)

#### by Pasha Roberts ~ Chief Scientist, Talent Analytics

## Context
Demo code supporting various presentations and classes about Prediction with Survival Analytics.

## The Slides

The slides are now online in this repository.
The easiest way to view them is to look at the PDF: [slides/survival_101.pdf](slides/survival_101.pdf).

They are actually HTML slides produced with [remark](https://github.com/gnab/remark) - if you clone this repository and open [slides/survival_101.html](slides/survival_101.html) in a browser, then you'll see a nice powerpoint-like presentation in your browser.
Type "?" to get the list of commands that you can use while walking through the slides.
Much better than powerpoint if you are comfortable with text.

## The Code
The code is in [code/survival101.R](code/survival101.R).
The functions include:

- `demoETL()` walks through the conversion of raw HR data into a data frame usable for survival analytics.
- `demoPrediction()` walks through creating a survival curve, predicting a proportional hazard model, and validating the model.
- `genAttritionData()` generates a random attrition dataset.
- `genRandomSpans()` generates random employment spans.
- `survFitData()` transforms a `survival::survfit` object into a usable R `data.frame`.
- `plotSurvFit()` makes a `ggplot2` plot of a survival curve
- `plotSurvAUC()` makes a `ggplot2` plot of an AUC curve
