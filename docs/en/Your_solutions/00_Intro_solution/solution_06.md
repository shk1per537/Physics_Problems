## 6. Function Analysis

We are given the function:

$$
f(x) = 3x^2 - 12x + 7
$$

We need to identify any local maxima or minima.

---

### Step 1: Find the first derivative

To find the critical points, we first calculate the derivative of $f(x)$ with respect to $x$:

$$
f'(x) = \frac{d}{dx}(3x^2 - 12x + 7) = 6x - 12
$$

### Step 2: Set the derivative to zero

Set $f'(x) = 0$ to find the critical point(s):

$$
6x - 12 = 0
$$

$$
6x = 12
$$

$$
x = 2
$$

So, there is a critical point at $x = 2$.

### Step 3: Determine if it is a maximum or minimum

We can use the second derivative test. Let's find $f''(x)$:

$$
f''(x) = \frac{d}{dx}(6x - 12) = 6
$$

Since $f''(2) = 6 > 0$, the function is concave up at $x = 2$. This means the critical point is a **local minimum**. 

*(Alternatively, note that $f(x)$ is a quadratic function (a parabola) opening upwards because the leading coefficient $3$ is positive. Therefore, its vertex must be a minimum).*

### Step 4: Find the $y$-value of the minimum

Substitute $x = 2$ back into the original function to find the corresponding $y$-value:

$$
f(2) = 3(2)^2 - 12(2) + 7
$$

$$
f(2) = 3(4) - 24 + 7
$$

$$
f(2) = 12 - 24 + 7 = -5
$$

### Final Answer

The function has a **local minimum** at the point **$(2, -5)$**. There are no local maxima.
