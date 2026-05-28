## 5. Kirchhoff's Laws

We are solving for the three branch currents using Kirchhoff's Current Law (KCL) and Voltage Law (KVL). First, we must assign a direction to each current. Let's define them relative to the top and bottom junctions (nodes):

* **I₁**: Flows **clockwise** through the left branch (entering the top node).
* **I₂**: Flows **downwards** through the shared middle branch R₂ (leaving the top node).
* **I₃**: Flows **downwards** through the right branch (leaving the top node). *(Note: As there is no R₃ explicitly labeled, we assume I₃ refers to the right branch containing E₂).*

---

### Part A: Setting Up the Equations

**1. Kirchhoff's Current Law (Top Node):**
The total current entering the junction must equal the total current leaving.

$$
I_1 = I_2 + I_3
$$

**2. Kirchhoff's Voltage Law (Left Loop):**
We traverse the left loop **clockwise** starting from the bottom node. 
* We pass through E₁ from the short bar (-) to the long bar (+), gaining 4.5 V.
* We experience voltage drops across r_w (1 Ω) and R₁ (20 Ω) in the direction of I₁.
* We experience a voltage drop across R₂ (10 Ω) in the direction of I₂.

$$
4.5 - 1 \cdot I_1 - 20 \cdot I_1 - 10 \cdot I_2 = 0
$$

Simplifying this equation:

$$
21 I_1 + 10 I_2 = 4.5
$$

**3. Kirchhoff's Voltage Law (Right Loop):**
We traverse the right loop **clockwise** starting from the top node.
* We move down the right branch *with* I₃, causing a voltage drop across r_w (1 Ω).
* We pass through E₂ from the short top bar (-) to the long bottom bar (+), gaining 9 V.
* We move up the middle branch *against* our defined downward I₂, resulting in a voltage gain across R₂.

$$
-1 \cdot I_3 + 9 + 10 \cdot I_2 = 0
$$

Rearranging to align our variables:

$$
10 I_2 - I_3 = -9
$$

### Part B: Solving the System

We have a system of three equations. Let's express everything in terms of I₂. From the third equation, we isolate I₃:

$$
I_3 = 10 I_2 + 9
$$

Substitute this I₃ into the KCL equation (Eq 1) to find I₁ in terms of I₂:

$$
I_1 = I_2 + (10 I_2 + 9) = 11 I_2 + 9
$$

Now, substitute this expression for I₁ into the Left Loop equation (Eq 2):

$$
21(11 I_2 + 9) + 10 I_2 = 4.5
$$

Expand and solve for I₂:

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

Now, substitute the exact fraction back into our expressions for I₁ and I₃:

**Calculating I₁:**

$$
I_1 = 11 \cdot \left(-\frac{184.5}{241}\right) + 9
$$

$$
I_1 = -\frac{2029.5}{241} + \frac{2169}{241} = \frac{139.5}{241} \approx 0.579 \text{ A}
$$

**Calculating I₃:**

$$
I_3 = 10 \cdot \left(-\frac{184.5}{241}\right) + 9
$$

$$
I_3 = -\frac{1845}{241} + \frac{2169}{241} = \frac{324}{241} \approx 1.344 \text{ A}
$$

### Final Answer

* **I₁ ≈ 0.579 A** (Flowing clockwise through the left branch).
* **I₂ ≈ -0.766 A** (The negative sign indicates the current actually flows **upwards** through the shared middle resistor R₂, opposite to our initial downward assumption).
* **I₃ ≈ 1.344 A** (Flowing downwards through the right branch).
