## 5. Relative Velocity

We have a river flowing East at 2 m/s. A boat that travels at 5 m/s in still water needs to cross the river directly North. We need to find the heading angle and the time it takes to cross a 200-meter-wide river.

---

### Step 1: Set up the vector triangle

Let the velocity of the river be $\vec{v}_{r}$ and the velocity of the boat relative to the water be $\vec{v}_{b}$. The resultant velocity of the boat relative to the ground is $\vec{v}_{g}$. 

To travel directly North, the boat must head somewhat West of North to counteract the Eastward flow of the river. This forms a right-angled vector triangle where:
* The hypotenuse is the boat's speed through the water: $|\vec{v}_{b}| = 5$
* The horizontal leg (East) is the river's speed: $|\vec{v}_{r}| = 2$
* The vertical leg (North) is the resultant speed across the ground: $|\vec{v}_{g}|$

### Step 2: Calculate the heading angle

Let $\theta$ be the angle West of North that the boat must head. The river's velocity exactly cancels the horizontal component of the boat's velocity.

Using trigonometry (opposite over hypotenuse):

$$
\sin(\theta) = \frac{|\vec{v}_{r}|}{|\vec{v}_{b}|} = \frac{2}{5} = 0.4
$$

Take the inverse sine to find the angle:

$$
\theta = \arcsin(0.4) \approx 23.58^\circ
$$

So, the boat must head approximately **$23.58^\circ$ West of North**.

### Step 3: Calculate the resultant velocity

To find how long it takes to cross, we first need the boat's actual speed directly North across the ground ($|\vec{v}_{g}|$). We can use the Pythagorean theorem:

$$
|\vec{v}_{g}|^2 + |\vec{v}_{r}|^2 = |\vec{v}_{b}|^2
$$

$$
|\vec{v}_{g}|^2 + 2^2 = 5^2
$$

$$
|\vec{v}_{g}|^2 + 4 = 25
$$

$$
|\vec{v}_{g}|^2 = 21
$$

$$
|\vec{v}_{g}| = \sqrt{21} \approx 4.58 \text{ m/s}
$$

### Step 4: Calculate the time to cross

The time ($t$) to cross the river is the total distance divided by the resultant velocity straight across the river:

$$
t = \frac{d}{|\vec{v}_{g}|}
$$

$$
t = \frac{200}{\sqrt{21}} \approx 43.64 \text{ seconds}
$$

### Final Answer

* **Heading:** Approximately **$23.58^\circ$** West of North.
* **Time to cross:** Approximately **43.64 seconds**.
