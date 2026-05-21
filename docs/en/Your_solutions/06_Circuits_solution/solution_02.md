## 2. Resistors

We are determining all possible equivalent resistances that can be created by connecting exactly three identical resistors together. To find all unique values, we must evaluate every possible topological combination: all in series, all in parallel, and the two possible mixed configurations.

The fundamental formulas for combining resistors are:
* **Series:** $R_{eq} = R_1 + R_2 + R_3 + ...$
* **Parallel:** $\frac{1}{R_{eq}} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3} + ...$ 

*(For two resistors in parallel, this simplifies to $R_{eq} = \frac{R_1 \cdot R_2}{R_1 + R_2}$)*

---

### Part A: All Three in Series

**Given:**
* Resistors: $R_1 = R_2 = R_3 = 1 \ \Omega$

When all three resistors are connected end-to-end in a single line, their resistances simply add together to create the maximum possible resistance:

$$
R_{eq1} = 1 + 1 + 1
$$

$$
R_{eq1} = 3 \ \Omega
$$

### Part B: All Three in Parallel

When all three resistors are connected across the same two points, the current splits equally among them, creating the minimum possible resistance:

$$
\frac{1}{R_{eq2}} = \frac{1}{1} + \frac{1}{1} + \frac{1}{1} = 3
$$

Taking the reciprocal:

$$
R_{eq2} = \frac{1}{3} \ \Omega \approx 0.333 \ \Omega
$$

### Part C: Two in Series, One in Parallel

In this mixed configuration, two resistors are in series with each other, and this entire branch is placed in parallel with the third resistor.

First, calculate the series branch ($R_s$):

$$
R_s = 1 + 1 = 2 \ \Omega
$$

Next, combine this $2 \ \Omega$ equivalent resistor in parallel with the remaining $1 \ \Omega$ resistor:

$$
R_{eq3} = \frac{2 \cdot 1}{2 + 1}
$$

$$
R_{eq3} = \frac{2}{3} \ \Omega \approx 0.667 \ \Omega
$$

### Part D: Two in Parallel, One in Series

In the final configuration, two resistors are in parallel with each other, and this group is placed in series with the third resistor.

First, calculate the parallel group ($R_p$):

$$
R_p = \frac{1 \cdot 1}{1 + 1} = \frac{1}{2} = 0.5 \ \Omega
$$

Next, add the remaining resistor which is in series with this group:

$$
R_{eq4} = 0.5 + 1
$$

$$
R_{eq4} = 1.5 \ \Omega
$$

### Final Answer

By using exactly three $1 \ \Omega$ resistors, you can create **four unique equivalent resistances**:
* **$3 \ \Omega$** (All in series)
* **$1.5 \ \Omega$** (Two in parallel, plus one in series)
* **$2/3 \ \Omega \ (\approx 0.67 \ \Omega)$** (Two in series, parallel to the third)
* **$1/3 \ \Omega \ (\approx 0.33 \ \Omega)$** (All in parallel)
