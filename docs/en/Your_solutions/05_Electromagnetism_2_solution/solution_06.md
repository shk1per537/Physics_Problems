## 6. EM Wave Analysis

We are extracting the physical properties of an electromagnetic wave directly from its mathematical wave function. The general equation for the electric field of a plane harmonic wave is:

$$
E(x,t) = E_0 \cdot \sin(kx - \omega t)
$$

By comparing our specific equation, $E_y(x,t) = 100\sin(10^7x - \omega t)$, to this standard form, we can identify the amplitude ($E_0 = 100 \text{ V/m}$) and the wave number ($k = 10^7 \text{ rad/m}$). We will assume the wave is traveling in a vacuum, meaning its speed is the speed of light ($c \approx 3 \times 10^8 \text{ m/s}$).

---

### Part A: Direction of Propagation

The argument of the sine function is the phase of the wave: $(10^7x - \omega t)$. 
* The variable $x$ tells us the wave is propagating along the **x-axis**.
* The negative sign ($-$) between the spatial ($kx$) and temporal ($\omega t$) terms indicates that the wave is moving in the **positive** direction.

Therefore, the wave propagates in the **$+x$ direction**.

### Part B: Wavelength and Angular Frequency

**1. Wavelength ($\lambda$):**
The wave number ($k$) is related to the wavelength by the formula $k = \frac{2\pi}{\lambda}$. Rearranging to solve for $\lambda$:

$$
\lambda = \frac{2\pi}{k}
$$

$$
\lambda = \frac{2\pi}{10^7} \approx 6.28 \times 10^{-7} \text{ m} \text{ (or 628 nm)}
$$

**2. Angular Frequency ($\omega$):**
The speed of the wave ($c$) is the ratio of its angular frequency to its wave number ($c = \frac{\omega}{k}$). Solving for $\omega$:

$$
\omega = c \cdot k
$$

$$
\omega = (3 \times 10^8 \text{ m/s}) \cdot (10^7 \text{ rad/m})
$$

$$
\omega = 3 \times 10^{15} \text{ rad/s}
$$

### Part C: The Magnetic Field Equation

In an electromagnetic wave, the electric and magnetic fields are always in phase, mutually perpendicular, and their magnitudes are related by the speed of light:

$$
B_0 = \frac{E_0}{c}
$$

Let's find the magnetic field amplitude ($B_0$):

$$
B_0 = \frac{100}{3 \times 10^8} \approx 3.33 \times 10^{-7} \text{ T}
$$

Now we must determine the axis of oscillation. The direction of propagation ($\vec{S}$) is given by the cross product of the field directions: $\vec{E} \times \vec{B}$.
* Propagation is in $+x$ ($\hat{i}$).
* The electric field $E_y$ is in $+y$ ($\hat{j}$).
* Since $\hat{j} \times \hat{k} = \hat{i}$, the magnetic field must oscillate along the **z-axis** ($\hat{k}$).

Combining the amplitude, the axis, and the exact same phase block, we get the magnetic field equation:

$$
B_z(x,t) = 3.33 \times 10^{-7} \sin(10^7x - 3 \times 10^{15} t) \text{ T}
$$

### Final Answer

* **Direction of propagation:** Along the positive x-axis ($+x$).
* **Wavelength ($\lambda$):** Approximately **$6.28 \times 10^{-7} \text{ m}$**.
* **Angular frequency ($\omega$):** **$3 \times 10^{15} \text{ rad/s}$**.
* **Magnetic field component:** **$B_z(x,t) = 3.33 \times 10^{-7} \sin(10^7x - 3 \times 10^{15} t) \text{ T}$**.
