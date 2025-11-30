
###### Step 1: check why improper
Is it because of an infinite interval, e.g. $[a, \infty)$ or a **singularity** in the interval (it means that in a certain point the function suddenly $\to \infty$ from both right and left sides).

###### Step 2: rewrite as limit
This is the case for an improper integral because of infinite interval:
$$\int^{\infty}_a f(x)dx = \lim_{R \to \infty} \int^R_a f(x)dx$$
$$\int_{-\infty}^b f(x)dx = \lim_{L \to -\infty} \int^b_L f(x)dx$$
while if there is a singularity in $c \in (a, b)$:
$$\int^b_a f= \lim_{\epsilon \to 0+}(\int^{c-\epsilon}_a f + \int^b_{c + \epsilon} f$$
(basically it's rewritten as the sum of the two integrals coming from both sides of the singularity, left and right)

###### Step 3: comparison criteria
Check if it's possible to use comparison criteria (basically comparing the behaviour of the function to an already known one)

https://chatgpt.com/s/t_69288f2a4cc88191a7c7dc01872a0586

###### Step 4: if not possible to use comparison criteria, solve the limit

