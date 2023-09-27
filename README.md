# R-Programming-For-Data-Analytics
R Programming For Data Analytics

#Getting Started with ggplot2. *R creates a scatter plot, puts the variable body mass on the y-axis, and the variable flipper length on the x-axis. #

install.packages("tidyverse")
library("ggplot2")
library("palmerpenguins")

ggplot(data=penguins)+geom_point(mapping=aes(x=flipper_length_mm, y=body_mass_g))

#instead of plotting the relationship between body mass and flipper length, we could use two different variables in the penguins dataset. Let's try bill length and bill depth. We can put bill length on the x-axis and bill depth on the y-axis. #

ggplot(data=penguins)
ggplot(data=penguins)+geom_point(mapping=aes(x=bill_length_mm, y=bill_depth_mm))

#(To learn more about any R function, just run the code question mark function_name. For example, if you want to learn more about the geom_point function, type in question mark geom_point.)#


