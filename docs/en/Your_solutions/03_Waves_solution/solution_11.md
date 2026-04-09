## 11. Animation: Two-Slit Interference

We are simulating Thomas Young's classic double-slit experiment. In this model, two slits act as coherent point sources of waves. According to the superposition principle, the total displacement of the resultant wave at any point in space is the algebraic sum of the displacements from the individual waves.

The formula for the total displacement $u(\vec{r},t)$ at a position vector $\vec{r}$ and time $t$ is given by:

$$
u(\vec{r},t) = \frac{A}{|\vec{r} - \vec{r}_1|} \sin(k|\vec{r} - \vec{r}_1| - \omega t) + \frac{A}{|\vec{r} - \vec{r}_2|} \sin(k|\vec{r} - \vec{r}_2| - \omega t)
$$

Where:
* $\vec{r}_1$ and $\vec{r}_2$ are the position vectors of the two slits.
* $A$ is the base amplitude.
* $k$ is the wave number, which is inversely proportional to the wavelength: $k = \frac{2\pi}{\lambda}$.
* $\omega$ is the angular frequency.
* $d = |\vec{r}_1 - \vec{r}_2|$ is the physical distance between the two slits.

By varying the wavelength $\lambda$ and the slit separation distance $d$, you can observe how the spatial distribution of constructive and destructive interference (the interference pattern) changes. 

*(Note: The interactive implementation of this mathematical model is provided in the simulator below).*
