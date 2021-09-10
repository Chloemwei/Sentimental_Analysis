# hw-09

# Notes 
Please resort to [this folder](data) for two sets of data I used
Please resort to [Rmd file](Airbnb-Comments-Sentimental-Analysis-and-Model.Rmd) for code  
*I adopted sentimental analysis on the data and follow my instructions you will be able to see a Naive Bayes application.  
Please resort to [md file](Airbnb-Comments-Sentimental-Analysis-and-Model.md) for the final report  
Please resort to [this folder](Airbnb-Comments-Sentimental-Analysis-and-Model_files) for visuals I created for analysis

Please make sure below packages are installed before reproducing this task:  
library(tidyverse)
library(here)
library(tidymodels)
library(tidytext)
library(textrecipes)
library(discrim)
library(naivebayes)

# Blokers and Solutions
I did not run into significant errors, everything is pretty smooth. Although I did not figure out the right use of unnest_tokens function, I think it will be great if everyone else can notice that input comes later than output. 

Building on the same techniques we learnt through last few lectures, I can perform the modelling in a more efficient manner. But due to the time limitation - final week, I decide to drop the visualization of confusion matrix, although I know that its result will be pretty. As an alternation, I reported the accuracy metric. I hope this model can be helpful for managers of Airbnb platform. 
