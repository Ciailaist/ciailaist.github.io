
Two common views of the integral:
+ The integral of a function f on a closed interval (a, b) is the "area" that is bound by f and x-axis, and lines passing a, f(a) and b, f(b).
![[Pasted image 20251107184131.png]]
+ The integral f a function f is another function F such that f is "anti-derivative" of F, i.e. F'(x) = f(x). More on this:

An integral is the _reverse_ of taking a derivative.  
It answers the question:
> “What function F(x) has a derivative equal to f(x)?”

We write this as:
$$∫f(x) dx=F(x)+C$$

Example (reverse of derivative)
You know that
$$\frac{d}{dx}(x^2) = 2x$$

So if we go _backwards_:
$$\int 2x\,dx = x^2 + C$$
That’s all an **indefinite integral** means — it’s the set of all functions whose derivative gives you the integrand.

### Indefinite integral
---
They are integrals where bounds have been omitted (useful when discussing a theoretical aspect or when the bounds are not important.)
![[Pasted image 20251107194012.png]]
instead of e.g.
![[Pasted image 20251107194222.png]]
-> Note that **the same properties apply** for definite integral as well as indefinite integral (theorem 3, lect 15)


### Improper integrals
---
Until now the integrals had the restriction that the the function f had to be defined and bounded on a finite interval [a, b]. Let's relax these restrictions.
There are two kinds:
+ **IMPROPER INTEGRAL OF FIRST KIND**: is when $b \to +\infty$ in $\int_a^b f(x)dx$. This is an infinite integral that is denoted with $\int_a^{\infty}f(x)dx$
+ **IMPROPER INTEGRAL OF SECOND KIND**: is when we keep the interval [a, b] finite but f is not bounded as $x \to a$ or $x \to b$. E.g. $f(x) = 1/x$ is not bound on [0,1] since $f \to \infty$ when $x \to 0$
