## 3. Conservation of Energy

We have a simple pendulum and need to find its maximum speed at the lowest point of its swing. 

**Given:**
* Length of the pendulum ($L$) = 1.0 m
* Initial release angle ($\theta$) = 15°
* Acceleration due to gravity ($g$) $\approx 9.8$ m/s²

---

### Step 1: Determine the change in height ($h$)

When the pendulum is pulled back to an angle $\theta$, it rises by a vertical distance $h$. We can find this height using trigonometry. 

The vertical distance from the pivot to the bob at angle $\theta$ is $L\cos(\theta)$. 
The total length of the string is $L$. Therefore, the height $h$ the bob has been lifted relative to its lowest point is:

$$
h = L - L\cos(\theta) = L(1 - \cos(\theta))
$$

Substitute the known values:

$$
h = 1.0 \cdot (1 - \cos(15^\circ))
$$

> **Note:** $\cos(15^\circ) \approx 0.9659$

$$
h = 1.0 \cdot (1 - 0.9659) = 0.0341 \text{ m}
$$

### Step 2: Apply conservation of energy

At the highest point of the swing (the release point), the pendulum momentarily has zero kinetic energy and maximum potential energy. At the lowest point, all that potential energy has been converted into kinetic energy.

According to the law of conservation of energy:
$$
\text{Initial Potential Energy} = \text{Final Kinetic Energy}
$$

$$
mgh = \frac{1}{2}mv^2
$$

Notice that the mass ($m$) appears on both sides of the equation, so it cancels out. This means the speed doesn't depend on how heavy the pendulum is!

$$
gh = \frac{1}{2}v^2
$$

### Step 3: Solve for the final velocity ($v$)

Rearrange the equation to solve for $v$:

$$
v^2 = 2gh
$$

$$
v = \sqrt{2gh}
$$

Now, substitute our values for $g$ and $h$:

$$
v = \sqrt{2 \cdot 9.8 \cdot 0.0341}
$$

$$
v = \sqrt{0.66836} \approx 0.817
$$

### Final Answer

The speed of the pendulum bob at the bottom of its swing is approximately **0.817 m/s**.
