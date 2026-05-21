## 9. Current

We are calculating the instantaneous electrical current flowing through a wire at a specific moment in time, given the function for the total charge. 

By definition, current ($I$) is the rate of flow of electric charge ($Q$) over time ($t$). Mathematically, this means instantaneous current is the first derivative of the charge function with respect to time:

$$
I(t) = \frac{dQ(t)}{dt}
$$

---

### Part A: Finding the Current Function

**Given Function:**
* Charge function: $Q(t) = 5t^2 + 5$ (in Coulombs)

Let's take the derivative of $Q(t)$ with respect to $t$. 
* The derivative of $5t^2$ is $10t$ (using the power rule).
* The derivative of the constant $5$ is $0$.

$$
I(t) = \frac{d}{dt}(5t^2 + 5)
$$

$$
I(t) = 10t
$$

This new function gives us the current in Amperes for any given second $t$.

### Part B: Calculating Current at a Specific Time

**Given Constant:**
* Time ($t$) = 3 s

Now we simply substitute $t = 3$ into our newly derived current function:

$$
I(3) = 10 \cdot 3
$$

$$
I(3) = 30\ \text{A}
$$

### Final Answer

* The instantaneous current flowing through the wire at exactly $t = 3\ \text{s}$ is **$30\ \text{A}$**.
