# A-B-Testing-Free-Trial-Screener-

<p align="center">
  <img weight=500 height=300 src="https://user-images.githubusercontent.com/49653689/97252477-646e5e80-17e0-11eb-9d72-e7ed3bd39bea.png">
</p>

#### -- Project Status: [Completed]

## Project Objective
The purpose of this project is to 

### Methods Used

* A/B Testing


### Technologies
* Jupyter, Python 3

## Project Description

### Data Source

[Udacity: A/B Testing](https://docs.google.com/document/u/1/d/1aCquhIqsUApgsxQ8-SQBAigFDcfWVVohLEXcV6jWbdI/pub?embedded=True)

### Metric Choice

-   Invariant metrics (expected to be unchanged in the control and experimental groups):

1. Number of cookies 
2. Number of clicks 
3. Click-through probability (CTP).

-   Evaluation metrics (expected to be different in the control and experimental groups):

1. Gross conversion 
2. Retention 
3. Net conversion 

### Sizing 

### Sanity Checks

Cookies: p̂ = 0.5001759250544788 ∈ (0.4988207611357565, 0.5011792388642435) ✓
Clicks: p̂ = 0.5022473692559886 ∈ (0.4958855839921207, 0.5041144160078793) ✓
CTP: p̂ = 0.0006806446729920174 ∈ (-0.0012952158606468556, 0.0012952158606468556) ✓

### Result Analysis

Gross Conversion:

0 ∉ (0.015082871873568143, 0.032157223376795344)
(-0.01, 0, 0.01) ⊄ (0.015082871873568143, 0.032157223376795344)
Statistical significance ✓   Practical significance  ✓

Net Conversion:

0 ∈ (-0.005413006265008506, 0.008058749355919152)
(-0.01, 0.01) ⊃ (-0.005413006265008506, 0.008058749355919152)
Statistical significance ✘   Practical significance  ✘

Retention (only evaluate on available data):

0 ∉ (-0.08066989681212079, -0.034535521226287544)
(-0.01, 0, 0.01) ⊄ (-0.08066989681212079, -0.034535521226287544)
Statistical significance ✓   Practical significance  ✓

### Sign Tests

### Follow-Up Experiment¶


## Further Work


## Reference

A/B Testing - Udacity Course Final Project https://classroom.udacity.com/courses/ud257

A/B Testing (great source!)  https://rstudio-pubs-static.s3.amazonaws.com/201749_9fc280333a5c4f448687e1d99b9bdf76.html
