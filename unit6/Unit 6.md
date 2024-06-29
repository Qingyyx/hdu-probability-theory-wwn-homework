# 1

$\tilde{X} = \frac{1}{36} \sum_{i=1}^{36}X_i $  
$ X \sim N(52,6.3^2) $  
$ E(\tilde X)=52 , D(\tilde X)=1.05^2 $  
$ \tilde X \sim N(52,1.05^2) $

$ P(50.8 \leq \tilde X \leq 53.8) = \Phi(\frac{53.8-52}{1.05}) - \Phi(\frac{50.8-52}{1.05}) = \Phi(1.71) - \Phi(-1.14) = 0.8293  $  

# 4

## (1)

$ \frac{X_1 + X_2 + X_3}{\sqrt 3} \sim N(0,1) $  
$ \frac{X_4 + X_5 + X_6}{\sqrt 3} \sim N(0,1) $  

$ \frac{(X_1 + X_2 + X_3)^2}{3} + \frac{(X_4 + X_5 + X_6)^2}{3} \sim \chi^2 (2) $  

$ \frac 13 Y \sim \chi^2 $  
$ C = \frac 13 $

## (2)

$ \frac{X_1 + X_2}{\sqrt 2} \sim N(0,1) $

$ \frac{(X_1+X_2) \div \sqrt 2 }{ \sqrt{ (X_3^2+X_4^2+X_5^2) \div 3 } }  = \sqrt{\frac{3}{2}}\frac{X_1 + X_2}{\sqrt{ (X_3^2+X_4^2+X_5^2) }} = t(3) $  
$ C = \sqrt{\frac 32} $

## (3)

$ X = \frac{Z}{\sqrt{\frac Yn}} $  
$ X^2 \sim F(1,n) $

# 6

## (1)

$ P = \prod_{i = 0}^{n}P(X_i = x_i) = \prod_{i = 0}^{n}[p^{x_i}(1-p)^{1-x_i}] $  
$ = p^{\sum_{i=1}^{n}x_i}(1-p)^{\sum_{i=1}^{n}(1-x_i)} $  


## (2)

$ P( \sum_{i=1}^{n}x_i = k ) = \binom{n}{k} p^k(1-p)^{n-k}  $

## (3)

$ E( \tilde X ) = p , D( \tilde X ) = \frac{p(1-p)}{n} $  
$ E(S^2) = D(X) = p(1-p) $


# 7

$ E( \tilde X ) = n , D( \tilde X) = \frac{n}{5}  $  
$ E(S^2) = D(X) = 2n $

# 8

## (1)

$f_{x_i}(x_i) = \frac{1}{\sqrt{2 \pi } \sigma }e^{-\frac{(x_i-\mu )^2}{2 \sigma ^2}}$

$ \prod_{i=1}{10} f_{x_i}(x_i) = \prod_{i=1}{10} \frac{1}{\sqrt{2 \pi } \sigma }e^{-\frac{(x_i-\mu )^2}{2 \sigma ^2}} $  
$ = \frac{1}{(2 \pi \sigma^2)^5}e^{-\sum_{i=1}^{10}\frac{(x_1-\mu )^2}{2 \sigma ^2}}$

## (2)

$ f_{\bar x}(x) = \frac{\sqrt {10}}{\sqrt{2 \pi } \sigma}e^{-5\frac{(x-\mu )^2}{\sigma ^2}} $

$ = \frac{\sqrt {5}}{\sqrt{\pi } \sigma}e^{-5\frac{(x-\mu )^2}{\sigma ^2}} $
