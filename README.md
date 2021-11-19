# Examples of Plots for Manuscripts

We provide examples of plots in R **for publications**.

There are many online tutorials and resources for plotting and dataframe manipulation in R. 
Here, instead, we provide examples and tips for generating plots in R for manuscripts or presentations.

## Contents

  * Line plots
    * [Line plot with error bars](https://github.com/CenikLab/plot_examples/blob/main/line_and_point_plots/line_plots.md)
  * Scatter plots
    * [Scatter Plot with bins](https://github.com/CenikLab/plot_examples/blob/main/scatter/scatter_plain.md)  

## Prerequisites
Basic knowledge of the following are assumed.

  * R
  * [ggplot](https://ggplot2.tidyverse.org/)
  * [dplyr](https://dplyr.tidyverse.org/)

## General Guidelines

  * Use [ggplot](https://ggplot2.tidyverse.org/) instead of R's built-in plotting functions. 
  * Have your plot saved in an object in your script. You may need to combine it with other plots later.
  * Save your plot in PDF format. Vector graphics formats, such as PDF, are higly preferred to pixel-based formats such as jpeg and png.
  * Once you agree on the colors and the general outlook, decide on the dimensions of your plot. Then, work your way backwards. Save your plot in a PDF file. View this file to fine-tune your plot. You may need to do this in many iterations.
  * When you decide to finalize your figures, print them in 100% scale. Make sure they look good on paper too.
  * Have your plotting parameters (axis thickness, font size, etc.) saved in variables in one place. Use these variables throughout your project. This way, you can manage a manuscript with many figures easily and consistently.
  * Have a color scheme and use these colors consistently. For example, use the same shades of blue for control experiments and the same shades of orange for treatment experiments.


 
 

