## 10. Kinematics

We are given the position vector of a point M moving in 3D space:

$$
\vec{r}(t) = (a\cos(\omega t), b\sin(\omega t), bt)
$$

where $a$, $b$, and $\omega$ are positive constants. 

---

### a) Find the equation of the point's trajectory

The position vector gives us the parametric equations for the coordinates:
1. $x(t) = a\cos(\omega t)$
2. $y(t) = b\sin(\omega t)$
3. $z(t) = bt$

To find the spatial trajectory, we need to eliminate the parameter $t$. Let's isolate the trigonometric functions in the first two equations:

$$
\frac{x}{a} = \cos(\omega t) \qquad \text{and} \qquad \frac{y}{b} = \sin(\omega t)
$$

Squaring both equations and adding them together, we use the identity $\cos^2(\theta) + \sin^2(\theta) = 1$:

$$
\left(\frac{x}{a}\right)^2 + \left(\frac{y}{b}\right)^2 = \cos^2(\omega t) + \sin^2(\omega t)
$$

$$
\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1
$$

This equation tells us that the projection of the trajectory onto the $xy$-plane is an ellipse. 
Since $z = bt$, the point moves upwards along the $z$-axis at a constant rate. The overall trajectory is an **elliptical helix** resting on the surface of an elliptical cylinder.

### b) Compute the path length from $t = 0$ to $t = t_0$

Path length $L$ is the integral of the speed $|\vec{v}(t)|$ over time:

$$
L = \int_{0}^{t_0} |\vec{v}(t)| \, dt
$$

First, we find the velocity vector by differentiating $\vec{r}(t)$:

$$
\vec{v}(t) = \frac{d\vec{r}}{dt} = \left( -a\omega\sin(\omega t), b\omega\cos(\omega t), b \right)
$$

Next, find the speed (magnitude of velocity):

$$
|\vec{v}(t)| = \sqrt{(-a\omega\sin(\omega t))^2 + (b\omega\cos(\omega t))^2 + b^2}
$$

$$
|\vec{v}(t)| = \sqrt{a^2\omega^2\sin^2(\omega t) + b^2\omega^2\cos^2(\omega t) + b^2}
$$

The path length is the integral of this expression:

$$
L = \int_{0}^{t_0} \sqrt{a^2\omega^2\sin^2(\omega t) + b^2\omega^2\cos^2(\omega t) + b^2} \, dt
$$

> **Note:** In the general case where $a \neq b$, this is an incomplete elliptic integral of the second kind and cannot be solved in terms of elementary functions. However, in the special case where $a = b$, the identity $\sin^2(\omega t) + \cos^2(\omega t) = 1$ applies, making the speed constant, and the integral simplifies to $L = t_0 \sqrt{a^2\omega^2 + b^2}$.

### c) Draw the trajectory using Python and discuss special cases

<img width="495" height="511" alt="image" src="https://github.com/user-attachments/assets/411917e4-a2f0-4ca2-ac86-91abd60b0a96" />

**Discussion of Special Cases:**

1. $a = b$ **(Circular Helix):** The cross-section of the cylinder becomes a perfect circle instead of an ellipse. The object moves upward at a constant speed, making the path length calculation completely linear and straightforward. This models the shape of a standard coil spring.
2. $\omega \to 0$: If the angular frequency approaches zero, the cosine term stays near 1 and the sine term stays near 0. The point would move in a straight line parallel to the $z$-axis at $x = a, y = 0$.
