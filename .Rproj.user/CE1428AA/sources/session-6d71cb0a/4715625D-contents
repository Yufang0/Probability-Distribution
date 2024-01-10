# f(y)=ky^3(1-y)^2,0<=y<=1
# Y~Beta(4,3)

#用反函數改念求出pbeta(y,4,3)=0.95的y
result <- uniroot(function(y) pbeta(y, 4, 3) - 0.95, interval = c(0, 1))
y=result$root;y