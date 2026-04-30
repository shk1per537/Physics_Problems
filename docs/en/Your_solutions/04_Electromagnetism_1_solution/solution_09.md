## 9. Vector Lorentz Force

We are calculating the magnitude of the magnetic force acting on a moving proton using its 3D vector components. The fundamental formula for the magnetic force ($\vec{F}$) in vector form is the Lorentz force equation:

$$
\vec{F} = q(\vec{v} \times \vec{B})
$$

To solve this, we must first find the cross product of the velocity vector ($\vec{v}$) and the magnetic field vector ($\vec{B}$), and then multiply it by the scalar charge of the proton ($q$). Finally, we calculate the magnitude of the resulting force vector.

*Note: The cross product of two vectors results in a new vector that is perpendicular to both original vectors.*

---

### Part A: The Cross Product ($\vec{v} \times \vec{B}$)

**Given Vectors:**
* Velocity ($\vec{v}$) = $2\hat{i} - 4\hat{j} + 1\hat{k} \text{ m/s}$
* Magnetic field ($\vec{B}$) = $1\hat{i} + 2\hat{j} - 1\hat{k} \text{ T}$

We set up the cross product using a matrix determinant:

$$
\vec{v} \times \vec{B} = \begin{vmatrix} 
\hat{i} & \hat{j} & \hat{k} \\
2 & -4 & 1 \\
1 & 2 & -1 
\end{vmatrix}
$$

Now, we expand the determinant across the top row ($\hat{i}$, $\hat{j}$, $\hat{k}$):

$$
= \hat{i} [(-4)(-1) - (1)(2)] - \hat{j} [(2)(-1) - (1)(1)] + \hat{k} [(2)(2) - (-4)(1)]
$$

$$
= \hat{i} [4 - 2] - \hat{j} [-2 - 1] + \hat{k} [4 - (-4)]
$$

$$
= 2\hat{i} - (-3)\hat{j} + 8\hat{k}
$$

$$
\vec{v} \times \vec{B} = 2\hat{i} + 3\hat{j} + 8\hat{k}
$$

### Part B: Magnitude of the Force

**Given Constants:**
* Charge of a proton ($q$) $\approx 1.60 \times 10^{-19} \text{ C}$

Now we write the full force vector by multiplying the cross product by the charge:

$$
\vec{F} = q(2\hat{i} + 3\hat{j} + 8\hat{k})
$$

To find the *magnitude* of this force ($|\vec{F}|$), we use the 3D Pythagorean theorem on the components of our cross product, and multiply by $q$:

$$
|\vec{F}| = q \sqrt{x^2 + y^2 + z^2}
$$

$$
|\vec{F}| = (1.60 \times 10^{-19}) \cdot \sqrt{2^2 + 3^2 + 8^2}
$$

$$
|\vec{F}| = (1.60 \times 10^{-19}) \cdot \sqrt{4 + 9 + 64}
$$

$$
|\vec{F}| = (1.60 \times 10^{-19}) \cdot \sqrt{77}
$$

Since $\sqrt{77} \approx 8.775$:

$$
|\vec{F}| \approx (1.60 \times 10^{-19}) \cdot 8.775
$$

$$
|\vec{F}| \approx 14.04 \times 10^{-19} \text{ N}
$$

Adjusting to proper scientific notation:

$$
|\vec{F}| \approx 1.40 \times 10^{-18} \text{ N}
$$

### Final Answer

* The force vector acting on the proton is **$(3.2\hat{i} + 4.8\hat{j} + 12.8\hat{k}) \times 10^{-19} \text{ N}$**.
* The magnitude of this magnetic force is approximately **$1.40 \times 10^{-18} \text{ N}$**.
