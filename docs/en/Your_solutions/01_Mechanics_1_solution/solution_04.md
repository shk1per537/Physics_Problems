## 4. Vector Calculus

We are given the position vector of an object as a function of time $t$:

$$
\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}
$$

We need to find the velocity vector $\vec{v}(t)$ and the acceleration vector $\vec{a}(t)$.

---

### Step 1: Find the velocity vector $\vec{v}(t)$

Velocity is the rate of change of position with respect to time. Therefore, we find the velocity vector by taking the first derivative of the position vector $\vec{r}(t)$:

$$
\vec{v}(t) = \frac{d\vec{r}}{dt}
$$

We differentiate the $\hat{i}$ and $\hat{j}$ components separately:

* For the $\hat{i}$ component: $\frac{d}{dt}(3t^2) = 6t$
* For the $\hat{j}$ component: $\frac{d}{dt}(5t - 8t^2) = 5 - 16t$

Combining these gives the velocity vector:

$$
\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}
$$

### Step 2: Find the acceleration vector $\vec{a}(t)$

Acceleration is the rate of change of velocity with respect to time. We find the acceleration vector by taking the derivative of the velocity vector $\vec{v}(t)$ (which is the second derivative of the position vector):

$$
\vec{a}(t) = \frac{d\vec{v}}{dt}
$$

Again, we differentiate the components separately:

* For the $\hat{i}$ component: $\frac{d}{dt}(6t) = 6$
* For the $\hat{j}$ component: $\frac{d}{dt}(5 - 16t) = -16$

Combining these gives the acceleration vector:

$$
\vec{a}(t) = 6\hat{i} - 16\hat{j}
$$

### Final Answer

The object's velocity and acceleration vectors as a function of time are:

$$
\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}
$$

$$
\vec{a}(t) = 6\hat{i} - 16\hat{j}
$$
