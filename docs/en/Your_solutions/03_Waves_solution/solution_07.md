## 7. Cyclotron Motion

We are determining the radius of the circular path an electron takes after being accelerated by an electric potential and then entering a uniform magnetic field. This problem is solved in two distinct stages. 

First, the electric potential energy is converted into kinetic energy to give the electron its velocity. The fundamental formula for this energy conservation is:

$$
e \cdot \Delta V = \frac{1}{2} m \cdot v^2
$$

Second, when the moving electron enters the uniform magnetic field perpendicularly, the magnetic force acts as a centripetal force, forcing it into a circular path. The formula balancing these forces is:

$$
e \cdot v \cdot B = \frac{m \cdot v^2}{r}
$$

*Note: The magnetic force always acts perpendicular to the velocity vector. This is why it continuously changes the electron's direction (causing circular motion) but does not change its actual speed.*

---

### Part A: Velocity of the Electron

**Given Constants:**
* Potential difference ($\Delta V$) = 5000 V
* Mass of an electron ($m_e$) $\approx 9.11 \times 10^{-31} \text{ kg}$
* Elementary charge ($e$) $\approx 1.60 \times 10^{-19} \text{ C}$

First, let's rearrange the energy conservation formula to solve for the electron's velocity ($v$):

$$
v = \sqrt{\frac{2 \cdot e \cdot \Delta V}{m_e}}
$$

Substitute the known values into the equation:

$$
v = \sqrt{\frac{2 \cdot (1.60 \times 10^{-19}) \cdot 5000}{9.11 \times 10^{-31}}}
$$

$$
v = \sqrt{\frac{1.60 \times 10^{-15}}{9.11 \times 10^{-31}}}
$$

$$
v \approx \sqrt{1.756 \times 10^{15}} \approx 4.19 \times 10^7 \text{ m/s}
$$

### Part B: Radius of the Circular Path

**Given Constants:**
* Magnetic field ($B$) = 0.1 T
* Velocity ($v$) $\approx 4.19 \times 10^7 \text{ m/s}$ (calculated in Part A)

Now, let's rearrange the magnetic force formula to solve for the radius ($r$). We can cancel out one $v$ from each side of the equation:

$$
e \cdot B = \frac{m_e \cdot v}{r}
$$

$$
r = \frac{m_e \cdot v}{e \cdot B}
$$

Substitute the values into this new equation:

$$
r = \frac{(9.11 \times 10^{-31}) \cdot (4.19 \times 10^7)}{(1.60 \times 10^{-19}) \cdot 0.1}
$$

$$
r = \frac{38.17 \times 10^{-24}}{1.60 \times 10^{-20}}
$$

$$
r \approx 2.38 \times 10^{-3} \text{ m}
$$

### Final Answer

* The velocity of the electron after acceleration is approximately **$4.19 \times 10^7 \text{ m/s}$**.
* The radius of the circular path it follows in the magnetic field is approximately **$2.38 \times 10^{-3} \text{ m}$** (which is about **2.38 mm**).
