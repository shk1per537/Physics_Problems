## 2. Ampere's Law

We are calculating the total magnetic field at a point midway between two long, straight, parallel wires carrying currents in opposite directions. The fundamental formula for the magnitude of the magnetic field ($B$) produced by a long, straight wire at a distance ($r$) is derived from Ampere's Law:

$$
B = \frac{\mu_0 \cdot I}{2\pi \cdot r}
$$

To find the total magnetic field at the midpoint, we must determine the magnitude and direction of the field created by each wire individually and then apply the principle of superposition (vector addition).

*Note: The direction of the magnetic field around a wire is determined by the **Right-Hand Grip Rule**: if you point your right thumb in the direction of the current, your fingers curl in the direction of the circular magnetic field lines.*

---

### Part A: Magnitude of Individual Fields

**Given Constants:**
* Total distance between wires ($d$) = $10 \text{ cm} = 0.1 \text{ m}$
* Distance from each wire to the midpoint ($r$) = $\frac{d}{2} = 0.05 \text{ m}$
* Current in wire 1 ($I_1$) = $5 \text{ A}$
* Current in wire 2 ($I_2$) = $5 \text{ A}$
* Vacuum permeability ($\mu_0$) = $4\pi \times 10^{-7} \text{ T}\cdot\text{m/A}$

First, let's calculate the magnitude of the magnetic field produced by the first wire ($B_1$) at the midpoint:

$$
B_1 = \frac{(4\pi \times 10^{-7}) \cdot 5}{2\pi \cdot 0.05}
$$

We can simplify the fraction by canceling out $2\pi$:

$$
B_1 = \frac{(2 \times 10^{-7}) \cdot 5}{0.05}
$$

$$
B_1 = \frac{10 \times 10^{-7}}{0.05}
$$

$$
B_1 = 200 \times 10^{-7} \text{ T} = 2 \times 10^{-5} \text{ T}
$$

Since the second wire carries the exact same amount of current ($I_2 = 5 \text{ A}$) and is at the exact same distance from the midpoint ($r = 0.05 \text{ m}$), the magnitude of its magnetic field ($B_2$) will be identical:

$$
B_2 = 2 \times 10^{-5} \text{ T}
$$

### Part B: Direction and Superposition

Now we must account for the direction of the currents to sum the fields correctly. The wires carry currents in **opposite** directions. 

Imagine the wires laid out flat on a page, with Wire 1 on the left and Wire 2 on the right. 
* If $I_1$ flows "up" the page, applying the Right-Hand Grip Rule shows that its magnetic field at the midpoint (to its right) points **into** the page.
* If $I_2$ flows "down" the page (opposite to $I_1$), applying the Right-Hand Grip Rule shows that its magnetic field at the midpoint (to its left) also points **into** the page.

Because the two magnetic field vectors point in the exact same direction at the midpoint, they reinforce each other. We simply add their magnitudes together to find the net magnetic field ($B_{net}$):

$$
B_{net} = B_1 + B_2
$$

$$
B_{net} = (2 \times 10^{-5}) + (2 \times 10^{-5})
$$

$$
B_{net} = 4 \times 10^{-5} \text{ T}
$$

### Final Answer

* The magnitude of the net magnetic field midway between the wires is **$4 \times 10^{-5} \text{ T}$** (or $40 \text{ }\mu\text{T}$).
* Because the currents flow in opposite directions, their individual magnetic fields reinforce each other at the midpoint. The direction of the net magnetic field is **perpendicular to the plane containing the wires** (e.g., pointing straight into the page if the wires lie flat on the page).
