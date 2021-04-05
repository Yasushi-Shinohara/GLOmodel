# Note for the generalized Lorentz oscillator models

## The Lorentz oscillator model
We begin with a classical particle motion in a harmonic potential with a damping and an external force:  
$$
m \frac{\mathrm{d}^2 x}{\mathrm{d} t^2} = -2m\gamma\frac{\mathrm{d} x}{\mathrm{d} t} - m\omega_0^2 x + F(t).
$$

The polarization density $P$ is given by $P = Nqx$, where $N$ and $q$ are number oensity of the particle and the charge of the particle.
The electric force on the particle is given as $F(t) = qE(t)$.
So, the equation of motion is expresseds as  
$$
\frac{\mathrm{d}^2 P}{\mathrm{d}t^2} +2\gamma\frac{\mathrm{d} P}{\mathrm{d} t}  +\omega_0^2 P
=
\epsilon_0 \omega_p^2 E(t),
$$
where $\omega_p^2 = \frac{Nq^2}{m\epsilon_0}$.

### Dielectric function
We seek a stational solution of the polarization under a monochromatic osccilatory field $E(t) = E_0 e^{\mathrm{i}\omega t}$.
We assume osccilation for the polarization with the same frequency as the driving field,  
$$
P(t)
=
P_0 e^{\mathrm{i}\omega t}.
$$
We have an equation for the complex amplitude,
$$
P_0
=
\frac{\epsilon_0 \omega_p^2}{-\omega^2 + 2\mathrm{i}\gamma \omega + \omega_0^2} E_0
=
\chi(\omega) E_0,
$$
where $\chi$ is the electric susceptibility.