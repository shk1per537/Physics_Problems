## 8. Waves

We need to determine which of the given functions can mathematically describe a traveling wave. To do this, we will follow the hint and check if each function satisfies the linear one-dimensional wave equation:

$$
\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2 y}{\partial t^2}
$$

Any function of the form $f(x - vt)$ or $f(x + vt)$ will satisfy this equation, provided it is twice differentiable. Let's test the second-order partial derivatives for each option.

---

### Option a) $y(x,t) = A\cos(kx^2 - \omega t)$

First, find the second partial derivative with respect to $x$:

$$
\frac{\partial y}{\partial x} = -A\sin(kx^2 - \omega t) \cdot (2kx) = -2Akx \sin(kx^2 - \omega t)
$$

$$
\frac{\partial^2 y}{\partial x^2} = -2Ak \sin(kx^2 - \omega t) - 4Ak^2x^2 \cos(kx^2 - \omega t)
$$

Next, find the second partial derivative with respect to $t$:

$$
\frac{\partial y}{\partial t} = -A\sin(kx^2 - \omega t) \cdot (-\omega) = A\omega \sin(kx^2 - \omega t)
$$

$$
\frac{\partial^2 y}{\partial t^2} = -A\omega^2 \cos(kx^2 - \omega t)
$$

Comparing the two second derivatives, it is clear that $\frac{\partial^2 y}{\partial x^2}$ is not simply proportional to $\frac{\partial^2 y}{\partial t^2}$ by a constant factor of $1/v^2$ (because of the extra variables $x$ and mixed terms). Therefore, this function **does not** satisfy the wave equation.

### Option b) $y(x,t) = A(x - vt)^2$

First, find the second partial derivative with respect to $x$:

$$
\frac{\partial y}{\partial x} = 2A(x - vt) \cdot (1) = 2A(x - vt)
$$

$$
\frac{\partial^2 y}{\partial x^2} = 2A
$$

Next, find the second partial derivative with respect to $t$:

$$
\frac{\partial y}{\partial t} = 2A(x - vt) \cdot (-v) = -2Av(x - vt)
$$

$$
\frac{\partial^2 y}{\partial t^2} = -2Av(-v) = 2Av^2
$$

Now substitute these back into the wave equation:

$$
2A = \frac{1}{v^2} (2Av^2)
$$

$$
2A = 2A
$$

The left side equals the right side, so this function **does** satisfy the wave equation.

### Option c) $y(x,t) = A\log(x + vt)$

First, find the second partial derivative with respect to $x$:

$$
\frac{\partial y}{\partial x} = \frac{A}{x + vt} \cdot (1) = A(x + vt)^{-1}
$$

$$
\frac{\partial^2 y}{\partial x^2} = -A(x + vt)^{-2} = -\frac{A}{(x + vt)^2}
$$

Next, find the second partial derivative with respect to $t$:

$$
\frac{\partial y}{\partial t} = \frac{A}{x + vt} \cdot (v) = Av(x + vt)^{-1}
$$

$$
\frac{\partial^2 y}{\partial t^2} = -Av(x + vt)^{-2} \cdot (v) = -\frac{Av^2}{(x + vt)^2}
$$

Now substitute these back into the wave equation:

$$
-\frac{A}{(x + vt)^2} = \frac{1}{v^2} \left( -\frac{Av^2}{(x + vt)^2} \right)
$$

$$
-\frac{A}{(x + vt)^2} = -\frac{A}{(x + vt)^2}
$$

The left side equals the right side, so this function also **does** satisfy the wave equation.

### Final Answer

* **Functions b) and c)** satisfy the wave equation.
* Both $y(x,t) = A(x - vt)^2$ and $y(x,t) = A\log(x + vt)$ are of the form $f(x \pm vt)$, making them valid mathematical solutions for a traveling wave.
