## 9. Optimization Problem

We have a rectangle in the first quadrant situated under the curve $y = 3 - x^2$. We need to find its dimensions (width and height) that give the maximum area.

---

### Step 1: Define the area function

Let the width of the rectangle along the x-axis be $x$. Since the top-right corner of the rectangle touches the curve, its height will be $y = 3 - x^2$.

The area ($A$) of a rectangle is width multiplied by height:

$$
A(x) = x \cdot (3 - x^2)
$$

$$
A(x) = 3x - x^3
$$

### Step 2: Find the derivative

To find the maximum area, we need to find the critical points by taking the first derivative of the area function with respect to $x$:

$$
A'(x) = \frac{d}{dx}(3x - x^3) = 3 - 3x^2
$$

### Step 3: Set the derivative to zero

Set $A'(x) = 0$ to find the critical value for $x$:

$$
3 - 3x^2 = 0
$$

$$
3x^2 = 3
$$

$$
x^2 = 1
$$

Since the rectangle is in the first quadrant, the width $x$ must be positive, so:

$$
x = 1
$$

*(We can quickly confirm this is a maximum using the second derivative test: $A''(x) = -6x$. Since $A''(1) = -6 < 0$, the curve is concave down at this point, meaning it is indeed a maximum).*

### Step 4: Find the corresponding height

Now substitute $x = 1$ back into the curve equation to find the height ($y$):

$$
y = 3 - (1)^2
$$

$$
y = 3 - 1 = 2
$$

### Final Answer

The dimensions of the rectangle with the maximum area are:

$$
\text{Width} = 1, \qquad \text{Height} = 2
$$
