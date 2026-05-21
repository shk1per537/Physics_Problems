## 8. AC Voltage Equation

We need to find the equation for the alternating voltage $V(t)$ across a resistor, given the equation for the alternating current $I(t)$ flowing through it.

In a purely resistive AC circuit, Ohm's Law applies not just to the effective (RMS) values, but also to the instantaneous values at any given moment in time:

$$
V(t) = I(t) \cdot R
$$

*Note: In a circuit with only a resistor (no capacitors or inductors), the voltage and current are exactly **in phase**. This means the sine wave for voltage reaches its peaks and zero-crossings at the exact same times as the current wave. Therefore, the angular frequency and phase argument ($120\pi t$) will remain exactly the same.*

---

### Part A: Calculating Peak Voltage

**Given Constants:**
* Current equation: $I(t) = 2\sin(120\pi t)\ \text{A}$
* Peak current ($I_0$) = $2\ \text{A}$
* Resistance ($R$) = $50\ \Omega$

First, let's find the peak voltage ($V_0$), which is the amplitude of our new voltage equation:

$$
V_0 = I_0 \cdot R
$$

$$
V_0 = 2 \cdot 50 = 100\ \text{V}
$$

### Part B: Constructing the Equation

Now we simply assemble the final equation by multiplying the entire original current function by the resistance, replacing the current amplitude with our newly calculated voltage amplitude:

$$
V(t) = V_0 \cdot \sin(120\pi t)
$$

$$
V(t) = 100\sin(120\pi t)
$$

### Final Answer

* The equation for the voltage across the resistor is **$V(t) = 100\sin(120\pi t)$** (in Volts).
