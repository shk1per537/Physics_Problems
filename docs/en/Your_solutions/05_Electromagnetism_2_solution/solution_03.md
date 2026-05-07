## 3. Biot-Savart Law

We are calculating the magnitude of the magnetic field produced by a short segment of a current-carrying wire at a specific point in space. The fundamental formula for this is the Biot-Savart Law. For a small segment of length ($\Delta l$), the magnitude of the magnetic field ($\Delta B$) is:

$$
\Delta B = \frac{\mu_0}{4\pi} \cdot \frac{I \cdot \Delta l \cdot \sin(\theta)}{r^2}
$$

Where $\theta$ is the angle between the direction of the current segment and the vector pointing from the segment to the observation point P.

*Note: Because the problem specifies that the segment is perpendicular to the line connecting it to point P, the angle $\theta$ is $90^\circ$, and $\sin(90^\circ) = 1$. This simplifies our calculation and means the magnetic field contribution from this specific segment is at its maximum.*

---

### Part A: Setting up the Equation

**Given Constants:**
* Current ($I$) = 3 A
* Length of segment ($\Delta l$) = 0.1 m
* Distance to point P ($r$) = 0.2 m
* Angle ($\theta$) = $90^\circ$
* Vacuum permeability ($\mu_0$) = $4\pi \times 10^{-7} \text{ T}\cdot\text{m/A}$

First, let's look at the constant term $\frac{\mu_0}{4\pi}$. Because $\mu_0$ contains $4\pi$, this entire fraction conveniently simplifies to exactly $10^{-7} \text{ T}\cdot\text{m/A}$. Let's substitute all our known values into the Biot-Savart equation:

$$
\Delta B = 10^{-7} \cdot \frac{3 \cdot 0.1 \cdot \sin(90^\circ)}{(0.2)^2}
$$

### Part B: Calculating the Magnetic Field

Now we perform the arithmetic steps:

$$
\Delta B = 10^{-7} \cdot \frac{0.3 \cdot 1}{0.04}
$$

$$
\Delta B = 10^{-7} \cdot 7.5
$$

Writing this in standard scientific notation:

$$
\Delta B = 7.5 \times 10^{-7} \text{ T}
$$

### Final Answer

* The magnitude of the magnetic field at point P due to this short current segment is **$7.5 \times 10^{-7} \text{ T}$** (or $0.75 \text{ }\mu\text{T}$).
