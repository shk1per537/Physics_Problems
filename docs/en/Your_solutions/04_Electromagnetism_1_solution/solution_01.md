## 1. Coulomb's Law

We are analyzing the electrostatic forces acting on a point charge located at the center of a square due to four identical charges positioned at the corners. The fundamental formula for calculating the magnitude of the electrostatic force ($F$) between two point charges ($q_1$ and $q_2$) separated by a distance ($r$) is Coulomb's Law:

$$
F = k \cdot \frac{|q_1 \cdot q_2|}{r^2}
$$

To find the total net force, we must evaluate the individual force vectors from each corner charge and combine them using the principle of superposition. 

*Note: Force is a vector quantity, meaning both its magnitude and direction must be considered when combining multiple forces.*

---

### Part A: Distance and Magnitude

**Given:**
* Charges at the corners ($q_{corner}$) = +1.0 C
* Side length of the square ($a$) = 1.0 m
* Central charge ($q_{center}$) = -2.0 C
* Coulomb's constant ($k$) $\approx 8.99 \times 10^9 \text{ N}\cdot\text{m}^2/\text{C}^2$

First, let's determine the distance ($r$) from the center of the square to any of its corners. The diagonal of a square is calculated as $a\sqrt{2}$. The distance from the center to a corner is exactly half of the diagonal:

$$
r = \frac{a\sqrt{2}}{2}
$$

$$
r = \frac{1.0 \cdot \sqrt{2}}{2} \approx 0.707 \text{ m}
$$

If we were to calculate the magnitude of the force exerted by just *one* corner charge on the central charge, we would substitute our values into Coulomb's Law:

$$
F_1 = k \cdot \frac{|q_{corner} \cdot q_{center}|}{r^2}
$$

Because all four corner charges are identical in magnitude (+1.0 C) and are located at the exact same distance ($r$) from the central charge, the magnitude of the force exerted by each individual corner charge is identical:

$$
F_1 = F_2 = F_3 = F_4
$$

### Part B: Vector Addition and Symmetry

Now we evaluate the direction of these forces to find the net force. Since the central charge is negative (-2.0 C) and the corner charges are positive (+1.0 C), the forces are attractive. This means the central charge is being pulled directly toward each of the four corners.

* The force pulling the central charge toward the top-left corner is directly opposed by the force pulling it toward the bottom-right corner.
* The force pulling the central charge toward the top-right corner is directly opposed by the force pulling it toward the bottom-left corner.

Because these opposing forces are equal in magnitude and point in exactly opposite directions along the diagonals, they perfectly cancel each other out. 

$$
\vec{F}_{net} = \vec{F}_{top\text{-}left} + \vec{F}_{bottom\text{-}right} + \vec{F}_{top\text{-}right} + \vec{F}_{bottom\text{-}left}
$$

$$
\vec{F}_{net} = 0 \text{ N}
$$

### Final Answer

* The magnitude of the net electric force on the central charge is **0 N**.
* Because the net force is perfectly balanced by the symmetry of the system, the direction of the force is **undefined** (or none).
