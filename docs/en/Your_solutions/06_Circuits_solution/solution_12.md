## 12. Transformer Currents

We are analyzing an ideal transformer to determine the voltage and current on the secondary side based on the primary side's characteristics. Transformers work on the principle of electromagnetic induction and use the ratio of turns in their coils to step up or step down AC voltage.

The fundamental equations for an ideal transformer are:

* **Voltage ratio:** $\frac{V_s}{V_p} = \frac{N_s}{N_p}$
* **Current ratio:** $\frac{I_p}{I_s} = \frac{N_s}{N_p}$

*Note that current is inversely proportional to voltage to conserve power, assuming 100% efficiency:*

$$
P_{in} = P_{out}
$$

$$
V_p \cdot I_p = V_s \cdot I_s
$$

---

### Part A: Secondary Voltage

**Given Constants:**
* Primary turns (Np) = 1000
* Secondary turns (Ns) = 200
* Primary voltage (Vp) = 120 V

Let's rearrange the voltage ratio formula to solve for the secondary voltage (Vs):

$$
V_s = V_p \cdot \frac{N_s}{N_p}
$$

Substitute the known values:

$$
V_s = 120 \cdot \frac{200}{1000}
$$

$$
V_s = 120 \cdot 0.2
$$

$$
V_s = 24 \text{ V}
$$

*Because the secondary voltage is lower than the primary voltage, this is a **step-down** transformer.*

### Part B: Primary Current

**Given Constants:**
* Secondary current (Is) = 3 A
* Turns ratio = 200 / 1000 = 0.2

Let's rearrange the current ratio formula to solve for the primary current (Ip):

$$
I_p = I_s \cdot \frac{N_s}{N_p}
$$

Substitute the known values:

$$
I_p = 3 \cdot 0.2
$$

$$
I_p = 0.6 \text{ A}
$$

### Final Answer

* The secondary voltage is **24 V**.
* The current in the primary coil is **0.6 A**.
