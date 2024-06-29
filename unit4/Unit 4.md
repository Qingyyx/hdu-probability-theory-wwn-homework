# 3

$ P(X = 4) = \frac{1}{64}  $  
$ P(X = 3) = \frac{2^3-1^3}{64} $  
$ P(X = 2) = \frac{3^3-2^3}{64} $  
$ P(X = 1) = \frac{4^3-3^3}{64} $  

$ E(X) = \sum_{k=1}^{4}kP(k) = \frac{25}{16} $

# 5

$ E(X) = \int_{-\infty}^{\infty} xf(x)dx $  
$ = \int_{0}^{1500} xf(x) dx +\int_{1500}^{3000} xf(x) dx $  
$ = \int_{0}^{1500} x \frac{1}{1500^2}x dx +\int_{1500}^{3000} x\frac{-1}{1500^2}(x-3000) dx $  
$ = \frac{1}{1500^2} \int_{0}^{1500} x^2 dx - \frac{1}{1500^2} \int_{1500}^{3000} x(x-3000) dx $  
$ = \frac{1}{1500^2} \left[ \frac{1}{3}x^3 \right]_0^{1500} - \frac{1}{1500^2} \left[ 3000 \times \frac{1}{2}x^2 -\frac{1}{3}x^3  \right]_{1500}^{3000} $  
$ =1500 $


# 6

## (1)

$ E(X) = \sum xP(x) = -0.2 $  
$ E(X^2) = \sum x^2P(x) = 2.8 $  
$ E(3X^2 + 5) = 3E(X^2) + 5 = 13.4 $

## (2)

$ X \sim \pi( \lambda ) $  
$ P(X = k) = \frac{ \lambda^k e^{-\lambda} }{k!} $

$ E(\frac{1}{X+1}) = \sum_{k=0}^{\infty} \frac{1}{k+1} \frac{ \lambda^k e^{-\lambda} }{k!} = \sum_{k=0}^{\infty} \frac{ \lambda^k e^{-\lambda} }{(k+1)!} $  
$ =\frac{e^{-\lambda}}{\lambda} \sum_{k=1}^{\infty}\frac{e^k}{k!} $  
$ \frac{e^{-\lambda}}{\lambda}(e ^{\lambda}-1) = \frac{1}{\lambda}(1-e^{-\lambda}) $

# 8

## (1)

$ E(X) = \sum_{i=1}^{3} \sum_{j=1}^{3} x_i p_{ij} = 2 $  
$ E(Y) = \sum_{i=1}^{3} \sum_{j=1}^{3} y_i p_{ij} = 0 $

##  (2)

$ E(Z) = E( \frac YX ) = \frac YX p_{xy} = -\frac{1}{15} $

## (3)

$ E((X-Y)^2) = \sum_{i=1}^{3} \sum_{j=1}^{3} (x_i - y_j)^2 p_{ij} = 5 $

# 9(1)

# 14

# 20

# 22

# 26

# 29

# 31

# 32

# 34(1)

# 36