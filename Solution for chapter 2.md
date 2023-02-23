Solution for chapter 2 

2.1

According to the definition of expectation (.i.e $E$) 

$ E(x) $ = $0.4*f(1)$+$0.1*f(2)$+$0.5*f(3)$

=14.6

2.2

![image-20230222170509104](C:\Users\zsm\AppData\Roaming\Typora\typora-user-images\image-20230222170509104.png)

2.3

Let the random variable $Z_{i} = 4*f(x_i,y_i)-\pi$

we have $q_n-\pi =\frac{1}{n}\Sigma_{i=1}^{n}Z_i$

since 

![image-20230222172303928](C:\Users\zsm\AppData\Roaming\Typora\typora-user-images\image-20230222172303928.png)

so we have $\Bbb P(|q_n-\pi|\ge \frac{1}{\sqrt{n}}) \le exp(-\frac{3}{6+\frac{1}{\sqrt n}})$

sin n is large ,so  $\Bbb P(|q_n-\pi|< \frac{1}{\sqrt{n}}) >1- exp(-\frac{3}{6+\frac{1}{\sqrt n}})$ is large

prove all.

2.4

Use of mathematical induction,let's assume $q_n = (1-\frac{1}{n})*q_{n-1}+\frac{1}{n}*f(x_{n})$ = $\frac{1}{n}\Sigma_{i=1}^{n}f(x_{i})$

we have $q_{n+1}=(1-\frac{1}{n+1})*q_{n}+\frac{1}{n+1}*f(x_{n+1})$ = $\frac{1}{n+1}\Sigma_{i=1}^{n}f(x_i)+\frac{1}{n+1}f(x_{n+1})$ = $\frac{1}{n+1}\Sigma_{i=1}^{n+1}f(x_i)$

prove all.