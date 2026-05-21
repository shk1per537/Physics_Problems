## 4. Mixed Circuit

We are calculating the equivalent resistance of a mixed circuit by breaking it down into simpler series and parallel blocks. All resistors in this circuit have a value of $10 \ \Omega$. We will simplify the circuit from the inside out, evaluating the distinct branches before combining them with the final resistor.

---

### Part A: Simplifying the Bottom Branch

Looking at the main split from the left terminal, let's analyze the bottom branch. It consists of one $10 \ \Omega$ resistor in series with a small parallel pair of two $10 \ \Omega$ resistors.

First, calculate the equivalent resistance of the small parallel pair ($R_{p1}$):

$$
R_{p1} = \frac{10 \cdot 10}{10 + 10} = \frac{100}{20} = 5 \ \Omega
$$

Next, add this to the resistor that is in series with it to find the total resistance of the entire bottom branch ($R_{bottom}$):

$$
R_{bottom} = 10 + 5 = 15 \ \Omega
$$

### Part B: Simplifying the Top Branch

The top branch is much simpler; it consists of exactly two $10 \ \Omega$ resistors connected end-to-end in a series sequence. 

Calculate the total resistance of the top branch ($R_{top}$):

$$
R_{top} = 10 + 10 = 20 \ \Omega
$$

### Part C: Parallel Combination of the Branches

Now we have simplified the main split into two equivalent resistors: a $20 \ \Omega$ top branch and a $15 \ \Omega$ bottom branch. These two branches are connected in parallel.

Calculate the equivalent resistance of this entire parallel section ($R_{parallel}$):

$$
R_{parallel} = \frac{R_{top} \cdot R_{bottom}}{R_{top} + R_{bottom}}
$$

$$
R_{parallel} = \frac{20 \cdot 15}{20 + 15}
$$

$$
R_{parallel} = \frac{300}{35} = \frac{60}{7} \ \Omega \ (\approx 8.57 \ \Omega)
$$

### Part D: Total Equivalent Resistance

Finally, this entire parallel section ($\frac{60}{7} \ \Omega$) is connected in series with the very last $10 \ \Omega$ resistor leading to the right terminal.

To find the final equivalent resistance ($R_{eq}$), we simply add them together:

$$
R_{eq} = R_{parallel} + 10
$$

$$
R_{eq} = \frac{60}{7} + 10
$$

To add these, convert 10 to a fraction with a common denominator ($\frac{70}{7}$):

$$
R_{eq} = \frac{60}{7} + \frac{70}{7} = \frac{130}{7} \ \Omega
$$

### Final Answer

* The exact equivalent resistance for the entire circuit is **$130/7 \ \Omega$**.
* In decimal form, this is approximately **$18.57 \ \Omega$**.
