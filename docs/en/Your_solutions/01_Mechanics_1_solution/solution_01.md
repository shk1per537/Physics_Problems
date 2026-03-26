## 1. Projectile Motion

We are given a projectile fired with an initial velocity $v_0 = 100$ m/s at an angle $\theta = 37^\circ$ above the horizontal. We will assume the acceleration due to gravity is $g = 9.8$ m/s² and that there is no air resistance.

First, let's establish the initial velocity components:
* Horizontal: $v_{0x} = v_0 \cos(37^\circ) \approx 100 \cdot 0.7986 = 79.86$ m/s
* Vertical: $v_{0y} = v_0 \sin(37^\circ) \approx 100 \cdot 0.6018 = 60.18$ m/s

---

### a) Derive the differential equations of motion

According to Newton's Second Law, $\Sigma \vec{F} = m\vec{a}$. Since we are ignoring air resistance, the only force acting on the projectile is gravity, which pulls straight down.

**In the horizontal ($x$) direction:**
There are no forces acting horizontally.

$$
\Sigma F_x = 0 \implies m \frac{d^2x}{dt^2} = 0
$$

Dividing by mass $m$, we get the horizontal differential equation:

$$
\frac{d^2x}{dt^2} = 0
$$

**In the vertical ($y$) direction:**
The only force is gravity, acting downwards (negative direction).

$$
\Sigma F_y = -mg \implies m \frac{d^2y}{dt^2} = -mg
$$

Dividing by mass $m$, we get the vertical differential equation:

$$
\frac{d^2y}{dt^2} = -g
$$

### b) Determine the time of flight

To find the time of flight ($T$), we need the equation for the vertical position $y(t)$. By integrating the vertical differential equation twice, we get:

$$
y(t) = v_{0y}t - \frac{1}{2}gt^2
$$

The projectile hits the ground when $y(t) = 0$. We set the equation to zero and solve for $t$:

$$
0 = t \left( v_{0y} - \frac{1}{2}gt \right)
$$

Since $t = 0$ is the launch time, the time of flight $T$ is when the term inside the parentheses equals zero:

$$
\frac{1}{2}gT = v_{0y} \implies T = \frac{2v_{0y}}{g}
$$

Substituting our known values:

$$
T = \frac{2(60.18)}{9.8} \approx 12.28 \text{ seconds}
$$

### c) Determine the maximum height

Maximum height ($H$) occurs when the vertical velocity reaches zero (the peak of the trajectory). Integrating the vertical acceleration once gives the vertical velocity equation:

$$
v_y(t) = v_{0y} - gt
$$

Set $v_y(t) = 0$ to find the time it takes to reach the peak ($t_{peak}$):

$$
0 = v_{0y} - g t_{peak} \implies t_{peak} = \frac{v_{0y}}{g}
$$

Now, substitute $t_{peak}$ into the vertical position equation to find $H$:

$$
H = v_{0y}\left(\frac{v_{0y}}{g}\right) - \frac{1}{2}g\left(\frac{v_{0y}}{g}\right)^2 = \frac{v_{0y}^2}{2g}
$$

Substituting our known values:

$$
H = \frac{(60.18)^2}{2(9.8)} = \frac{3621.63}{19.6} \approx 184.78 \text{ meters}
$$

### d) Determine the range

The range ($R$) is the total horizontal distance traveled during the time of flight ($T$). Integrating the horizontal differential equation twice gives the horizontal position equation:

$$
x(t) = v_{0x}t
$$

Substitute the total time of flight $T$ into this equation:

$$
R = x(T) = v_{0x} \cdot T
$$

Substituting our known values:

$$
R = 79.86 \cdot 12.28 \approx 980.68 \text{ meters}
$$

*(Note: If your specific textbook standardizes $\sin(37^\circ) = 0.6$ and $\cos(37^\circ) = 0.8$ exactly for simplicity, the components would be exactly 60 m/s and 80 m/s, yielding $T \approx 12.24$ s, $H \approx 183.67$ m, and $R \approx 979.59$ m).*
