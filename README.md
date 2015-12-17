# normality_shinyapp
Shiny application showing the sampling distribution of sample means of samples taken from distributions of various shapes.

This repository contains code to run an application via the R package Shiny. The application helps those interested in visualizing
the sampling distribution of sample means of samples taken from distributions of shapes ranging from normal distributions,
skewed distributions, and even multinomial distributions. 

To run the application, open up R and copy-paste the following code into the console (or into a script and run the code from there):

  install.packages("shiny", dependencies = TRUE)
  
  install.packages("VGAM", dependencies = TRUE)
  
  shiny::runGitHub("matthewbranan/normality_shinyapp")
