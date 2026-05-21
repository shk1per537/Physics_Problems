## 14. RLC Circuit

We are exploring the mathematical model of a series RLC circuit and comparing it to a fundamental mechanical system. By applying Kirchhoff's Voltage Law (KVL) to a series circuit with a voltage source $V(t)$, a resistor $R$, an inductor $L$, and a capacitor $C$, we state that the sum of the voltage drops equals the supplied voltage:

$$
V_L(t) + V_R(t) + V_C(t) = V(t)
$$

Substituting the characteristic equations for each component ($V_L = L \frac{dI}{dt}$ and $V_R = I \cdot R$), we get:

$$
L \frac{dI}{dt} + R \cdot I(t) + V_C(t) = V(t)
$$

---

### Part A: The Differential Equation

To make this a proper second-order differential equation that we can compare to mechanical systems, we express it in terms of electrical charge $Q(t)$. We know that current is the rate of change of charge ($I = \frac{dQ}{dt}$) and the voltage across the capacitor is $V_C = \frac{Q}{C}$. 

Substituting these relationships, the differential equation for the series RLC circuit becomes:

$$
L \frac{d^2Q}{dt^2} + R \frac{dQ}{dt} + \frac{1}{C}Q = V(t)
$$

### Part B: The Damped Harmonic Oscillator

Now, let's look at the classic mechanical system of a mass $m$ attached to a spring with constant $k$, experiencing a damping (friction) force proportional to its velocity ($b \cdot v$), and driven by an external force $F(t)$. Using Newton's Second Law ($\Sigma F = ma$), the differential equation is:

$$
m \frac{d^2x}{dt^2} + b \frac{dx}{dt} + kx = F(t)
$$

Where $x(t)$ is the displacement (position) of the mass.

### Part C: The Analogies

By looking at the two second-order linear differential equations above, we can see they are mathematically identical in structure. This means the physics of an RLC circuit is exactly analogous to a mass oscillating on a spring! 

Here is the direct mapping of the terms:

| Mechanical System (Oscillator) | Electrical System (RLC Circuit) | Physical Significance |
| :--- | :--- | :--- |
| **Position / Displacement** ($x$) | **Charge** ($Q$) | The fundamental quantity that is moving/changing. |
| **Velocity** ($v = \frac{dx}{dt}$) | **Current** ($I = \frac{dQ}{dt}$) | The rate of flow or movement. |
| **Mass** ($m$) | **Inductance** ($L$) | **Inertia:** opposes changes in motion/current. |
| **Damping Constant** ($b$) | **Resistance** ($R$) | **Dissipation:** removes energy from the system (friction/heat). |
| **Spring Constant** ($k$) | **Inverse Capacitance** ($\frac{1}{C}$) | **Restoring Force:** pushes the system back to equilibrium. |
| **External Force** ($F$) | **Voltage Source** ($V$) | The external driving energy applied to the system. |
