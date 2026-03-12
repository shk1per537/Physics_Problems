## 10. Infinite Series

An ant starts at the origin $(0,0)$ and moves in a sequence: $1$ m East, $1/2$ m North, $1/3$ m West, $1/4$ m South, $1/5$ m East, and so on. We need to determine its final $(x, y)$ coordinates after an infinite number of steps.

---

### Step 1: Separate the movements into $x$ and $y$ coordinates

The ant moves alternately along the $x$-axis (East/West) and the $y$-axis (North/South).

* **Movements along the $x$-axis (East is positive, West is negative):**
    * Step 1: $+1$
    * Step 3: $-1/3$
    * Step 5: $+1/5$
    * ...and so on.

* **Movements along the $y$-axis (North is positive, South is negative):**
    * Step 2: $+1/2$
    * Step 4: $-1/4$
    * Step 6: $+1/6$
    * ...and so on.

### Step 2: Evaluate the infinite series for the $x$-coordinate

The final $x$-coordinate is the sum of this alternating series:

$$
x = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots
$$

This is the well-known Gregory-Leibniz series, which corresponds to the Maclaurin series expansion for $\arctan(z)$ evaluated at $z = 1$. Since $\arctan(1) = \frac{\pi}{4}$, we get:

$$
x = \frac{\pi}{4}
$$

### Step 3: Evaluate the infinite series for the $y$-coordinate

The final $y$-coordinate is the sum of this alternating series:

$$
y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \dots
$$

We can factor out $\frac{1}{2}$ from the entire sequence:

$$
y = \frac{1}{2} \left( 1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots \right)
$$

The series inside the parentheses is the alternating harmonic series, which converges to the natural logarithm of 2 ($\ln(2)$). Therefore:

$$
y = \frac{1}{2}\ln(2)
$$

*(Note: This can also be written as $\ln(\sqrt{2})$ using logarithm properties).*

### Final Answer

The final position of the ant is at the coordinates:

$$
\left( \frac{\pi}{4}, \frac{\ln(2)}{2} \right)
$$
