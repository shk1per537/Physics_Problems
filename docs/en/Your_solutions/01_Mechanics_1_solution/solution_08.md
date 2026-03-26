## 8. Circular Motion

We need to calculate the centripetal acceleration of a person standing on the Earth's equator. 

**Given:**
* Radius of the Earth ($R$) $\approx 6378 \text{ km}$
* The Earth completes one full rotation every 24 hours.

---

### Step 1: Convert units to standard SI units

First, we convert the radius from kilometers to meters:

$$
R = 6378 \text{ km} = 6,378,000 \text{ m}
$$

Next, we find the period of rotation ($T$) in seconds. The Earth rotates once per day (24 hours):

$$
T = 24 \text{ hours} \cdot 60 \text{ minutes/hour} \cdot 60 \text{ seconds/minute}
$$

$$
T = 86,400 \text{ seconds}
$$

### Step 2: Choose the centripetal acceleration formula

The formula for centripetal acceleration ($a_c$) is:

$$
a_c = \frac{v^2}{R}
$$

Alternatively, using angular velocity ($\omega$), where $\omega = \frac{2\pi}{T}$, the formula is:

$$
a_c = \omega^2 R = \left(\frac{2\pi}{T}\right)^2 R = \frac{4\pi^2 R}{T^2}
$$

### Step 3: Calculate the acceleration

We will use the formula containing the period $T$:

$$
a_c = \frac{4 \pi^2 (6,378,000)}{(86,400)^2}
$$

First, square the period:

$$
(86,400)^2 = 7,464,960,000
$$

Now, plug it into the equation:

$$
a_c = \frac{4 \pi^2 (6,378,000)}{7,464,960,000}
$$

$$
a_c \approx \frac{251,790,689}{7,464,960,000} \approx 0.0337 \text{ m/s}^2
$$

### Final Answer

The centripetal acceleration of a person standing on the Earth's equator is approximately **$0.0337 \text{ m/s}^2$**.
