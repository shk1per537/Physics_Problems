## 7. Dynamics with Friction

We need to find the acceleration of a 10 kg block (bottom) which has a 5 kg block (top) resting on it. The top block is tethered to a wall, and a force is applied to the bottom block.

**Given:**
* Mass of top block ($m_1$) = 5 kg
* Mass of bottom block ($m_2$) = 10 kg
* Applied force ($F$) = 45 N
* Coefficient of kinetic friction ($\mu_k$) = 0.2
* Gravity ($g$) $\approx 9.8$ m/s²

---

### Step 1: Identify the friction surfaces for the 10 kg block

The bottom block ($m_2$) experiences kinetic friction from two different interfaces:
1.  **Top Surface:** Between $m_1$ and $m_2$.
2.  **Bottom Surface:** Between $m_2$ and the floor.



### Step 2: Calculate the friction forces

**Friction from the top block ($f_{k1}$):**
The normal force is just the weight of the top block: $N_1 = m_1 g$.
$$f_{k1} = \mu_k m_1 g$$
$$f_{k1} = 0.2 \cdot 5 \cdot 9.8 = 9.8 \text{ N}$$

**Friction from the floor ($f_{k2}$):**
The floor must support the weight of **both** blocks: $N_2 = (m_1 + m_2)g$.
$$f_{k2} = \mu_k (m_1 + m_2)g$$
$$f_{k2} = 0.2 \cdot (5 + 10) \cdot 9.8$$
$$f_{k2} = 0.2 \cdot 15 \cdot 9.8 = 29.4 \text{ N}$$

### Step 3: Apply Newton's Second Law to the 10 kg block

The net force ($\Sigma F$) on the bottom block is the applied force minus both friction forces:

$$\Sigma F = F - f_{k1} - f_{k2}$$
$$\Sigma F = 45 - 9.8 - 29.4 = 5.8 \text{ N}$$

Now, find the acceleration ($a$) using $F = ma$:

$$a = \frac{\Sigma F}{m_2}$$
$$a = \frac{5.8}{10} = 0.58 \text{ m/s}^2$$

> **Note:** Even though the top block is involved in creating friction, we only divide by the mass of the **moving** block (10 kg) because the 5 kg block is held stationary by the wall.

### Final Answer

The acceleration of the 10 kg block is **$0.58 \text{ m/s}^2$**.
