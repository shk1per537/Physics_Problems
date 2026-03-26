## 1. Gravitational Dependence

We are analyzing the behavior of a simple pendulum under different gravitational conditions. The formula for the period of a simple pendulum is:

$$
T = 2\pi \sqrt{\frac{L}{g}}
$$

where $T$ is the period, $L$ is the length of the string, and $g$ is the acceleration due to gravity.

---

### Part A: Period on the Moon

**Given:**
* Period on Earth ($T_E$) = 4 s
* Gravity on the Moon ($g_M$) = $\frac{1}{6} g_E$

We need to find the period on the Moon ($T_M$). Let's set up the equation for the Moon:

$$
T_M = 2\pi \sqrt{\frac{L}{g_M}}
$$

Substitute $g_M$ with $\frac{g_E}{6}$:

$$
T_M = 2\pi \sqrt{\frac{L}{\frac{g_E}{6}}}
$$

Simplify the fraction inside the square root:

$$
T_M = 2\pi \sqrt{\frac{6L}{g_E}} = \sqrt{6} \cdot \left( 2\pi \sqrt{\frac{L}{g_E}} \right)
$$

Notice that the term in the parentheses is exactly the formula for the period on Earth ($T_E$). Therefore, we can substitute $T_E$ into the equation:

$$
T_M = \sqrt{6} \cdot T_E
$$

$$
T_M = \sqrt{6} \cdot 4 \approx 2.449 \cdot 4 \approx 9.80 \text{ seconds}
$$

### Part B: Length for a 1-second period on Earth

**Given:**
* Desired period ($T$) = 1 s
* Gravity on Earth ($g$) $\approx 9.8 \text{ m/s}^2$

We need to rearrange the period formula to solve for length ($L$):

$$
T = 2\pi \sqrt{\frac{L}{g}}
$$

Divide by $2\pi$:

$$
\frac{T}{2\pi} = \sqrt{\frac{L}{g}}
$$

Square both sides:

$$
\frac{T^2}{4\pi^2} = \frac{L}{g}
$$

Multiply by $g$:

$$
L = \frac{g T^2}{4\pi^2}
$$

Now, substitute the known values:

$$
L = \frac{9.8 \cdot (1)^2}{4\pi^2}
$$

$$
L \approx \frac{9.8}{39.478} \approx 0.248 \text{ meters}
$$

### Final Answer

* The period of the pendulum on the Moon would be approximately **9.80 seconds**.
* To have a period of exactly 1 second on Earth, the pendulum must be approximately **0.248 meters (or 24.8 cm)** long.
