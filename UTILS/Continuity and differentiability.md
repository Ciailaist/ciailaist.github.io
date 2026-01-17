Great — you want **a general, repeatable pattern** that works for **ANY continuity/differentiability exercise with a piecewise function**.

I’ll give you a **universal checklist** you can apply to *every* exercise (including the three you showed).  
No prior knowledge needed — just follow the steps mechanically.

***

# ⭐ **THE UNIVERSAL METHOD (THE PATTERN)**

### ✔️ Use this same method for ANY piecewise continuity/differentiability exercise.

***

# 🔵 **STEP 1 — Identify the “boundary point(s)”**

A piecewise function changes formula at some number(s).  
These are the only points where continuity/differentiability can fail.

Examples:

*   If the piece splits at $$x = 3$$ → boundary point is **3**.
*   If the piece splits at $$x = 0$$ → boundary point is **0**.
*   If it splits twice, you will have two boundary points.

**Why?**  
Away from boundaries, the function is just polynomials, exponentials, etc. → automatically continuous and differentiable.

***

# 🔵 **STEP 2 — Compute the LEFT LIMIT at the boundary**

Take the formula used **just before** the boundary.

Example:  
If the function says

$$
f(x) = x^2+1 \quad \text{when } x\le 3
$$

then the formula to the left of 3 is $$x^2+1$$.

Compute:

$$
\lim_{x\to 3^-} f(x)
$$

Just plug in the boundary value.

***

# 🔵 **STEP 3 — Compute the RIGHT LIMIT at the boundary**

Take the formula used **just after** the boundary.

Example:  
If the function says

$$
f(x)=c-x^2 \quad \text{when } x>3
$$

then the right side formula is $$c - x^2$$.

Compute:

$$
\lim_{x\to 3^+} f(x)
$$

Again: plug in the boundary value.

***

# 🔵 **STEP 4 — Make the function continuous**

A function is continuous if:

$$
\text{left limit} = \text{right limit} = \text{function value at boundary}
$$

So you **set these equal** and solve for $$c$$.

This ALWAYS gives you the required value(s) of $$c$$.

***

# 🔵 **STEP 5 — For differentiability, compute LEFT and RIGHT derivatives**

Take the derivative of:

*   the left-side formula
*   the right-side formula

Then evaluate both at the boundary.

Compute:

$$
f'_-(a) \quad \text{and} \quad f'_+(a)
$$

***

# 🔵 **STEP 6 — Set the two derivatives equal**

The function is differentiable at the boundary if:

$$
f'_-(a) = f'_+(a)
$$

If you get a value of $$c$$ → the function is differentiable.  
If the derivatives cannot match → not differentiable.

***

# 🎯 THIS IS THE ENTIRE PATTERN

Let’s now apply the pattern to **your first exercise**:

***

# ✅ APPLYING THE PATTERN TO THIS FUNCTION

$$
f(x)=
\begin{cases}
x^2+1 & x\le 3 \\
c - x^2 & x>3
\end{cases}
$$

Boundary point: **3**

***

## ⭐ Step 2 — Left limit

$$
\lim_{x\to 3^-}(x^2+1)=3^2+1=10
$$

***

## ⭐ Step 3 — Right limit

$$
\lim_{x\to 3^+}(c - x^2)=c - 3^2 = c - 9
$$

***

## ⭐ Step 4 — Make them equal

Continuity requires:

$$
10 = c - 9
$$

Solve:

$$
c = 19
$$

So the function is continuous **only when $$c=19$$**.

***

# ⭐ Step 5 — Differentiability

Left derivative:

$$
f'(x)=2x \quad\Rightarrow\quad f'_-(3)=6
$$

Right derivative:

$$
f'(x) = -2x \quad \Rightarrow\quad f'_+(3)=-6
$$

***

# ⭐ Step 6 — Compare

$$
6 \ne -6
$$

They cannot be made equal, no matter what $$c$$ is.

💥 **The function is NOT differentiable at $$x=3$$** for any value of $$c$$.

***

# 🟢 **SUMMARY OF RESULTS FOR THIS EXERCISE**

*   Continuous **only if**
    $$
    c = 19
    $$
*   Never differentiable at $$x=3$$ (for any $$c$$).

***
