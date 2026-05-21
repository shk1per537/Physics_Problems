## 5. Kirchhoff's Laws

We are solving for the three branch currents using Kirchhoff's Current Law (KCL) and Voltage Law (KVL). First, we must assign a direction to each current. Let's define them relative to the top and bottom junctions (nodes):

* **$I_1$**: Flows **clockwise** through the left branch (entering the top node).
* **$I_2$**: Flows **downwards** through the shared middle branch $R_2$ (leaving the top node).
* **$I_3$**: Flows **downwards** through the right branch (leaving the top node). *(Note: As there is no $R_3$ explicitly labeled, we assume $I_3$ refers to the right branch containing $\mathcal{E}_2$)*.

---

### Part A: Setting Up the Equations

**1. Kirchhoff's Current Law (Top Node):**
The total current entering the junction must equal the total current leaving.

$$
I_1 = I_2 + I_3
$$

**2. Kirchhoff's Voltage Law (Left Loop):**
We traverse the left loop **clockwise** starting from the bottom node. 
* We pass through $\mathcal{E}_1$ from the short bar (-) to the long bar (+), gaining $4.5\text{ V}$.
* We experience voltage drops across $r_w$ ($1\ \Omega$) and $R_1$ ($20\ \Omega$) in the direction of $I_1$.
* We experience a voltage drop across $R_2$ ($10\ \Omega$) in the direction of $I_2$.

$$
4.5 - 1 \cdot I_1 - 20 \cdot I_1 - 10 \cdot I_2 = 0
$$

Simplifying this equation:

$$
21 I_1 + 10 I_2 = 4.5
$$

**3. Kirchhoff's Voltage Law (Right Loop):**
We traverse the right loop **clockwise** starting from the top node.
* We move down the right branch *with* $I_3$, causing a voltage drop across $r_w$ ($1\ \Omega$).
* We pass through $\mathcal{E}_2$ from the short top bar (-) to the long bottom bar (+), gaining $9\text{ V}$.
* We move up the middle branch *against* our defined downward $I_2$, resulting in a voltage gain across $R_2$.

$$
-1 \cdot I_3 + 9 + 10 \cdot I_2 = 0
$$

Rearranging to align our variables:

$$
10 I_2 - I_3 = -9
$$

### Part B: Solving the System

We have a system of three equations. Let's express everything in terms of $I_2$. From the third equation, we isolate $I_3$:

$$
I_3 = 10 I_2 + 9
$$

Substitute this $I_3$ into the KCL equation (Eq 1) to find $I_1$ in terms of $I_2$:

$$
I_1 = I_2 + (10 I_2 + 9) = 11 I_2 + 9
$$

Now, substitute this expression for $I_1$ into the Left Loop equation (Eq 2):

$$
21(11 I_2 + 9) + 10 I_2 = 4.5
$$

Expand and solve for $I_2$:

$$
231 I_2 + 189 + 10 I_2 = 4.5
$$

$$
241 I_2 = 4.5 - 189
$$

$$
241 I_2 = -184.5
$$

$$
I_2 = -\frac{184.5}{241} \approx -0.766 \text{ A}
$$

Now, substitute the exact fraction back into our expressions for $I_1$ and $I_3$:

**Calculating $I_1$:**

$$
I_1 = 11 \cdot \left(-\frac{184.5}{241}\right) + 9
$$

$$
I_1 = -\frac{2029.5}{241} + \frac{2169}{241} = \frac{139.5}{241} \approx 0.579 \text{ A}
$$

**Calculating $I_3$:**

$$
I_3 = 10 \cdot \left(-\frac{184.5}{241}\right) + 9
$$

$$
I_3 = -\frac{1845}{241} + \frac{2169}{241} = \frac{324}{241} \approx 1.344 \text{ A}
$$

### Final Answer

* **$I_1 \approx 0.579 \text{ A}$** (Flowing clockwise through the left branch).
* **$I_2 \approx -0.766 \text{ A}$** (The negative sign indicates the current actually flows **upwards** through the shared middle resistor $R_2$, opposite to our initial downward assumption).
* **$I_3 \approx 1.344 \text{ A}$** (Flowing downwards through the right branch).
