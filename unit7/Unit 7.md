# 2(2)

$ \mu_1 = \int_0^1 x \sqrt \theta x^{\sqrt \theta-1}\mathrm{~d}x = \int_0^1 \sqrt \theta x^{\sqrt \theta}\mathrm{~d}x = \frac{\sqrt \theta}{\sqrt \theta+1} $  
$ \theta = (\frac{\mu_1}{1-\mu_1})^2 $

$ \hat \theta = (\frac{\bar x}{1-\bar x})^2 $

# 3(2)

$ L = \prod_{i=1}^{n} \sqrt \theta x_i^{\sqrt \theta -1} = \theta ^ {\frac n2} (\prod_{i=1}^{n} x_i)^{\sqrt \theta -1} $  
$ \ln L = \frac n 2 \ln \theta + (\sqrt \theta -1) \sum_{i=1}^{n} \ln x_i $ 
$ \frac{\mathrm d}{\mathrm d\theta}\ln L = \frac{n}{2\theta} +\frac{1}{2 \sqrt \theta } \sum_{i=1}^{n}\ln x_i = 0 $



$ \hat \theta = \frac{n^2}{( \sum_{i=1}^{n}\ln x_i)^2} $

$ \hat \theta = \frac{n^2}{( \sum_{i=1}^{n}\ln X_i)^2} $


# 4(1,2)

## (1)

$ \mu_1 = \theta ^ 2 + 2 \times 2 \theta (1 - \theta) + 3 \times (1 - \theta)^2 = 3 - 2 \theta $  
$ \theta = \frac{1}{2}(3 - \mu_1) $

$ \hat \theta = \frac{1}{2}(3 - \bar x) = \frac 5 6 $

$ L = \prod_{i=1}^{3} P(X_i = x_i) = \theta^2 \times 2 \theta(1-\theta) \times \theta^2 = 2 \theta^5(1 - \theta) $  
$ \ln L = \ln 2 + 5 \ln \theta + \ln (1-\theta) $  
$ \frac{\mathrm d}{\mathrm d\theta}\ln L = \frac{5}{\theta} - \frac{1}{1-\theta} = 0 $  

$ \hat \theta = \frac 5 6 $


## (2)

$ L = \prod_{i=1}^{n} \frac{\lambda^{x_i}e^{-\lambda}}{x_i!} = \lambda ^ {\sum_{i=1}^{n}x_i} e^{- n\lambda} $  
$ \ln L = -n \lambda + (\sum_{i=1}^{n}x_i)\ln \lambda - \ln \prod_{i=1}^{n}x_i! $  
$ \frac{\mathrm d}{\mathrm d\lambda}\ln L = -n + \sum_{i=1}^{n} \frac{x_i}{ \lambda} = 0 $  

$ \hat \lambda = \frac{\sum_{i=1}^{n}x_i}{n} = \bar x $  
$ \hat \lambda  = \bar X $


# 7(1)

$ P(X = 0) = \frac{\lambda^0 e^{-\lambda}}{0!} = e^{-\lambda} $  
$ \hat P(X = 0) = e ^{-\bar x} $

# 10

## (1)

$ E( c \sum_{i=1}^{n-1}(X_{i+1} - X_i)^2) = c \sum_{i=1}^{n-1} E( D(X_{i+1} - X_i) + E^2(X_{i+1} - X_i)) $  
$ = c \sum_{i=1}^{n-1} D(X_{i+1}) + D(X_i) = 2 \sigma^2(n-1)c $  

$ E( c \sum _{i=1}^{n-1} (X_{i+1} - X_i )^2) = \sigma^2 $

$ c = \frac{1}{2(n-1)} $

## (2)

$E( \bar X - c S^2 ) = E(\bar X^2) - cE(S^2) = ( \frac{\sigma^2}{n} + \mu^2) - c \sigma^2 = \mu^2 $  

$ c = \frac{1}{n} $

# 11

## (1)

$$

 L(\theta)=\frac{1}{\theta^{n}} \prod_{i=1}^{n} x_{i}^{(1-\theta) / \theta} \\
 \ln L(\theta)=-n \ln \theta+\frac{1-\theta}{\theta} \ln \prod_{i=1}^{n} x_{i} \\
 \frac{\mathrm{d}}{\mathrm{d} \theta} \ln L(\theta)=-\frac{n}{\theta}+(\sum_{i=1}^{n} \ln x_{i})(\frac{-1}{\theta^{2}})=0 
-n \theta=\sum_{i=1}^{n} \ln x_{i} \\
 \hat \theta = \frac{-1}{n} \sum_{i=1}^{n} = \ln X_i 

$$


## (2)

$$

\begin{aligned}
E(-\ln X) & =\int_{0}^{1}(-\ln x) \cdot \frac{1}{\theta} x^{\frac{1}{\theta}-1} \mathrm{~d} x \\
& =-x^{\frac{1}{\theta}} \ln x|_{0} ^{1}+\int_{0}^{1} \frac{1}{x} x^{\frac{1}{\theta}} \mathrm{d} x \\
& = \theta
\end{aligned}\\

E(\hat{\theta})=\frac{1}{n} \sum_{i=1}^{n} E(-\ln X_{i})=\frac{1}{n} \cdot n \theta=\theta,

$$

# 12

## (1)

$ E(X_i) = \theta , D(X_i) = \theta^2 $  
$ E(T_1) = \theta $  
$ E(T_2) = 2\theta $  
$ E(T_3) = \theta $  

## (2)


$ \begin{aligned}
D(T_1) &= D( \frac{1}{6} (X_1+X_2) + \frac{1}{3} (X_3 + X_4)) \\
&= \frac{1}{36} D(X_1+X_2) + \frac{1}{9} D(X_3+X_4) \\
&= \frac{2}{36} \theta^2 + \frac{2}{9} \theta^2 \\
&= \frac{5}{18} \theta^2
\end{aligned} $  

$ D(T_3) = \frac{1}{16} \sum_{i=1}^{4}D(X_i) = \frac{4}{16}\theta^2 <D(T_1) $  

$统计量 T_3 比 T_1 有效$


# 13(1)

$ E(\hat \theta ^ 2) = E((\hat \theta)^2) = D(\hat \theta) + E^2(\hat \theta) = D(\hat \theta) + \theta^2 > \theta ^2 $  
$\hat  \theta ^ 2 = (\hat \theta) ^ 2 不是无偏估计两$


# 16

## (1)

$ P(-z_{\alpha/2} < \frac{\bar X  - \mu}{ \sigma / \sqrt{n}} < z_{\alpha/2}) = 1 - \alpha $  
$ P( \bar X - \frac{\sigma}{\sqrt{n}}z_{\alpha/2} < \mu < \bar X + \frac{\sigma}{\sqrt{n}}z_{\alpha/2}) = 1 - \alpha $  

$ ( 6 \pm \frac{0.6}{3} z_{0.025}) = (5.608, 6.392) $


## (2)

$ P( \bar X - \frac{S}{\sqrt{n}}t_{\alpha/2}(n-1) < \mu < \bar X + \frac{S}{\sqrt{n}}z_{\alpha/2}(n-1)) = 1 - \alpha $  

$ ( 6 \pm \frac{\sqrt{0.33}}{3} 2.306) = (5.558, 6.442) $

# 17

## (1)

$ (\bar x \pm \frac{s}{\sqrt{n}} t_{\alpha/2}(n-1)) = (6.678 \pm \frac{0.00387}{\sqrt{6}} \times 2.0150) = (6.675,6.681) $


$ P(\chi ^2_{1-\alpha/2}(n-1) < \frac{(n-1)S^2}{\sigma^2} < \chi ^2_{\alpha/2}(n-1)) = 1 - \alpha $  
$ P( \frac{S^2}{\chi^2_{\alpha/2}} < \sigma^2 < \frac{S^2}{\chi^2_{1-\alpha/2}}) = 1 - \alpha $  

$ (6.8 \times 10 ^{-6},6.5 \times 10 ^{-5}) $


## (2)

$ \mu: (6.661,6.667) $  

$ \sigma^2: (3.8 \times 10 ^{-6},5.06 \times 10 ^{-5}) $  


# 18

$ (\frac{\sqrt{n-1}S}{\sqrt{\chi ^2_{\alpha/2}(n-1)}} ,\frac{\sqrt{n-1}S}{\sqrt{\chi ^2_{1-\alpha/2}(n-1)}}) = (7.4,21.1) $


# 21

$ n_1 = 4 $  
$ \bar x_1 = 0.14125 $  
$ 3s_1^2 = 0.00002475 $  
$ n_2 = 5 $  
$ \bar x_2 = 0.1392 $  
$ 4s_2^2 = 0.0000208 $  
$ \alpha = 0.05 $  
$ s_\omega^2  = \frac{ 3s_1^2+4s_2^2}{7} = 0.00255^2 $  
$ t_{\alpha/2}(n_1 + n_2 - 2) = 2.3646 $  

$ (\bar x_1 - \bar x_2 \pm t_{\alpha/2}(n_1 + n_2 - 2)s_\omega{\sqrt{1/n_1+1/n_2}}) $  
$ = (-0.002,0.006) $


# 23

$ (\frac{s_A^2}{s_B^2 \times F_{0.025}(9,9)} , \frac{s_A^2}{s_B^2 \times F_{0.975}(9,9)}) = (0.222,3.601) $

# 25

## (1)

$ P(-z_{\alpha/2} < \frac{\bar X  - \mu}{ \sigma / \sqrt{n}} < z_{\alpha/2}) $  
$ P( \bar X - \frac{\sigma}{\sqrt{n}}z_{\alpha/2} < \mu < \bar X + \frac{\sigma}{\sqrt{n}}z_{\alpha/2}) $  

$上限 : \mu = 6 + \frac {0.5745}{3} = 6.356 $

## (2)

$ \mu_1 - \mu_2  = \bar x_1 - \bar x_2 - t_{\alpha}(n_1 + n_2 - 2)s_{\omega}\sqrt{1/n_1+1/n_2} = -0.0012 $

## (3)

$ P(\frac{S_A^2/S_B^2}{\sigma_A^2/\sigma_B^2} > F_{0.95}(9,9))=0.95  $  

$ \bar {\frac{\sigma_A^2}{\sigma_B^2}} = \frac{s_A^2}{s_B^2 \times F_{0.95}(9,9)} = 2.84$