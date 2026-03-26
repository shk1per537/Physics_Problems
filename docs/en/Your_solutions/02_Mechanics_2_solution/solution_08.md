## 8. Work of a Variable Force

We are given a one-dimensional conservative force:
$$F(x) = -kx$$
where $k$ is a positive constant (Hooke's Law).

---

### 1. Equation of Motion and its Solution

According to Newton's Second Law, $F = ma$:
$$m\frac{d^2x}{dt^2} = -kx \implies m\ddot{x} + kx = 0$$

Dividing by $m$ and defining $\omega^2 = \frac{k}{m}$:
$$\ddot{x} + \omega^2 x = 0$$

This is the differential equation for a Simple Harmonic Oscillator. The general solution is:
$$x(t) = A\cos(\omega t + \phi)$$
where $A$ is the amplitude and $\phi$ is the phase constant.

### 2. Work done from $0$ to $x_0$

Work is the integral of force over displacement:
$$W = \int_{0}^{x_0} F(x) \, dx = \int_{0}^{x_0} (-kx) \, dx$$

Integrating:
$$W = \left[ -\frac{1}{2}kx^2 \right]_{0}^{x_0} = -\frac{1}{2}kx_0^2$$

> **Note:** The work is negative because the force is directed opposite to the displacement.

### 3. Interpretation as Potential Energy

For a conservative force, the change in potential energy ($\Delta U$) is defined as the negative of the work done by that force:
$$\Delta U = -W = -\left( -\frac{1}{2}kx^2 \right) = \frac{1}{2}kx^2$$

Assuming the potential energy at the origin is zero ($U(0) = 0$), the potential energy function is:
$$U(x) = \frac{1}{2}kx^2$$

### 4. Verify the relationship $F = -\frac{dU}{dx}$

We take the negative derivative of our potential energy function:
$$-\frac{dU}{dx} = -\frac{d}{dx}\left( \frac{1}{2}kx^2 \right) = -(k \cdot x) = -kx$$

Since this matches our original force $F(x) = -kx$, the relationship is verified.

### 5. Graphs of $F(x)$ and $U(x)$

* **$F(x) = -kx$:** A straight line passing through the origin with a negative slope.
* **$U(x) = \frac{1}{2}kx^2$:** A parabola opening upwards with its vertex at the origin.
<img width="1189" height="490" alt="image" src="https://github.com/user-attachments/assets/1f0417b5-0a66-40ee-bfe6-55a3d9a2083d" />
