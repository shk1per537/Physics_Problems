## 2. Harmonic Motion

We are given a mass-spring system oscillating with simple harmonic motion.

**Given:**
* Mass ($m$) = 10 kg
* Position function: $x(t) = 0.2\cos(10\pi t)$ (in meters)

---

### Step 1: Extract variables from the equation

The standard equation for simple harmonic motion is:

$$
x(t) = A\cos(\omega t)
$$

By comparing our given equation $x(t) = 0.2\cos(10\pi t)$ to the standard form, we can clearly identify two key parameters:
* Amplitude ($A$) = 0.2 m
* Angular frequency ($\omega$) = $10\pi$ rad/s

### Step 2: Find the spring constant ($k$)

The angular frequency of a mass-spring system is defined by its mass and the stiffness of the spring (the spring constant). The formula is:

$$
\omega = \sqrt{\frac{k}{m}}
$$

We can rearrange this equation to solve for $k$ by squaring both sides and multiplying by $m$:

$$
\omega^2 = \frac{k}{m} \implies k = m\omega^2
$$

Now, substitute our known values:

$$
k = 10 \cdot (10\pi)^2
$$

$$
k = 10 \cdot 100\pi^2 = 1000\pi^2
$$

> **Note:** $1000\pi^2 \approx 9869.6$ N/m

### Step 3: Find the total mechanical energy ($E$)

Assuming no friction, the total mechanical energy in a simple harmonic oscillator is conserved. It is equal to the maximum potential energy stored in the spring when it is fully stretched to its amplitude ($A$):

$$
E = \frac{1}{2}kA^2
$$

Substitute our calculated values for $k$ and $A$:

$$
E = \frac{1}{2}(1000\pi^2)(0.2)^2
$$

$$
E = 500\pi^2 \cdot 0.04
$$

$$
E = 20\pi^2
$$

> **Note:** $20\pi^2 \approx 197.4$ J

### Final Answer

* The spring constant $k$ is **$1000\pi^2$ N/m** (approx. 9869.6 N/m).
* The total mechanical energy is **$20\pi^2$ Joules** (approx. 197.4 J).
