## 8. Definite Integrals

We need to calculate the area under the curve of the function $f(x) = \sin(x)$ from $x = 0$ to $x = \pi$.

---

### Step 1: Set up the definite integral

The area under a curve $f(x)$ from $a$ to $b$ is calculated using the definite integral:

$$
Area = \int_{a}^{b} f(x) \, dx
$$

Substituting our specific function and limits:

$$
Area = \int_{0}^{\pi} \sin(x) \, dx
$$

### Step 2: Find the antiderivative

The antiderivative of $\sin(x)$ is $-\cos(x)$. Applying the Fundamental Theorem of Calculus, we write:

$$
Area = \left[ -\cos(x) \right]_{0}^{\pi}
$$

### Step 3: Evaluate the integral

Now, we substitute the upper limit ($\pi$) and subtract the value at the lower limit ($0$):

$$
Area = (-\cos(\pi)) - (-\cos(0))
$$

We know from trigonometry that $\cos(\pi) = -1$ and $\cos(0) = 1$. Substituting these values:

$$
Area = (-(-1)) - (-(1))
$$

$$
Area = 1 + 1 = 2
$$

### Final Answer

The area under the curve of $f(x) = \sin(x)$ from $x = 0$ to $x = \pi$ is **2**.
