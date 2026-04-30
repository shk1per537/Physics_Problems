## 9. Damped Oscillator

We are analyzing the behavior of a damped harmonic oscillator. The motion is described by the second-order linear ordinary differential equation:

$$
m\frac{d^2x}{dt^2} + b\frac{dx}{dt} + kx = 0
$$

where $m$ is mass, $b$ is the damping coefficient, and $k$ is the spring constant.

---

### 1. General Solution

To find the general solution, we assume a solution of the form $x(t) = e^{rt}$. Substituting this into the differential equation yields the characteristic algebraic equation:

$$
mr^2 + br + k = 0
$$

Using the quadratic formula, the roots are:

$$
r_{1,2} = \frac{-b \pm \sqrt{b^2 - 4mk}}{2m}
$$

Let's introduce two parameters to simplify:
* Undamped natural frequency: $\omega_0 = \sqrt{\frac{k}{m}}$
* Damping coefficient: $\gamma = \frac{b}{2m}$

The roots can be rewritten as: $r_{1,2} = -\gamma \pm \sqrt{\gamma^2 - \omega_0^2}$. 
The general solution is a linear combination of the roots: 

$$
x(t) = C_1 e^{r_1 t} + C_2 e^{r_2 t}
$$

### 2. Classification of Cases

The behavior of the system depends entirely on the discriminant ($b^2 - 4mk$):

* **Underdamped ($b^2 < 4mk$ or $\gamma < \omega_0$):**
  The roots are complex conjugates: $r_{1,2} = -\gamma \pm i\omega_d$, where $\omega_d = \sqrt{\omega_0^2 - \gamma^2}$ is the damped angular frequency.
  Solution: $x(t) = e^{-\gamma t}(A\cos(\omega_d t) + B\sin(\omega_d t))$. 
  *Physical meaning:* The system oscillates with an exponentially decreasing amplitude.

* **Critically damped ($b^2 = 4mk$ or $\gamma = \omega_0$):**
  There is one repeated real root: $r = -\gamma$.
  Solution: $x(t) = (A + Bt)e^{-\gamma t}$. 
  *Physical meaning:* The system returns to equilibrium as fast as possible without oscillating.

* **Overdamped ($b^2 > 4mk$ or $\gamma > \omega_0$):**
  The roots are real and negative.
  Solution: $x(t) = A e^{r_1 t} + B e^{r_2 t}$. 
  *Physical meaning:* The system returns to equilibrium slowly without oscillating.

*(Note: The numerical solution, effect of parameter b, and corresponding graphs are demonstrated in the interactive visualization).*
