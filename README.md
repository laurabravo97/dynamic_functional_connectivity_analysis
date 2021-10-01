# Dynamic resting-state Functional Connectivity Analysis

Python script to obtain dynamic functional connectivity metrics, after using a sliding window approach, statistical analyses to test for differences between groups and 
plots of results using plotly (code available, but interactive plots don't displayed on github). 


Indices obtained: 

a) average of the Pearson's z-transformed correlation coefficient between pairs of seeds across the set of sliding windows
b) variability of these connectivity values (SD) across windows 


In addition, indices to classify the different states of brain connectivity (i.e. connectivity patterns) were obtained: 

a) proportion of windows in each state
b) Mean Dwell Time (MDT) in each state
c) Probability of Transition (PT) to other states to each specific one. 


Some statistical tests using scipy. 
