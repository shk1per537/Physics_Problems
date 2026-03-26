## 7. Elimination of time and interpretation of acceleration

We are given the path equations in parametric form:

$$
x(t) = 2t^2, \qquad y(t) = 3t^3
$$

---

### Step 1: Eliminate the parameter $t$

To find the direct relationship between $x$ and $y$ (the Cartesian equation of the trajectory), we need to eliminate $t$. 

First, solve for $t^2$ using the $x(t)$ equation:

$$
x = 2t^2 \implies t^2 = \frac{x}{2}
$$

Now, let's look at the $y(t)$ equation. To make substitution easier, we can square both equations to match the powers of $t$:

$$
x^3 = (2t^2)^3 = 8t^6
$$

$$
y^2 = (3t^3)^2 = 9t^6
$$

Now, solve both for $t^6$:

$$
t^6 = \frac{x^3}{8} \qquad \text{and} \qquad t^6 = \frac{y^2}{9}
$$

Set them equal to each other:

$$
\frac{x^3}{8} = \frac{y^2}{9}
$$

$$
9x^3 = 8y^2
$$

This is the equation of the trajectory, which takes the shape of a semi-cubical parabola.

### Step 2: Draw the trajectory

<img width="871" height="692" alt="image" src="https://github.com/user-attachments/assets/e8cda2a6-50fd-41c5-8f60-722bc745f456" />

### Step 3: Calculate velocity and acceleration vectors

The position vector is $\vec{r}(t) = 2t^2\hat{i} + 3t^3\hat{j}$.

**1. Velocity vector $\vec{v}(t)$:**
Take the first derivative of the position vector:

$$
\vec{v}(t) = \frac{d\vec{r}}{dt} = \frac{d}{dt}(2t^2)\hat{i} + \frac{d}{dt}(3t^3)\hat{j}
$$

$$
\vec{v}(t) = 4t\hat{i} + 9t^2\hat{j}
$$

**2. Magnitude of velocity $|\vec{v}(t)|$ (Speed):**

$$
|\vec{v}(t)| = \sqrt{(4t)^2 + (9t^2)^2} = \sqrt{16t^2 + 81t^4}
$$

$$
|\vec{v}(t)| = t\sqrt{16 + 81t^2}
$$

**3. Acceleration vector $\vec{a}(t)$:**
Take the derivative of the velocity vector:

$$
\vec{a}(t) = \frac{d\vec{v}}{dt} = \frac{d}{dt}(4t)\hat{i} + \frac{d}{dt}(9t^2)\hat{j}
$$

$$
\vec{a}(t) = 4\hat{i} + 18t\hat{j}
$$

**4. Magnitude of acceleration $|\vec{a}(t)|$:**

$$
|\vec{a}(t)| = \sqrt{4^2 + (18t)^2} = \sqrt{16 + 324t^2}
$$

$$
|\vec{a}(t)| = 2\sqrt{4 + 81t^2}
$$

### Step 4: Is the acceleration constant?

No, the acceleration is **not constant**. 

While the horizontal ($\hat{i}$) component of acceleration is a constant $4$, the vertical ($\hat{j}$) component is $18t$. Because the vertical component depends on the variable $t$, the overall acceleration vector changes magnitude and direction as time passes.
