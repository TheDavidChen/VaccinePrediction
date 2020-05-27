# VaccinePrediction

This project was a collaboration between Sandesh Bhandari, David Chen, and Elizabeth Saline for our STAT 508 (Data Mining and Supervised Learning) course. This project was completed on May 4th, 2020. 

# Introduction 

Vaccines have proven an effective way to protect people against certain viral diseases, but not everyone gets the vaccines that are available. There are some legitimate reasons people cannot get a vaccine (e.g. compromised immunity or allergy to an ingredient) that cannot be overcome, but other people avoid vaccines without these reasons.

The data for this project comes from a contest hosted by DrivenData. The goal of the contest is to predict how likely individuals are to receive two vaccines: the H1N1 and seasonal flu. The data was collected through the National 2009 H1N1 Flu Survey. A number of belief, behavior, and demographic factors were collected and used to create models to predict whether the individual received one, both, or neither of the vaccines.

Since we are dealing with 2 classification problems, we explored the classification methods from the STAT 508 course. Specifically, we looked at regression methods, tree-based methods and support vector machines (SVM). We compared the test set results of all these methods and found that some of them worked well while others did not. We found that support vector machines seemed to perform the best overall. For seasonal vaccination prediction, the radial SVM had the best overall test set accuracy of 78.3%. For h1n1 vaccination prediction, full logistic regression resulted in the best overall test set accuracy of 83.1%.

# Reproduction

R version 3.6.0 was used to create this project, along with multiple packages (see final report). Tidyverse 1.3.0 was used frequently. 

Note that the `Final_Report.html` covers all the work done in this repo. The code in the `Source` file simply represent the individual parts before we aggregated everything together. Note that the `Source` folder was created after everything was completed, so if one would like to reproduce the work, rename the data source location. 
