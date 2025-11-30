$$\int f(x)dx$$
Starting from this, you can choose a new variable (usually done when there are e.g. logarithms) that depends on x, such as $u = g(x)$

Then, by changing the variable, you must also change $dx$.
$$du = g'(x) dx$$
###### Example
$$\int 2x \cos(x^2)dx$$
**Step 1:** choose the new variable $u = x^2$

Step 2: calculate $du$ (based on what $du$ is).
$$du = (x^2)'dx = 2x dx$$
since we already have a $2x$ in the original function, we substitute as the following:
$$\int 2x \cos(x^2) dx = \int \cos(u)du$$
then integrate in $u$ (it was made possible because it conforms now to integration rules)
$$\int \cos(u) du = \int \sin(u) + C$$
and return to original variable
$$\sin(u) + C = \sin(x^2)+C$$
