## 10. Force Field and Power

We are analyzing a particle of mass $m = 0.5$ kg moving in a 3D force field with position equations:
$$x(t) = 5t^2 - t, \quad y(t) = 2t^3, \quad z(t) = -3t + 2$$

---

### 1. Particle Velocity $\vec{v}(t)$
Velocity is the first derivative of the position components:
* $v_x = \frac{dx}{dt} = 10t - 1$
* $v_y = \frac{dy}{dt} = 6t^2$
* $v_z = \frac{dz}{dt} = -3$

$$\vec{v}(t) = (10t - 1)\mathbf{i} + (6t^2)\mathbf{j} - 3\mathbf{k}$$

### 2. Particle Momentum $\vec{p}(t)$
Momentum is defined as mass times velocity ($\vec{p} = m\vec{v}$):
$$\vec{p}(t) = 0.5 \cdot [(10t - 1)\mathbf{i} + (6t^2)\mathbf{j} - 3\mathbf{k}]$$
$$\vec{p}(t) = (5t - 0.5)\mathbf{i} + (3t^2)\mathbf{j} - 1.5\mathbf{k}$$

### 3. Particle Acceleration $\vec{a}(t)$
Acceleration is the derivative of the velocity components:
* $a_x = \frac{dv_x}{dt} = 10$
* $a_y = \frac{dv_y}{dt} = 12t$
* $a_z = \frac{dv_z}{dt} = 0$

$$\vec{a}(t) = 10\mathbf{i} + 12t\mathbf{j} + 0\mathbf{k}$$

### 4. Force Acting on the Particle $\vec{F}(t)$
Using Newton's Second Law ($\vec{F} = m\vec{a}$):
$$\vec{F}(t) = 0.5 \cdot [10\mathbf{i} + 12t\mathbf{j}]$$
$$\vec{F}(t) = 5\mathbf{i} + 6t\mathbf{j}$$

### 5. Power Transferred by the Field $P(t)$
Power is the dot product of force and velocity ($P = \vec{F} \cdot \vec{v}$):
$$P(t) = (5\mathbf{i} + 6t\mathbf{j} + 0\mathbf{k}) \cdot ((10t - 1)\mathbf{i} + (6t^2)\mathbf{j} - 3\mathbf{k})$$
$$P(t) = 5(10t - 1) + 6t(6t^2) + 0(-3)$$
$$P(t) = 50t - 5 + 36t^3$$

**Final Result:** $P(t) = 36t^3 + 50t - 5$
