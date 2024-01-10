# y=80,z=0.5  y=90,z=1.5
# Y~Normal(75,100)

z=seq(from=0,to=1.2,by=0.1)
y=dnorm(z,0,1)
plot(-3,y, type='l')
polygon(c(0,z,1.2),c(0,y,0),col="pink")

#p(0<=Z<=1.2)
pnorm(1.2, 0, 1)-pnorm(0, 0, 1)

#p(-0.9<=Z<=0)
pnorm(0, 0, 1)-pnorm(-0.9, 0, 1)

#p(0.3<=Z<=1.56)
pnorm(1.56, 0, 1)-pnorm(0.3, 0, 1)

#p(-0.2<=Z<=0.2)
pnorm(0.2, 0, 1)-pnorm(-0.2, 0, 1)

#p(-1.56<=Z<=-0.2)
pnorm(-0.2, 0, 1)-pnorm(-1.56, 0, 1)