## Momentum Through Internal and External Forces

Suppose all particles interact with the particles in the system and outside as well, Then,
$$
\begin{align}
f_{j} &= \frac{dp_{j}}{dt} \\ \\
f_{j} &= f_{j}^{int} + f_{j}^{ext} \\ \\
\sum_{j=1}^{N}f_{j}^{int} &+ \sum_{j=1}^{N} f_{j}^{ext} = \sum_{j=1}^{N} \frac{dp_{j}}{dt}

\end{align}
$$
We know by Newton's Third law $i.e$, The force between any two particles are equal and opposite so their sum is zero
Thus,
$$
\sum_{j=1}^{N} f_{j}^{int} = 0
$$
Hence,
$$
\begin{align}
P \equiv \sum_{j=1}^{N}p_{j} \\  \\
F_{ext} = \frac{dP}{dt}
\end{align}

$$

This shows how Internal and External Forces affect the momentum of the system

---

## Center of Mass

$$
\begin{align}
F &= \frac{dP}{dt} \\ \\
F &= M\ddot{R} \\ \\
P &= \sum_{j=1}^{N} m_{j}\dot{r_{j}} \\ \\
M\ddot{R} &= \frac{dP}{dt} = \sum_{j=1}^{N} m_{j}\ddot{r_{j}}

\end{align}
$$
***which is true only if,***
$$
R = \frac{1}{M}\sum_{j=1}^{N}m_{j}r_{j}
$$
We define $R$ as a vector from origin to the center of mass

##### Note:
> As far as translation of the center of mass is concerned $F = M\ddot{R}$ is valid for any system of particles
> $i.e,$ the system of particles obey Newton's Third Law

Furthermore,
```ad-note
title: ~
$\qquad \qquad \qquad R = \frac{1}{M}\int r \, dm  \qquad -\text{when N} \rightarrow \infty$
```

#### Calculating COM of a Rod
$$
\begin{align}
\lambda &= \lambda_{o} \left( \frac{x}{L} \right)  \\ \\
M &= \int  \, dm  \\
&=\int_{0}^{L} \lambda \:\: dx \\
&= \int_{0}^{L} \frac{\lambda_{o}x}{L} \, dx  \\
&= \frac{1}{2}\lambda_{o}L \\ \\
R &= \frac{1}{M} \int \lambda \:r \, dx  \\
&=\frac{2}{\lambda_{o}L} \int _{0}^{L} \frac{(x \mathbf{i}+0\mathbf{j}+0\mathbf{k})\lambda_{o}x}{L} \, dx  \\
&= \frac{2}{L^{2}} \left[ \frac{x^{3}}{3} \right]^{L}_{0} \mathbf{i} \\
&=\frac{2}{3}L \:\:\mathbf{i}
\end{align}
$$





