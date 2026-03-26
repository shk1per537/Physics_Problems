## 12. Work and Energy with a Constant Force

We are analyzing a body of mass $m = 2$ kg under a constant force $\vec{F} = [6, 2]$ N.

**Initial Conditions (at $t = 0$):**
* Position: $\vec{r}(0) = [0, 0]$ m
* Velocity: $\vec{v}(0) = [1, -1]$ m/s

---

### 1. Determine $\vec{a}(t)$
Using Newton's Second Law ($\vec{F} = m\vec{a}$):
$$\vec{a} = \frac{\vec{F}}{m} = \frac{[6, 2]}{2} = [3, 1] \text{ m/s}^2$$
Since the force is constant, the acceleration is also constant.

### 2. Determine $\vec{v}(t)$
Velocity is the integral of acceleration:
$$\vec{v}(t) = \int \vec{a} \, dt + \vec{v}_0 = [3t, t] + [1, -1]$$
$$\vec{v}(t) = [3t + 1, t - 1] \text{ m/s}$$

### 3. Determine $\vec{r}(t)$
Position is the integral of velocity:
$$\vec{r}(t) = \int \vec{v}(t) \, dt + \vec{r}_0 = \left[ \frac{3}{2}t^2 + t, \frac{1}{2}t^2 - t \right] + [0, 0]$$
$$\vec{r}(t) = [1.5t^2 + t, 0.5t^2 - t] \text{ m}$$

### 4. Calculate Work Done at $t = 3$ s
Work done by a constant force is the dot product of force and displacement ($W = \vec{F} \cdot \Delta\vec{r}$).

At $t = 3$ s:
* $x(3) = 1.5(3)^2 + 3 = 13.5 + 3 = 16.5$ m
* $y(3) = 0.5(3)^2 - 3 = 4.5 - 3 = 1.5$ m
* $\Delta\vec{r} = [16.5, 1.5]$ m

$$W = [6, 2] \cdot [16.5, 1.5] = 6(16.5) + 2(1.5) = 99 + 3 = 102 \text{ J}$$

### 5. Check Consistency with the Work-Energy Theorem
The Work-Energy Theorem states that $W = \Delta K = K_f - K_i$.

* **Initial Kinetic Energy ($K_i$):**
$$K_i = \frac{1}{2}m|\vec{v}_0|^2 = \frac{1}{2}(2)(1^2 + (-1)^2) = 2 \text{ J}$$

* **Final Velocity at $t = 3$ s:**
$$\vec{v}(3) = [3(3) + 1, 3 - 1] = [10, 2] \text{ m/s}$$
$$|\vec{v}(3)|^2 = 10^2 + 2^2 = 104$$

* **Final Kinetic Energy ($K_f$):**
$$K_f = \frac{1}{2}m|\vec{v}(3)|^2 = \frac{1}{2}(2)(104) = 104 \text{ J}$$

* **Change in Kinetic Energy ($\Delta K$):**
$$\Delta K = 104 - 2 = 102 \text{ J}$$

> **Conclusion:** Since $W = 102 \text{ J}$ and $\Delta K = 102 \text{ J}$, the results are consistent with the Work-Energy Theorem.
