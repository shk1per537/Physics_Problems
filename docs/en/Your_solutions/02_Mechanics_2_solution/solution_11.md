## 11. Dynamics with a time-dependent force

We are given a particle of mass $m = 3$ kg moving under a time-dependent force:
$$\vec{F}(t) = (15t)\mathbf{i} + (3t - 12)\mathbf{j} + (-6t^2)\mathbf{k}$$

**Initial Conditions (at $t = 0$):**
* Position: $\vec{r}_0 = (5, 2, -3)$ m
* Velocity: $\vec{v}_0 = (2, 0, 1)$ m/s

---

### Step 1: Find the acceleration $\vec{a}(t)$

Using Newton's Second Law ($\vec{F} = m\vec{a}$), we divide the force vector by the mass:
$$\vec{a}(t) = \frac{\vec{F}(t)}{m} = \frac{1}{3} \cdot [15t\mathbf{i} + (3t - 12)\mathbf{j} - 6t^2\mathbf{k}]$$
$$\vec{a}(t) = (5t)\mathbf{i} + (t - 4)\mathbf{j} + (-2t^2)\mathbf{k}$$

### Step 2: Find the velocity $\vec{v}(t)$

Velocity is the integral of acceleration. We integrate component by component:
* $v_x(t) = \int 5t \, dt = \frac{5}{2}t^2 + C_{v1}$
* $v_y(t) = \int (t - 4) \, dt = \frac{1}{2}t^2 - 4t + C_{v2}$
* $v_z(t) = \int -2t^2 \, dt = -\frac{2}{3}t^3 + C_{v3}$

Apply initial conditions $\vec{v}_0 = (2, 0, 1)$ at $t = 0$:
* $v_x(0) = 2 \implies C_{v1} = 2$
* $v_y(0) = 0 \implies C_{v2} = 0$
* $v_z(0) = 1 \implies C_{v3} = 1$

**Velocity Result:**
$$\vec{v}(t) = (2.5t^2 + 2)\mathbf{i} + (0.5t^2 - 4t)\mathbf{j} + (-\frac{2}{3}t^3 + 1)\mathbf{k}$$

### Step 3: Find the position $\vec{r}(t)$

Position is the integral of velocity:
* $x(t) = \int (2.5t^2 + 2) \, dt = \frac{5}{6}t^3 + 2t + C_{r1}$
* $y(t) = \int (0.5t^2 - 4t) \, dt = \frac{1}{6}t^3 - 2t^2 + C_{r2}$
* $z(t) = \int (-\frac{2}{3}t^3 + 1) \, dt = -\frac{1}{6}t^4 + t + C_{r3}$

Apply initial conditions $\vec{r}_0 = (5, 2, -3)$ at $t = 0$:
* $x(0) = 5 \implies C_{r1} = 5$
* $y(0) = 2 \implies C_{r2} = 2$
* $z(0) = -3 \implies C_{r3} = -3$

**Position Result:**
$$\vec{r}(t) = (\frac{5}{6}t^3 + 2t + 5)\mathbf{i} + (\frac{1}{6}t^3 - 2t^2 + 2)\mathbf{j} + (-\frac{1}{6}t^4 + t - 3)\mathbf{k}$$
