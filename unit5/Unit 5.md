# 4

令第$i$个零件的质量是$X_i$,$W$是总质量，则有

$$
\sum_{i=1}^{5000} X_i = W
$$

$ E(X_i) = 0.5 , D(X_i) = 0.1^2 $  
$ \frac{W-5000 \times 0.5}{\sqrt{5000} \times 0.1} $ 近似 $N(0,1)$  
$ P(W>2510) = 1 - P(W \leq 2510) =  1 - \Phi(\frac{2510-5000 \times 0.5}{\sqrt{5000} \times 0.1}) = 1 - \Phi(\sqrt 2) $  
$ \approx 0.0787 $

# 7 

## (1)

$ E(X_i) = 1.29 $  
$ E(X_i^2) = 1.713 $  
$ D(X_i) = E(X_i^2) - E^2(X_i) = 0.0489 $  

令$ W = \sum_{i=1}^{300} X_i $  
$P(W \geq 400) = P(\frac{400-300 \times 1.29}{\sqrt{300} \times \sqrt{0.0489}} \leq \frac{W-300 \times 1.29}{\sqrt{300} \times \sqrt{0.0489}}) $  
$ \approx 1 - \Phi(3.39) = 0.0003 $

## (2)

$ E(Y) = 300 \times 0.2 $  
$ D(Y) = 300 \times 0.2 \times 0.8 $  
$ P(Y \geq 60) = 1 - P(Y \leq 60) = 1 - P(\frac{Y - 300 \times 0.2}{\sqrt{300} \times \sqrt{0.2 \times 0.8}} \leq \frac{60-300 \times 0.2}{\sqrt{300} \times \sqrt{0.2 \times 0.8}}) $  
$ \approx 1 - \Phi(0) = 0.5 $




# 12

$ E(X_i) = 1.2 $  
$ E(X_i^2) = 1.8 $  
$ D(X_i) = E(X_i^2) - E^2(X_i) = 0.36 $  

令$ s = \sum_{i=1}^{200} X_i $  
$ s \sim N(200 \times 1.2, 200 \times 0.36)$  

$ 0.95 \leq P(s \leq n) $ 
$ 0.95 \leq \Phi(\frac{n-200 \times 1.2}{\sqrt{200} \times \sqrt{0.36}}) = \Phi(\frac{n-240}{\sqrt{72}}) $  
$ n \geq 240 + 1.645 \times sqrt{72} $  
$ n \geq 254 $

