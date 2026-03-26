## 2. Range Optimization

We are given the range formula for projectile motion:

$$
R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}
$$

We need to analytically show that the maximum range is achieved when the launch angle $\theta = 45^\circ$.

---

### Step 1: Analyze the variables

For a given projectile, the initial velocity $v_0$ and the acceleration due to gravity $g$ are constant. Therefore, the range $R(\theta)$ depends entirely on the trigonometric part of the equation: $\sin(2\theta)$.

To maximize the overall range $R(\theta)$, we must maximize the value of $\sin(2\theta)$.

### Step 2: Find the maximum value of the sine function

From basic trigonometry, we know that the maximum possible value of the sine function for any angle is $1$:

$$
\sin(2\theta) = 1
$$

### Step 3: Solve for $\theta$

The angle whose sine is $1$ is $90^\circ$ (or $\frac{\pi}{2}$ radians). Therefore, we can set the argument inside the sine function equal to $90^\circ$:

$$
2\theta = 90^\circ
$$

Divide both sides by $2$ to isolate $\theta$:

$$
\theta = 45^\circ
$$

### Alternative Method (Using Calculus)

We can also prove this by taking the first derivative of the range function with respect to $\theta$ and setting it to zero to find the critical point:

$$
R'(\theta) = \frac{d}{d\theta} \left( \frac{v_0^2 \sin(2\theta)}{g} \right) = \frac{v_0^2}{g} \cdot \cos(2\theta) \cdot 2 = \frac{2v_0^2}{g} \cos(2\theta)
$$

Set the derivative to zero:

$$
\frac{2v_0^2}{g} \cos(2\theta) = 0
$$

Since the constants $\frac{2v_0^2}{g}$ cannot equal zero, the cosine term must be zero:

$$
\cos(2\theta) = 0
$$

In the first quadrant (since we are launching upwards), the angle whose cosine is $0$ is $90^\circ$:

$$
2\theta = 90^\circ \implies \theta = 45^\circ
$$

### Final Answer

Both logical and calculus-based analytical methods prove that for a given initial velocity, the maximum range is achieved at a launch angle of **$45^\circ$**.
