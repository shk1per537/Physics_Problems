## 4. Energy & Momentum

We need to solve this problem in two distinct phases: first, finding the speed of the sliding block at the bottom of the track using conservation of energy, and second, finding the final combined speed using conservation of momentum.

**Given:**
* Mass of sliding block ($m_1$) = 0.5 kg
* Initial height ($h$) = 3.0 m
* Mass of stationary block ($m_2$) = 1.5 kg
* Acceleration due to gravity ($g$) $\approx 9.8$ m/s²

---

### Step 1: Conservation of Energy (Sliding down)

As the first block slides down the frictionless track, all of its initial gravitational potential energy turns into kinetic energy at the bottom.

$$
m_1gh = \frac{1}{2}m_1v_1^2
$$

Because $m_1$ is on both sides, it cancels out. We can rearrange the equation to solve for the velocity of the first block just before the collision ($v_1$):

$$
v_1 = \sqrt{2gh}
$$

Substitute the known values:

$$
v_1 = \sqrt{2 \cdot 9.8 \cdot 3.0} = \sqrt{58.8} 
$$

> **Note:** $v_1 \approx 7.668$ m/s

### Step 2: Conservation of Momentum (The collision)

When the sliding block hits the stationary block and they stick together, it is a perfectly inelastic collision. Kinetic energy is lost in the crash, but **momentum is conserved**.

$$
\text{Initial Momentum} = \text{Final Momentum}
$$

$$
m_1v_1 + m_2(0) = (m_1 + m_2)v_f
$$

Since the second block is initially at rest, its starting momentum is zero. The equation simplifies to:

$$
m_1v_1 = (m_1 + m_2)v_f
$$

### Step 3: Solve for the final velocity ($v_f$)

Rearrange the momentum equation to isolate $v_f$:

$$
v_f = \frac{m_1v_1}{m_1 + m_2}
$$

Substitute all our known values (using the exact square root for accuracy):

$$
v_f = \frac{0.5 \cdot \sqrt{58.8}}{0.5 + 1.5}
$$

$$
v_f = \frac{0.5 \cdot 7.668}{2.0}
$$

$$
v_f = \frac{3.834}{2.0} = 1.917
$$

### Final Answer

The speed of the combined mass just after the collision is approximately **1.917 m/s**.
