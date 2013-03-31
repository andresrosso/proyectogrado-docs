
x.poi<-rpois(n=100,lambda=20) # a vector of random variables from the Poisson distr.


#In case of count data we can use goodfit() included in vcd package
library(vcd) ## loading vcd package
gf <- goodfit(x.poi,type= "poisson",method= "MinChisq")
summary(gf)
plot(gf,main="Count data vs Poisson distribution")

write.csv(x.poi, file = "c:/temp/XPoi.csv")