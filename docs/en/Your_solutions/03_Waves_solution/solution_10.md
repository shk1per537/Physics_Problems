## 10. Animation: Wave Sources

We are modeling the superposition of multiple spherical (or circular in 2D) waves propagating outward from arbitrary point sources. The displacement $u$ at any point $\vec{r}$ in space and at time $t$ caused by a single source at $\vec{r}_0$ is given by:

$$
u(\vec{r},t) = \frac{A}{|\vec{r} - \vec{r}_0|^\alpha} \sin(k|\vec{r} - \vec{r}_0| - \omega t)
$$

Where:
* $A$ is the base amplitude.
* $|\vec{r} - \vec{r}_0|$ is the Euclidean distance from the source to the point of measurement.
* $\alpha$ is the attenuation parameter determining how quickly the wave amplitude decays over distance (e.g., $\alpha = 0$ means no decay, like an ideal plane wave; $\alpha = 0.5$ represents a 2D circular wave; $\alpha = 1$ represents a 3D spherical wave intensity decay).
* $k$ is the wave number ($k = \frac{2\pi}{\lambda}$).
* $\omega$ is the angular frequency ($\omega = 2\pi f$).

### Superposition Principle

When multiple sources are placed on the canvas, the total wave displacement at any given point is the algebraic sum of the displacements from all individual sources. If we have $N$ sources located at positions $\vec{r}_{0i}$ (where $i = 1, 2, ..., N$), the total displacement $U_{total}$ is:

$$
U_{total}(\vec{r},t) = \sum_{i=1}^{N} \frac{A}{|\vec{r} - \vec{r}_{0i}|^\alpha} \sin(k|\vec{r} - \vec{r}_{0i}| - \omega t)
$$

*(Note: The interactive implementation of this mathematical model is provided in the simulator).*
