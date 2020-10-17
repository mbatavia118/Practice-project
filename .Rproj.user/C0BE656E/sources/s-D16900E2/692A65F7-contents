#1.10 practice problem - make a graph of y=x^2

#clear brain
rm(list=ls())

#define x and y
x<-seq(-10, 10, 0.5)
y<-x^2

#make the graph
qplot(x,y, geom="line", color="red")

#1.10 practice problem 2 - make a graph of y=sinx

#clear brain
rm(list=ls())

#define x and y
x<-seq(0,25,0.5)
y<-sin(x)

qplot(x,y,geom="line")

#practice problem 3 - plot 1000 randomly generated numbers from a normal distribution

#clear brain
rm(list=ls())

#library needed = stats
library(stats)

#generate 1000 observations from a normal distribution and store as x
x<-rnorm(1000, mean = 0, sd=1)

#generate a histogram of these values
qplot(x, binwidth=0.1)
