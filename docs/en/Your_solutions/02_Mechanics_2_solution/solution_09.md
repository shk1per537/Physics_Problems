## 9. Vertical Throw with Drag

We are modeling an object thrown upward where air resistance is proportional to velocity (linear drag). The equation of motion is:

$$m\frac{dv}{dt} = -mg - kv$$

**Initial Conditions:**
* $v(0) = v_0$
* $x(0) = 10$

---

### 1. Analytical Solution

First, we solve for velocity $v(t)$. Let $\gamma = k/m$. The equation becomes:
$$\frac{dv}{dt} = -(g + \gamma v)$$

Separating variables and integrating:
$$\int_{v_0}^{v} \frac{dv'}{g + \gamma v'} = \int_{0}^{t} -dt'$$
$$\frac{1}{\gamma} \ln\left(\frac{g + \gamma v}{g + \gamma v_0}\right) = -t$$

Solving for $v(t)$:
$$v(t) = \left(v_0 + \frac{g}{\gamma}\right)e^{-\gamma t} - \frac{g}{\gamma}$$

To find position $x(t)$, we integrate velocity:
$$x(t) = 10 + \int_{0}^{t} v(t') dt'$$
$$x(t) = 10 + \frac{1}{\gamma}\left(v_0 + \frac{g}{\gamma}\right)(1 - e^{-\gamma t}) - \frac{g}{\gamma}t$$

### 2. Maximum Height

Maximum height occurs when $v(t) = 0$. Let's find this time $t_{max}$:
$$0 = \left(v_0 + \frac{g}{\gamma}\right)e^{-\gamma t_{max}} - \frac{g}{\gamma} \implies e^{-\gamma t_{max}} = \frac{g}{g + \gamma v_0}$$
$$t_{max} = \frac{1}{\gamma} \ln\left(1 + \frac{\gamma v_0}{g}\right)$$

Substituting $t_{max}$ back into the $x(t)$ equation gives the peak height.

### 3. Comparison with Vacuum Case (No Drag)

When there is no drag ($k=0$ or $\gamma \to 0$), the equations simplify to the standard kinematic formulas:
* **Velocity:** $v(t) = v_0 - gt$
* **Position:** $x(t) = 10 + v_0 t - \frac{1}{2}gt^2$
* **Max Height Time:** $t_{max} = \frac{v_0}{g}$

> **Observation:** With drag, the object reaches a lower maximum height and reaches it sooner than it would in a vacuum. This is because both gravity and drag are working together to slow the object down during the ascent.
> <img width="855" height="547" alt="image" src="https://github.com/user-attachments/assets/479daad2-df70-4869-b83e-e6eb9ce4ebf7" />
