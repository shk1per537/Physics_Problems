## 1. Series and Parallel Circuit

We are analyzing a direct current (DC) circuit containing a battery and three resistors to compare how their arrangement affects the total resistance and the total current drawn from the power source. 

The fundamental formula relating voltage ($V$), current ($I$), and resistance ($R$) is Ohm's Law:

$$
I = \frac{V}{R_{eq}}
$$

Where $R_{eq}$ is the equivalent (or total) resistance of the circuit. The formulas for finding $R_{eq}$ depend on how the components are connected:
* **Series:** $R_{eq} = R_1 + R_2 + R_3 + ...$
* **Parallel:** $\frac{1}{R_{eq}} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3} + ...$

---

### Part A: Series Circuit

**Given Constants:**
* Resistors: $R_1 = 15 \ \Omega$, $R_2 = 30 \ \Omega$, $R_3 = 50 \ \Omega$
* Voltage ($V$) = 12 V

In a series circuit, the current has only one path to flow, so the resistances simply add up:

$$
R_{eq, series} = 15 + 30 + 50
$$

$$
R_{eq, series} = 95 \ \Omega
$$

Now we use Ohm's Law to calculate the total current drawn from the battery in this configuration:

$$
I_{series} = \frac{12}{95}
$$

$$
I_{series} \approx 0.126 \text{ A}
$$

### Part B: Parallel Circuit

**Given Constants:**
* Resistors: $R_1 = 15 \ \Omega$, $R_2 = 30 \ \Omega$, $R_3 = 50 \ \Omega$
* Voltage ($V$) = 12 V (remains the same)

In a parallel circuit, the current splits into multiple paths. We calculate the equivalent resistance using the reciprocal formula:

$$
\frac{1}{R_{eq, parallel}} = \frac{1}{15} + \frac{1}{30} + \frac{1}{50}
$$

To add these fractions, we find a common denominator, which is 150:

$$
\frac{1}{R_{eq, parallel}} = \frac{10}{150} + \frac{5}{150} + \frac{3}{150}
$$

$$
\frac{1}{R_{eq, parallel}} = \frac{18}{150}
$$

Now, we take the reciprocal to find $R_{eq, parallel}$:

$$
R_{eq, parallel} = \frac{150}{18} = \frac{25}{3}
$$

$$
R_{eq, parallel} \approx 8.33 \ \Omega
$$

Now we calculate the total current drawn from the battery in parallel:

$$
I_{parallel} = \frac{12}{25/3} = \frac{36}{25}
$$

$$
I_{parallel} = 1.44 \text{ A}
$$

### Final Answer

* **Series Connection:** The equivalent resistance is **$95 \ \Omega$**, and the total current from the battery is approximately **$0.126 \text{ A}$**.
* **Parallel Connection:** The equivalent resistance drops significantly to approximately **$8.33 \ \Omega$**, causing the battery to supply a much larger total current of **$1.44 \text{ A}$**.
