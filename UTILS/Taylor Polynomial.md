The idea behind it is to approximate a function in a part using a polynomial of n-th degree. Why? Because polynomials are easy for computers and calculators to handle, while logarithms are more complicated.

![alt text](https://github.com/Ciailaist/ciailaist.github.io/blob/main/a-imgs/Pasted%20image%2020251107174430.png "Expr")

E.g. assume we want to approximate a function f at some point a, with a polynomial of degree 1, $P_1(x)$. We want:
+ f and P to have the same value in a
+ their derivative to have the same value

The further we go from a (the "meeting point"), f and P may become completely different.
A better approximation can be obtained with polynomial of larger degree, since the higher the degree, the more we can "adjust" the polynomial to "look like" f.

To obtain a polynomial of degree n (provided that f is n-times differentiable in a):
$$P_n(x) = f(a) + \frac{f'(a)}{1!}(x-a)+\frac{f''(a)}{2!}(x-a)^2 + \frac{f'''(a)}{3!}(x-a)^3 + ... + \frac{f^{(n)}(a)}{n!}(x-a)^n$$

If a = 0, we also call polynomial $P_n$ n-th order Taylor Polynomial for f about part a. If a = 0 we also call $P_n$ McLaurin polynomial. 
