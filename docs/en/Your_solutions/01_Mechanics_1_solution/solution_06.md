## 6. Variable Velocity

We are given the velocity function of an object:

$$
v(t) = t^2 + 2t - 5
$$

We also have an initial condition: at $t = 0$, the position is $x = 4$. 
We need to find the object's position $x(3)$ and acceleration $a(3)$ at $t = 3$.

---

### Step 1: Find the acceleration at $t = 3$

Acceleration is the rate of change of velocity, which means we need to take the first derivative of the velocity function with respect to time:

$$
a(t) = \frac{dv}{dt} = \frac{d}{dt}(t^2 + 2t - 5)
$$

$$
a(t) = 2t + 2
$$

Now, substitute $t = 3$ into the acceleration function:

$$
a(3) = 2(3) + 2 = 6 + 2 = 8
$$

### Step 2: Find the position function $x(t)$

Position is the antiderivative (or indefinite integral) of velocity. We integrate the velocity function:

$$
x(t) = \int v(t) \, dt = \int (t^2 + 2t - 5) \, dt
$$

$$
x(t) = \frac{t^3}{3} + t^2 - 5t + C
$$

To find the constant of integration $C$, we plug in our initial condition ($x = 4$ when $t = 0$):

$$
4 = \frac{0^3}{3} + 0^2 - 5(0) + C
$$

$$
C = 4
$$

So, our complete position function is:

$$
x(t) = \frac{t^3}{3} + t^2 - 5t + 4
$$

### Step 3: Find the position at $t = 3$

Finally, substitute $t = 3$ into the position function we just found:

$$
x(3) = \frac{3^3}{3} + 3^2 - 5(3) + 4
$$

$$
x(3) = \frac{27}{3} + 9 - 15 + 4
$$

$$
x(3) = 9 + 9 - 15 + 4 = 7
$$

### Final Answer

At time $t = 3$, the object's position is **$x = 7$** and its acceleration is **$a = 8$**.
