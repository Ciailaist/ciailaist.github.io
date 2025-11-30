##### Rules
---
1. Power rule:
	If $f(x) = x^n$ then $f'(x) = nx^{n-1}
2. Constant multiple:
	If $f(x) = c \cdot g(x)$ then $f'(x) = c \cdot g'(x)$
3. Sum / difference:
	$(g(x)) \pm h(x))' = g'(x) \pm h'(x)$
4. Product rule:
	If $f(x) = u(x)v(x)$ then $f'(x) = u'(x)v(x) + u(x)v'(x)$
5. Quotient rule:
	If $f(x) = \frac{u(x)}{v(x)}$ then $f'(x) = \frac{u'(x)v(x)-u(x)v'(x)}{[v(x)]^2}$
6. Chain rule (composition):
	If $f(x) = g(h(x))$ then $f'(x) = g'(h(x)) \cdot h'(x)$
7. Constant derivative
	If $f(x) = c$ where c is a constant, then $f'(x) = 0$ because constants never change.

###### Recipe
----
1. Simplify $f$ whenever possible
2. Identify which rules apply
3. Compute derivatives of inner pieces (like $u'(x), v'(x)$)
4. Plug into the correct rule
5. Simplify algebra (collect like terms, factor powers)

## First derivative and increasing/decreasing
---
The sign of $f'(x)$ tells you how $f(x)$ behaves:
+ If $f'(x) > 0$  -> the slope is positive -> $f(x)$ is increasing
+ If $f'(x) < 0$  -> the slope is negative -> $f(x)$ is decreasing
+ If $f'(x) = 0$  -> the tangent is flat (horizontal)

#### Critical points
---
Critical points are all x such that $f'(x) = 0$ or $f'(x)$ does not exist, and $x \in \text{domain of }f$
We check them because local maxima or minima can only occur there (or at domain boundaries)

#### Local maxima and minima
---
= describe where a function "peaks" or "dips" locally:
+ **Local maximum**: $f(x_0)$ if higher than nearby values
	E.g. $x= 0$ in $f(x) = -x^2$
+ **Local minimum** $f(x_0)$ is lower than nearby values
	E.g. $x= 0$ in $f(x) = x^2$
###### How to find them
1. Compute $f'(x)$
2. Solve $f'(x) = 0$
3. Use the sign of $f'(x)$:
	+ If $f'$ changes from + to - -> local maximum
	+ If $f'$ changes from - to + -> local minimum
	+ If $f'$ doesn't change sign -> not a max/min
###### Example
Take $f(x) = x^2$
1. $f'(x) = 2x$
2. $f'(x) = 0$ at $x= 0$ -> critical point
3. For $x<0, f'(x) <0$ (decreasing); for $x>0, f'(x) > 0$ (increasing). So the sing changes from - to + -> local minimum at $x=0$


## Second derivative
---
##### How to find
---
The second derivative $f''$ is simply the derivative of $f'$. You take the derivative again and apply the same [[#Rules]].

##### What it tells you
---
+ $f'(x)$ measures how fast $f(x)$ is changing (slope)
+ $f''(x)$ measures how fast that slope is changing (curvature)

So:
+ if $f''(x) > 0$, the slope is increasing -> the graph is convex (going upward)
+ if $f''(x) < 0$, the slope is decreasing -> the graph is concave (going downward)

#### Inflection points
---
= it's a point on the graph where the curve changes from concave to convex, or the other way around.

Mathematically, a point $x_0$ is an inflection point if:
1. $f''(x) = 0$ or $f''(x_0)$ is undefined (means that x is not in the domain) and,
2. the sign of $f''(x)$ changes when passing through $x_0$

**Example:**
For $f(x) = x^3, f''(x) = 6x$
At $x=0, f''(0) = 0$.
+ For $x<0: f'' < 0$, thus concave
+ For $x>0: f'' > 0$, thus convex
 So $x=0$ is an inflection point, and the point is (0,0).