## Superposition Principle

We are analyzing the interference of two identical waves traveling in opposite directions. According to the principle of superposition, the resultant wave displacement $y(x,t)$ is the algebraic sum of the individual wave displacements.

---

### Part A: Equation of the Standing Wave

**Given:**
* Wave 1 (traveling right): $y_1(x,t) = A\sin(kx - \omega t)$
* Wave 2 (traveling left): $y_2(x,t) = A\sin(kx + \omega t)$

To find the resultant wave, we add the two equations:

$$
y(x,t) = y_1(x,t) + y_2(x,t)
$$

$$
y(x,t) = A\sin(kx - \omega t) + A\sin(kx + \omega t)
$$

To simplify this, we can use the trigonometric sum-to-product identity:

$$
\sin(\alpha) + \sin(\beta) = 2 \sin\left(\frac{\alpha + \beta}{2}\right) \cos\left(\frac{\alpha - \beta}{2}\right)
$$

Let $\alpha = kx - \omega t$ and $\beta = kx + \omega t$:

1.  **Sum term:** $\frac{(kx - \omega t) + (kx + \omega t)}{2} = \frac{2kx}{2} = kx$
2.  **Difference term:** $\frac{(kx - \omega t) - (kx + \omega t)}{2} = \frac{-2\omega t}{2} = -\omega t$

Substitute these back into the identity:

$$
y(x,t) = A \cdot 2 \sin(kx) \cos(-\omega t)
$$

Since cosine is an even function ($\cos(-\theta) = \cos(\theta)$), we arrive at the final equation for the standing wave:

$$
y(x,t) = 2A \sin(kx) \cos(\omega t)
$$

*Note: In this equation, $2A\sin(kx)$ represents the amplitude of the wave at any position $x$, which varies spatially but is independent of time.*

---

### Part B: Positions of the Nodes

Nodes are positions on a standing wave where the displacement is always zero, regardless of time. This occurs when the spatial amplitude term equals zero:

$$
2A \sin(kx) = 0
$$

Since $2A \neq 0$, it must be that:

$$
\sin(kx) = 0
$$

The sine function equals zero at integer multiples of $\pi$:

$$
kx = n\pi \quad \text{where } n = 0, 1, 2, 3, \dots
$$

Recall that the wave number $k$ is defined in terms of wavelength ($\lambda$) as $k = \frac{2\pi}{\lambda}$. Substitute this into the equation:

$$
\left(\frac{2\pi}{\lambda}\right) x = n\pi
$$

Divide both sides by $\pi$:

$$
\frac{2x}{\lambda} = n
$$

Solve for $x$:

$$
x = \frac{n\lambda}{2}
$$

### Final Answer

* The equation of the resulting standing wave is **$y(x,t) = 2A \sin(kx) \cos(\omega t)$**.
* The nodes are located at positions **$x = \frac{n\lambda}{2}$** (where $n = 0, 1, 2, 3, \dots$). This means nodes occur at $x = 0, \frac{\lambda}{2}, \lambda, \frac{3\lambda}{2}$, and so on.
