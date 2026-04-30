## 2. Electric Potential

We are calculating the total electric potential at the center of a square due to four point charges located at its corners. The fundamental formula for the electric potential ($V$) created by a point charge ($q$) at a distance ($r$) is:

$$
V = k \cdot \frac{q}{r}
$$

To find the total electric potential at a specific point, we use the principle of superposition. 

*Note: Unlike electric force or electric field, electric potential is a **scalar** quantity. This means we do not need to worry about vectors or directions; we simply calculate the algebraic sum of the individual potentials, taking the signs of the charges into account.*

---

### Part A: Distance Calculation

**Given:**
* Charges at corners: $q_1 = +1.0 \text{ C}$, $q_2 = -2.0 \text{ C}$, $q_3 = +3.0 \text{ C}$, $q_4 = -4.0 \text{ C}$
* Side length of the square ($a$) = 1.0 m
* Coulomb's constant ($k$) $\approx 8.99 \times 10^9 \text{ N}\cdot\text{m}^2/\text{C}^2$

First, we determine the distance ($r$) from the center of the square to any of its corners. The diagonal of a square is $a\sqrt{2}$. The distance from the center to a corner is exactly half of the diagonal:

$$
r = \frac{a\sqrt{2}}{2}
$$

$$
r = \frac{1.0 \cdot \sqrt{2}}{2} \approx 0.707 \text{ m}
$$

### Part B: Superposition of Potentials

Now we calculate the total net potential ($V_{net}$) at the center by adding the potentials from all four charges. Since the distance ($r$) and Coulomb's constant ($k$) are the same for all four charges, we can factor them out to simplify the mathematical calculation:

$$
V_{net} = V_1 + V_2 + V_3 + V_4
$$

$$
V_{net} = \frac{k \cdot q_1}{r} + \frac{k \cdot q_2}{r} + \frac{k \cdot q_3}{r} + \frac{k \cdot q_4}{r}
$$

$$
V_{net} = \frac{k}{r} \cdot (q_1 + q_2 + q_3 + q_4)
$$

Let's substitute our known values into the simplified equation. We sum the charges first:

$$
\Sigma q = (+1.0) + (-2.0) + (+3.0) + (-4.0) = -2.0 \text{ C}
$$

Now substitute the sum back into the main equation:

$$
V_{net} = \frac{8.99 \times 10^9}{0.707} \cdot (-2.0)
$$

$$
V_{net} \approx (12.71 \times 10^9) \cdot (-2.0)
$$

$$
V_{net} \approx -25.42 \times 10^9 \text{ V}
$$

### Final Answer

* The net electric potential at the center of the square is approximately **$-2.54 \times 10^{10} \text{ V}$** (or $-25.42 \text{ GV}$).
