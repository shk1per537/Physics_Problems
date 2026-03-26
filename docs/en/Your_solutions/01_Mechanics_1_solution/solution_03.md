## 3. Path Intersection

We are given the parametric equations for Alice and Bob's paths:
* Alice: $A(t) = (2+t, 8-3t)$
* Bob: $B(t) = (2t-1, 2t+2)$

---

### Step 1: Check for a collision

For Alice and Bob to collide, they must be at the exact same $x$ and $y$ coordinates at the exact same time $t$. 

Let's set their $x$-coordinates equal to each other:

$$
2 + t = 2t - 1
$$

$$
t = 3
$$

If they collide, their $y$-coordinates must also be equal at $t = 3$. Let's check:

For Alice at $t = 3$:

$$
A_y(3) = 8 - 3(3) = 8 - 9 = -1
$$

For Bob at $t = 3$:

$$
B_y(3) = 2(3) + 2 = 6 + 2 = 8
$$

Since $-1 \neq 8$, they are not at the same place at the same time. **They do not collide.**

*(Note: Their physical paths do cross in space at the point $(2.75, 5.75)$, but Alice and Bob arrive there at different times).*

### Step 2: Set up the distance function

Since they don't collide, we need to find the minimum distance between them. The square of the distance, $D^2(t)$, between the two points at any time $t$ is given by the distance formula:

$$
D^2(t) = (B_x(t) - A_x(t))^2 + (B_y(t) - A_y(t))^2
$$

Substitute the parametric equations:

$$
D^2(t) = ((2t - 1) - (2 + t))^2 + ((2t + 2) - (8 - 3t))^2
$$

Simplify the terms inside the parentheses:

$$
D^2(t) = (t - 3)^2 + (5t - 6)^2
$$

Expand the binomials:

$$
D^2(t) = (t^2 - 6t + 9) + (25t^2 - 60t + 36)
$$

Combine like terms to get our optimization function:

$$
D^2(t) = 26t^2 - 66t + 45
$$

### Step 3: Find the time of minimum distance

To minimize $D^2(t)$, we take its first derivative with respect to $t$ and set it to zero:

$$
\frac{d}{dt} D^2(t) = 52t - 66
$$

$$
52t - 66 = 0
$$

$$
52t = 66
$$

$$
t = \frac{66}{52} = \frac{33}{26} \approx 1.269
$$

### Step 4: Calculate the minimum distance

Now, substitute $t = \frac{33}{26}$ back into the distance squared formula:

$$
D^2\left(\frac{33}{26}\right) = 26\left(\frac{33}{26}\right)^2 - 66\left(\frac{33}{26}\right) + 45
$$

$$
D^2 = 26\left(\frac{1089}{676}\right) - \frac{2178}{26} + 45
$$

$$
D^2 = \frac{1089}{26} - \frac{2178}{26} + \frac{1170}{26}
$$

$$
D^2 = \frac{81}{26}
$$

Take the square root to find the actual minimum distance:

$$
D = \sqrt{\frac{81}{26}} = \frac{9}{\sqrt{26}} = \frac{9\sqrt{26}}{26} \approx 1.765
$$

### Final Answer

Alice and Bob **do not collide**. 
The minimum distance between them is **$\frac{9}{\sqrt{26}}$ (approx. 1.765 units)**, and it occurs at time **$t = \frac{33}{26}$ (approx. 1.269 seconds)**.
