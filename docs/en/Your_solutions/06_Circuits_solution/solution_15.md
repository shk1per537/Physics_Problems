## 15. Resistor Cube*

We need to find the equivalent resistance between two opposite corners (the main diagonal) of a cube made of 12 identical resistors, each with resistance $R$. 

To solve this without writing a massive system of Kirchhoff's equations, we must use the **symmetry of the cube**. We will inject a total current $I$ into one corner and track how it splits along the edges until it exits the opposite corner, calculating the voltage drops along the way.

Let's designate the entry corner as Node A and the opposite exit corner as Node D.

---

### Part A: Tracking the Current

**1. The First Split (From Node A):**
When the total current $I$ enters Node A, it faces three identical edges. Because the cube is perfectly symmetrical relative to the main diagonal, the current splits equally into three parts.
* Current in each of the first 3 edges = $\frac{I}{3}$

Let's call the three corners reached by these edges the "B Nodes". Because the paths are identical, all three B Nodes are at the exact same electrical potential.

**2. The Second Split (From B Nodes to C Nodes):**
From each B Node, the current must travel forward. Each B Node connects to two edges that continue toward the exit. The current $\frac{I}{3}$ splits equally into two.
* Current in each of these 6 middle edges = $\frac{I}{3} \div 2 = \frac{I}{6}$

Let's call the nodes reached by these edges the "C Nodes". There are three C Nodes, and they are all adjacent to the final exit corner. Because they are geometrically symmetrical to the B Nodes (just on the other side), they are also at equal potential.

**3. The Recombination (From C Nodes to Node D):**
At each of the three C Nodes, two currents of $\frac{I}{6}$ flow in from the middle edges and combine to flow down the final edge toward the exit Node D.
* Current in each of the final 3 edges = $\frac{I}{6} + \frac{I}{6} = \frac{I}{3}$

At Node D, the three $\frac{I}{3}$ currents combine to perfectly recreate the total exit current $I$.

### Part B: Calculating the Total Voltage Drop

Now we use Ohm's Law ($V = I \cdot R$) to calculate the voltage drop across each section of the cube from Node A to Node D. We only need to trace **one single continuous path** from A to D, because the potential difference is the same regardless of which specific edges you follow.

**1. Voltage drop from A to B:**

$$
V_{AB} = \frac{I}{3} \cdot R
$$

**2. Voltage drop from B to C:**

$$
V_{BC} = \frac{I}{6} \cdot R
$$

**3. Voltage drop from C to D:**

$$
V_{CD} = \frac{I}{3} \cdot R
$$

**Total Voltage Drop ($V_{total}$):**

$$
V_{total} = V_{AB} + V_{BC} + V_{CD}
$$

$$
V_{total} = \frac{I \cdot R}{3} + \frac{I \cdot R}{6} + \frac{I \cdot R}{3}
$$

To add these fractions, find a common denominator (6):

$$
V_{total} = \frac{2IR}{6} + \frac{1IR}{6} + \frac{2IR}{6}
$$

$$
V_{total} = \frac{5IR}{6}
$$

### Part C: Equivalent Resistance

By definition, the equivalent resistance ($R_{eq}$) of the entire cube is the total voltage drop divided by the total current ($R_{eq} = \frac{V_{total}}{I}$).

$$
R_{eq} = \frac{\frac{5}{6} \cdot I \cdot R}{I}
$$

The current $I$ cancels out, leaving us with our final answer:

$$
R_{eq} = \frac{5}{6}R
$$

### Final Answer

* The equivalent resistance between two diagonally opposite corners of the resistor cube is **$\frac{5}{6} R$**.
