## 1. Vector Algebra

We are given two vectors in $\mathbb{R}^3$:

$$
\vec{a} = [2, 1, -3], \qquad \vec{b} = [4, -2, 1]
$$

---

### a) The magnitude of each vector

For $\vec{a}$:

$$
|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{4 + 1 + 9} = \sqrt{14}
$$

For $\vec{b}$:

$$
|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{16 + 4 + 1} = \sqrt{21}
$$

### b) The dot product $\vec{a} \cdot \vec{b}$

$$
\vec{a} \cdot \vec{b} = a_x b_x + a_y b_y + a_z b_z
$$

$$
\vec{a} \cdot \vec{b} = (2)(4) + (1)(-2) + (-3)(1) = 8 - 2 - 3 = 3
$$

### c) The cross product $\vec{a} \times \vec{b}$

$$
\vec{a}\times\vec{b} = 
\begin{bmatrix}
a_y b_z - a_z b_y \\
a_z b_x - a_x b_z \\
a_x b_y - a_y b_x
\end{bmatrix}
=
\begin{bmatrix}
(1)(1) - (-3)(-2) \\
(-3)(4) - (2)(1) \\
(2)(-2) - (1)(4)
\end{bmatrix}
=
\begin{bmatrix}
1 - 6 \\
-12 - 2 \\
-4 - 4
\end{bmatrix}
=
\begin{bmatrix}
-5 \\
-14 \\
-8
\end{bmatrix}
$$

So, $\vec{a} \times \vec{b} = [-5, -14, -8]$.

### d) The angle between vectors $\vec{a}$ and $\vec{b}$

If $\theta$ is the angle between $\vec{a}$ and $\vec{b}$, then:

$$
\cos\theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}||\vec{b}|}
$$

Substituting the values we found earlier:

$$
\cos\theta = \frac{3}{\sqrt{14} \cdot \sqrt{21}} = \frac{3}{\sqrt{294}}
$$

Therefore, the angle is:

$$
\theta = \arccos\left(\frac{3}{\sqrt{294}}\right)
$$
