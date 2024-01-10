# y=80,z=0.5  y=90,z=1.5
# Y~Normal(75,100)

#畫出常態分佈圖
draw<- function() {
  z=seq(from=-3,to=3,by=0.1)
  y=dnorm(z,0,1)
  plot(z,y, type='l')
}

#p(0<=Z<=1.2)
#在常態分佈圖上填上機率面積
draw()
z1=seq(from=0,to=1.2,by=0.1)
y1=dnorm(z1,0,1)
polygon(c(0,z1,1.2),c(0,y1,0),col="pink")
#實際機率數值
pnorm(1.2, 0, 1)-pnorm(0, 0, 1)

#p(-0.9<=Z<=0)
#在常態分佈圖上填上機率面積
draw()
z1=seq(from=0,to=1,by=0.1)
y1=dnorm(z1,0,1)
polygon(c(0,z1,1),c(0,y1,0),col="pink")
#實際機率數值
pnorm(0, 0, 1)-pnorm(-0.9, 0, 1)

#p(0.3<=Z<=1.56)
#在常態分佈圖上填上機率面積
draw()
z1=seq(from=0.3,to=1.56,by=0.1)
y1=dnorm(z1,0,1)
polygon(c(0.3,z1,1.56),c(0,y1,0),col="pink")
#實際機率數值
pnorm(1.56, 0, 1)-pnorm(0.3, 0, 1)

#p(-0.2<=Z<=0.2)
#在常態分佈圖上填上機率面積
draw()
z1=seq(from=-0.2,to=0.2,by=0.1)
y1=dnorm(z1,0,1)
polygon(c(-0.2,z1,0.2),c(0,y1,0),col="pink")
#實際機率數值
pnorm(0.2, 0, 1)-pnorm(-0.2, 0, 1)

#p(-1.56<=Z<=-0.2)
#在常態分佈圖上填上機率面積
draw()
z1=seq(from=-1.56,to=-0.2,by=0.1)
y1=dnorm(z1,0,1)
polygon(c(-1.56,z1,-0.2),c(0,y1,0),col="pink")
#實際機率數值
pnorm(-0.2, 0, 1)-pnorm(-1.56, 0, 1)