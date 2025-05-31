Chapter 12
-------------
**Stress**: Force per area $(\sigma = \frac{F}{A})$
**Strain**: Relative change in length $(\epsilon = \frac{\Delta L}{L_0})$
**Young's Modulus** ($Y$)


Extra:
Speed of Sound in Materials
 $$v = \sqrt\frac{B}{\rho}$$

B is the Bulk modulus. $\rho$ is density, $M/V$
Bulk modulus is how hard it is to squeeze (compress) without changing its shape. Applies for gases/liquids.

Bulk modulus for gases:
$$B = -V \frac{dP}{dV}$$

*Types of Compression Processes*
Isothermal Process, gas is compressed slowly, temperature is constant.
$PV$ constant, $B_T = P$

Adiabatic Process, gas is compressed rapidly; no heat exchange, 

$$PV^{\gamma} = \text{constant}$$
$\gamma$ is the ratio of specific heats.
$$B_S = \gamma P$$

Chapter 13
----
$$F = G \frac{m_1 m_2}{r^2}$$
$$g = G \frac{M}{r^2}$$
$$U = -G \frac{m_1 m_2}{r}$$
$$E = KE + U = -\frac{GMm}{2r}$$
Negative total energy means the satellite is **bound** (it cannot escape).
Minimum speed to escape from a planet's gravity (i.e. to reach E = 0) is:

$$ v_{esc} = \sqrt\frac{2GM}{r}$$
from $\frac{1}{2}mv_{esc}^2 = \sqrt\frac{2GM}{r}$ 

**Kepler Laws**
* **1st Law**: Law of Ellipses 
 Every planet (or satellite) moves in an ellipse with the Sun (or Earth) at one focus. Ellipse: An oval shape. A circle is a special case of an ellipse. 
 
* **2nd Law**: Law of Equal Areas 
 A line joining a planet to the Sun sweeps out equal areas in equal times. This means: Planets move faster when they are closer to the Sun and slower when farther away.

Angular momentum is conserved, $L = mr^2\frac{d\theta}{dt}$
Area swept out per unit time $\frac{dA}{dt} = \frac{1}{2}r^2\frac{d\theta}{dt}$
(Area of slice of circle, tiny angle planet moves $d\theta$)

* **3rd Law**: Law of Periods The square of the orbital period $T$ of a planet is proportional to the cube of the average distance $r$ from the Sun: 
 $$T^2 \propto r^3 \text{ or }
  \frac{T^2}{r^3} = \text{constant}$$
  For objects orbiting the same central body (e.g., Earth), this constant is the same.

This comes from $v =  \frac{2\pi r}{T}$ using satelite speed.

**Speed of Satellites**
$$F_{gravity} = F_{centripetal}$$

Chapter 14
-------------
$$\rho = \frac{m}{V}$$
$$P = \frac{F}{A}$$
$$P = P_0 + \rho gh$$ $h$ is depth.

**Pascal’s principle**: A change in pressure at any point in a confined fluid is transmitted equally throughout the fluid.

**Archimedes’ principle (Buoyancy)**: An object in a fluid experiences an upward force equal to the weight of the fluid it displaces.

$$F_{buoyant} = \rho_{fluid}V_{displaced}g$$

 **Continuity equation for incompressible fluids**: $$A_1 v_1 = A_2 v_2$$(conservation of mass, mass of fluid passing through each section/time must be same).

 **Bernoulli's equation**:
$$P + \frac{1}{2} \rho v^2 + \rho g y = \text{constant}$$(essentially conservation of energy for flowing fluids)

**Uses**:
* If you know the pressure and speed at one point in flowing fluid, you can find them at another.
* Explaining airplane lift. (low $P$, wing is pushed up)
* Why water speeds up as it moves from a wider to narrower pipe

Chapter 15
---
Back-and-forth repetitive movement around a central point.

**Amplitude** ($A$): The maximum distance from the center (rest position). 
**Period** ($T$): Time for one complete cycle (back and forth). 
**Frequency** ($f$): Number of cycles per second $(f = \frac{1}{T}$)
 **Restoring force**: Force that tries to bring the object back to the center.

$$x(t) = Acos(\omega t + \phi)$$$\omega = \sqrt\frac{k}{m} = \frac{2\pi}{T}$
$\phi=$ phase


**Force in SHM:**
$$F = -kx$$

**Energy of the Simple Harmonic Oscillator**
$$ E = \frac{1}{2}kA^2$$Energy switches between potential $(\frac{1}{2}kx^2)$ and kinetic $(\frac{1}{2}mv^2)$.

You use the first derivative of the wave equation to find velocity, then use $\frac{1}{2}kx^2$ and $\frac{1}{2}mv^2$ to find total energy.

**The Pendulum**
SHM can be seen as the *projection* of uniform circular motion onto one axis, helping visualize phase, amplitude and period.

***For small angles***, simple pendulum behaves like SHM.
$$ T = 2\pi \sqrt\frac{\ell}{g}$$$\ell =$ length.

**Damped Oscillations**
Oscillations where energy is lost (for example, due to friction).
The amplitude of the oscillation gets smaller with time.
$$ F_{damping} = -bv$$$b =$ is damping constant (how strong it is).

$$F_\text{total} = -kx - b \frac{dx}{dt}$$$-kx$ (tries to pull the mass back to center)
$-b\frac{dx}{dt}$ (opposes motion, proportional to speed)
$$F = ma$$$$m 
\frac{d^2x}{dt^2} = -b \frac{dx}{dt} - kx$$$$m \frac{d^2x}{dt^2} + b \frac{dx}{dt} + kx = 0$$

**Exponential Decay**

Exponential decay describes a process where a quantity decreases by a constant percentage (or fraction) over equal time intervals.
$$y(t) = y_0e^{-\lambda t}$$$\lambda$: decay constant (how fast it shrinks)

**Underdamped**: Oscillates, but ampitude decreases over time.

$$x(t) = A e^{-\gamma t} \cos(\omega' t + \phi)$$

$A$: initial amplitude 
$e^{-\gamma t}$: exponential decay (shrinking envelope) 
$\omega'$: new (lower) angular frequency 
$\gamma = \frac{b}{2m}$: damping rate

**Critically damped**: Returns to equilibrium as fast as possible without *oscillating*.
**Overdamped**: Returns slowly, no oscillation.

**Forced Oscillations**
An oscillating system is *pushed* or *driven* by an external, **periodic** force. (like pushing a child on a swing at regular intervals).

$$m \frac{d^2x}{dt^2} + b \frac{dx}{dt} + kx = F_0 \cos(\omega_\text{drive} t)$$$F_0$: amplitude of the driving force
$w_{drive}$: driving frequency.

*Key idea* is, system responds to both **its natural frequency** and **frequency of the driving force**.

**Resonance**: If the driving frequency matches the system's natural frequency, the amplitude can become very large (even with *damping*).

$$A_\text{drive} = \frac{F_0/m}{\sqrt{(\omega_0^2 - \omega_\text{drive}^2)^2 + (2\gamma \omega_\text{drive})^2}}$$

from the second dertivative of wave equation

$A_{drive}$ is the amplitude of the object's oscillation.
$\gamma = \frac{b}{2m}$, damping rate
$\omega_0 = \sqrt\frac{k}{m}$, natural angular frequency

When $w_{drive}$ is close to natural frequency, $A_{drive}$ is large--**resonance**. If damping $b$ is large, the amplitude is smaller.

Chapter 16
-----
A wave is a **disturbance** (a change in position, pressure, etc.) that travels through a *medium* (like air, water, string) carrying **energy** from one place to another.

Particles themselves *mostly* move back and forth or up and down--**they do not travel *with* the wave**, the ***disturbance moves***.

Most basic form of a travelling wave (moving in the $+x$ direction is:

$$ y(x,t) = f(x - vt)$$$y$ is the displacement at position $x$ and time $t$.
$v$ is the wave speed.
$f$ is any function that represents the **shape** of the pulse.

We are interested in sinusoidal waves:

$$ y(x, t) = Asin(kx - \omega t + \phi)$$$k = \frac{2\pi}{\lambda}$: wave number
$\omega = 2\pi f$
$\phi$: phase constant

*Quick note*: if $-\omega$; then the wave moves along the positive direction, if $+\omega$ vice versa.

**Speed of Waves on Strings**
The speed at a which a wave travels along a **stretched string** depends on the string's tension and its mass per unit length.

$$ v = \sqrt\frac{T}{\mu}$$
$T$: tension force
$\mu$: mass per unit length of the string ($\frac{m}{L}$)

**Reflection and Transmission**
When a wave reaches a boundary between two different media (or a change in properties like tension or thickness), part of the wave is reflected (bounces back) and part is transmitted (passes through).

*Reflection*
When a wave hits a boundary, some of its energy goes back toward where it came from.
* If the boundary is fixed (like tying the string to a wall), the reflected wave inverts (flips upside down).
* If the boundary is free (like a loose ring), the reflected wave does not invert.

*Transmission*
Some energy continues into the new medium (for example, a thick string joined to a thin string)

The transmitted wave may change speed and wavelength, depending on the properties (tension, mass per length) of the new medium.

Wave behavior at boundaries:
* If moving from lighter to heavier string: Reflected wave inverts. 
* If moving from heavier to lighter string: Reflected wave keeps its orientation.
* Transmitted wave keeps its orientation either way.

**Rate of Energy Transfer by Sinusoidal Waves on Strings**

A sine-shaped wave on a string carries *energy* along the string, the rate at which energy is transferred is called **power**.

$$ P= \frac{1}{2}\mu\omega^2 A^2v$$

Let's show the derivation.

First:
$$P = \frac{\text{work}}{\text{time}} = F\frac{\Delta x}{\Delta t}$$
Instantaneous power:
$$P = F\frac{dx}{dt} = Fv$$

Wave equation for a sinusoidal wave is:
$$ y(x,t) = Asin(kx-\omega t)$$
$$ y'(x,t)= v_y(x, t) = \frac{\partial y}{\partial x} = -A\omega cos(kx-\omega t)$$

We need the vertical component of $F_T$,
$$F_{vertical} = F_T sin\theta$$ For small angles,
$$\sin\theta \approx \tan\theta = \frac{\partial y}{\partial x}$$Thus,
$$F_{vertical} = F_T\frac{\partial y}{\partial x}$$
Power at a point is,
$$P(x, t) = F_T\frac{\partial y}{\partial x} \cdot \frac{\partial y}{\partial t}$$
$$P(x, t) = F_{T} \left[A k \cos(kx - \omega t)\right] \cdot \left[-A \omega \cos(kx - \omega t)\right]$$
$$= -F_{T} A^2 k \omega \cos^2(kx - \omega t)$$

The average of $cos^2(x)$, $x$ is arbitrary, over a full cycle is $\frac{1}{2}$.
Thus,
$$\langle P \rangle = -F_{T} A^2 k \omega \times \frac{1}{2}$$
We take magnitude for power,
$$\langle P \rangle = \frac{1}{2} F_{T} k \omega A^2$$
Substituting $F_{T} = \mu v^2$ and $k = \omega/v$,
$$\langle P \rangle = \frac{1}{2} \mu v^2 \cdot \frac{\omega}{v} \cdot \omega A^2 = \frac{1}{2} \mu v \omega^2 A^2$$$$\boxed{ P = \frac{1}{2} \mu \omega^2 A^2 v }$$

**The Linear Wave Equation**
The linear wave equation is a mathematical relationship that describes *how waves move through a medium* (like a string).

$$\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2 y}{\partial t^2}$$$y(x, t)$: Displacement of the string at position \(x\) and time 
$v$: Speed of the wave along the string

*Key concepts:*

This equation says: The way the shape of the wave curves in space $\frac{\partial^2 y}{\partial x^2}$ is related to the way it curves in time $\frac{\partial^2 y}{\partial t^2}$, scaled by the square of the wave speed. 

Any function of the form $y(x, t) = f(x - vt)$ or $y(x, t) = f(x + vt)$ is a solution. 

This equation works for many types of waves, not just on strings, as long as the wave is “linear” (the properties of the medium don’t change with the size of the disturbance).

Chapter 17
-----
**Mechanical waves** need a medium, like sound in air, ripples on water.
**Electromagnetic waves** do not need a medium, like light.

**Transverse waves**, particles move perpendicular to the wave direction, like light or wave on a string.

**Longitudinal waves**, particles move parallel to the wave direction (like sound waves in air)

Sound is a **longitudinal mechanicel wave in a medium**, fastest in solids, slowest in gases.

$$ v = f\lambda$$


**Doppler Effect**: The change in frequency (or pitch) of a wave as measured by an observer, because the source of the wave and/or the observer are *moving relative to each other*.

If the source and observer are moving **towards each other**, observed frequency goes **up**.

If they move **apart**, observed frequency goes **down**.

$$f' = f(\frac{v\pm v_0}{v\pm v_s})$$
$v$ is speed of sound in air
$v_o$: speed of observer, positive if moving towards the source
$v_s$: speed of source, positive if moving away from the observer

**What if both of them moves?**
this is stupid
*02:17, May 28th, 2025.*

*Same direction, source behind*
If source is behind and faster than the observer,
 $$f' = f \frac{v - v_o}{v - v_s}, f' > f$$If source is behind and slower than the observer, 
$$f' = f \frac{v - v_o}{v - v_s},  f' < f$$If source is behind and at the same speed with the observer, 
$$f' = f$$

*Same direction, observer behind*
If observer is behind and faster than the source,
$$f' = f \frac{v + v_o}{v + v_s},f' > f$$
If observer is behind and slower than the source,
$$f' = f \frac{v + v_o}{v + v_s},f' < f$$

Opposite directions makes sense.

Opposite directions, they're getting away from each other, $$f' = f \frac{v - v_o}{v + v_s}, f' < f$$Opposite directions, they're getting closer, $$f' = f \frac{v + v_o}{v - v_s},f' > f$$

The Doppler effect happens because the distance between the source and observer changes while waves are being emitted, which changes how often the wave crests reach the observer.

If the source and observer are moving closer together, the observer **meets wave crests more often (higher frequency)**. If they are moving apart, the observer **meets wave crests less often (lower frequency).**

Chapter 18
--------
**Superposition principle** is when two or more waves overlap, total displacement at any point is simply the sum of the individual *wave displacemetns* at that point.

In a linear system, waves simply add together---no change to their basic shape or frequency.

In a nonlinear system, things can be complicated, thus; this principle only works if it is a linear system.

**Interference** is the result of superposition, if waves add up (there is bigger amplitude), it is **constructive interference**. If waves subtract (there is smaller and/or zero amplitude), it is **destructive interference**.

**Constructive**: When **crests** meet **crests**, or **troughs** meet **troughs**, they reinforce each other. 

**Destructive**: When a **crest** meets a **trough**, they can cancel out.

**Standing Waves**
When two **identical** waves travel in opposite directions and **overlap** (such as wave reflecting back on a string).

**Nodes** are points that never move (zero amplitude).
**Antinodes** points with maximum movement (maximum amplitude).

Wave appears "stationary"---it vibrates in place.

The standing wave can be written as
$$y(x,t) = 2A \sin(kx) \cos(\omega t)$$

Here, $2A$ is the maximum amplitude, $\sin(kx)$ describes the stationary pattern and $\cos(\omega t)$ describes the time oscillation at each point.

Nodes are $\sin(kx) = 0$ (zero displacement, always at the ends for fixed boundaries)
Antinodes are $sin(kx) = \pm 1$ (max displacement, between nodes)

**Fixed at both ends**
If a string fixed at both ends, when a wave hits the end it reflect backs, original and reflected waves travel in opposite directions and overlap. At certain frequencies, this overlap creates a standing wave---th string ibrates in segments.

**Nodes** are points on the string that never move ($\Delta$ = 0), **always** at the fixed ends.
**Antinodes** are points with the largest vibration (maximum displacement). It is located between **nodes**.

**What are Harmonics/Normal Modes?**
Only certain "wave patterns" fit---that is both fixed ends are nodes and so on, depending on the string length **L**.

The **fundamental frequency** aka **first harmonic** has just two nodes (ends) and one antinode in the middle.

Higher harmonics fit more "loops" on the string.

$$\lambda_n = \frac{2L}{n}$$$$f_n = n\frac{v}{2L}$$
* $n = 1, 2, 3, \ldots$ (harmonic number)

**Harmonic number** $n$ tells you how many half wave-lengths fit in the length $L$ of the string.

Think the formula as:

$$\frac{\lambda_n}{2} \cdot n = L$$
Now it makes more sense when thinking the definition.
A loop is node, anti-node to a node, each loops is $\frac{\lambda}{2}$ wave-length.

**Standing Waves in Air Columns**
Tubes with air inside, if both ends are open, then it behaves like a string of both fixed ends.

If one end is closed and the other is open, then:
**Closed end is a node** (as no air movement here), open end is an anti-node.

Only odd harmonics are allowed $n=1,3,5,...$
$$\lambda_n = \frac{4L}{n}$$$$f_n = n \frac{v}{4L}$$$$n = 1, 3, 5, ...$$

For a closed-open tube, the harmonic number tells you **how many quarter-wavelenghts are in the tube**.

$$\lambda_n = \frac{4L}{n}$$$$\frac{\lambda_n}{4} \cdot n = L$$


Distance between an antinode and a node is $\frac{\lambda}{4}$, is A-N and is called the **first harmonic**. $(n = 1)$

Next wave pattern is A-N-A-N, called the **third harmonic**, total distance is $\frac{3\lambda_3}{4}$, thus $\frac{3\lambda_3}{4} = L$, then $\lambda_3 = \frac{4L}{3}$

Each **loop** = one half-wavelength $(\lambda /2)$
In an **open-open** tube, **harmonic number** $n$ = **number of loops**.
In a **closed-open** tube, $n/2$ = **number of loops**.

As $n$ gives you the number of quarter-wavelengths in the tube, your total wavelength is equal to $n\frac{\lambda}{4}$, a loop is of length $\frac{\lambda}{2}$, then the number of loops in a closed-open end tube is $$\text{Loops} = \frac{n\frac{\lambda}{4}}{\frac{\lambda}{2}}$$ $$ = \frac{n}{2}$$

**Beats**
If two sound waves have similar (but not the same) frequencies, they combine to produce a new sound whose amplitude varies in time. **The pulsing change in loudness when two close but different frequencies are played together**.

**Beat frequency**: The rate at which loudness fluctuates. 


$$f_{\text{beat}} = |f_1 - f_2|$$
For beats, we usually care about the sound at a **fixed positions**, at a fixed spot, $x$ is constant, so $kx$ just becomes a constant phase shift.
The important changes (the beats) happen over **time**, not over space.

$$y_1 = A \sin\left(2\pi f_1 t\right)$$$$y_2 = A \sin\left(2\pi 
f_2 t\right)$$$$\sin A + \sin B = 2 \sin\left(\frac{A+B}{2}\right) \cos\left(\frac{A-B}{2}\right)$$$$y = y_1 + y_2 = 2A \cos\left(\pi (f_1 - 
f_2)t\right) \sin\left(2\pi f_{\mathrm{avg}} t\right)$$

The pitch you hear is $f_{avg}$, the loudness goes up and down at the beat frequency $(|f_1-f_2|)$
$$f_{\mathrm{avg}} = \frac{f_1 + f_2}{2}$$

The $sin$ term oscillates rapidly at the average frequency, which is what you perceive as the pitch. 
The $cos$ term changes slowly, controlling the amplitude (loudness) over time.

Chapter 19
-------
**Temperature** is a measure of the *average kinetitc energy* of the **particles** in substances.

It tells us how hot/cold something is, but it's tied to *particle motion*.

**Thermal Equilibrium** is when two objects are at the same temperature, no heat flows between them.

**Zeroth Law of Thermodynamics**: If objects A is in thermal equilibrium with B, B with C, then A is in C. (like transitivity in math).

Standard reference temperatures used to define temperature scales and calibrate thermometers.

Celsius $^{\circ}\mathrm{C}$, based on water's freezing $(0^{\circ}\mathrm{C})$ and boiling $(100^{\circ}\mathrm{C})$ points.

Kelvin $\mathrm{K}$, absolute temperature scale, $0 \space \mathrm{K}$: absolute zero (the coldest *possible* temperature)
$$T_{\mathrm{K}} = T_{\mathrm{C}} + 273.15$$$$T_{\mathrm{C}} = \frac{5}{9}(T_\mathrm{F} - 32)$$
$$0^{\circ}\mathrm{C} = 32\mathrm{F}$$$$100^{\circ}\mathrm{C} = 212\mathrm{F}$$

Thermometers rely on some property changes with temperature---like the volume of mercury or alcohol in a glass tube, or electrical resistance.

**Thermometric property** is a physical property that changes in a known way with temperature.

**Liquid-in-glass thermometers**: Use expansion of liquids (like mercury, alcohol). 
**Electric thermometers**: Use resistance changes in metals (resistance thermometers, thermistors).
**Gas thermometers**: Very accurate, use the pressure of gas at constant volume.

**Specific heat** ($c$): Amount of heat needed to raise 1 kg of a substance by 1°C (or 1 K).
$$Q = mc\Delta T$$

**Molar specific heat**: Amount of heat required to raise the temperature of 1 mole of a substance by $1 \space \mathrm{K}$ or $1^{\circ}\mathrm{C}$.

$$Q = mc\Delta T = nC\Delta T$$

**Calorimeter:** Device to measure heat transfer.

**Calorimetry:** The process of measuring heat by observing temperature changes in a known mass of water (or other substance). Heat lost = heat gained: In isolated systems, heat gained by one part equals heat lost by another (assuming no heat loss to surroundings).

**Latent heat ($L$)**: Heat required for a phase change (solid↔liquid, liquid↔gas) at constant temperature.

$$Q = mL$$

Latent heat of fusion: For melting/freezing.
Latent heat of vaporization: For boiling/condensing.
During phase change, temperature stays constant—even as *heat is added or removed*.

**Thermal Expansion**
Most materials expand when **heated**, contract when **cooled**.

$$\Delta L = \alpha L_0 \Delta T$$$$\Delta V = \beta V_0 \Delta T$$

$\alpha$: coefficient of *linear* expansion.
$\beta$: coefficient of *volume* expansion.

**Absolute Zero** is the temperature **all molecular motion stops**. $(0\space\mathrm{K} = 273.15^{\circ}\mathrm{C})$

**An Ideal Gas** made up of particles that:
* do not interact with each other (no forces between them *except* during collisions)
* take up no space themselves (particles are points)
* collisons between particles/and with walls are perfect elastic (no energy lost)

$$PV = nRT$$
$R$: universal gas constant ($8.314 \space\mathrm{J}/\mathrm{mol}\cdot \mathrm{K})$

**Standart temperature and pressure* is $0^{\circ}\mathrm{C}, 1 \space \mathrm{atm}$,  1 mole of an ideal gas occupies $22.4 \space\mathrm{L}$.

**1st Law of Thermodynamics**
***Energy can neither be created nor destroyed, only transferred or transformed.***

It is a principle of energy conservation for thermodynamic systems.

$$\Delta E_{\text{int}} = Q - W$$
$\Delta E_{\text{int}}$: Change in internal energy (the energy inside a system due to the motion and arrangement of its molecules)
$Q$: **Heat added to the system** (energy transferred in due to *temperature difference*)
$W$: Work done by the system (**energy the system transfers to its surroundings** by doing work)

**Important!**
As $E_{int} \propto T$, if $\Delta T = 0$ then $\Delta E_{int} = 0$ then $Q = W$

**Sign conventions**
$Q > 0$: Heat/energy added to system
System gets warmer.

$Q < 0$: Heat/energy removed from system
 System gets cooler.
 
$W > 0$: Work done by the system (expansion)
System pushes against surroundings, like gas expanding.

$W< 0$: Work done on the system (compression)
Surroundings compress the system, like squeezing a gas.

$\Delta E_{\text{int}} > 0$: Internal energy increases (system’s molecules **move faster** or get rearranged to higher energy states).

$\Delta E_{\text{int}} < 0$: Internal energy decreases (molecules **move slower** or rearrange to lower energy states).

$E_{total} = E_K + E_P + E_{int}$

*Internal Energy $(E_{int})$:*
Only the **microscopic energy** inside the system, random motion ($E_K$) and interactions ($E_P$) of atoms an molecules.

Does not include energy due to the system's overall motion or position.

Work $(W)$
If $W = F\Delta x$ and $F = PA$ then $$W = P \Delta V$$
Also $$=\int_{V_i}^{V_f}PdV$$

**Thermal Processes**
There are ways a gas can change its state (pressure, volume, temperature). Each type has a special "constant" and a unique energy relationship.

**Quasistatic (reversible) process**: A process that happens slowly enough for the system to remain in equilibrium at all times.

**Isothermal Process** (constant temperature)
$T = \text{constant}$
$\Delta E_{int} = 0$ (for an ideal gas)
All heat added is converted to work:
$$Q = W$$
On a PV diagram: curve (not a straight line), called an **isotherm**)

**Adiabatic Process** (no heat exchange)
$Q = 0$
$\Delta E_{int} = -W$
On a PV diagram: steeper curve than isothermal.

**Isochoric Process** (constant volume)
$\Delta V = dV = 0$
 as $W  = 0$, $\Delta E_{int} = Q$
 On a PV diagram: vertical line (volume doesn't change).

**Isobaric Process** (constant pressure)
$P = \text{constant}$
$$W= P\Delta V$$

**Energy (PV) Diagrams and Cycles**
Area under the curve between two volumes represents the **work done by the gas** during **expansion**/**compression**.

A **cyclic process** is a sequence of processes that returns the gas o its starting state. Paths form a closed loop on the PV diagram.

Over a complete cycle 
$$\Delta E_{int} = 0$$then$$Q = W$$

If the net work done **by the gas** $(W > 0)$, direction of the loop is **clockwise**.

If the net work done **on the gas** (W < 0), direction of the loop is **counter-clockwise.**

The amount of heat $(Q)$ and work $(W)$ depends on the **path taken**.
Only $\Delta E_{int}$ depends solely on the states.

$Q$ and $W$ are not state functions (they do not describe the system’s state, but how you got there). $\Delta E_{\text{int}}$ is a state function.

**Very Important!*
At constant volume, $W = 0$, heat added; all heat goes to increasing internal energy:
$$Q_v = nC_v\Delta T  = \Delta E_{int}$$At constant pressure, the gas can expand and do work, so more heat is needed for the same temperature change:
$$Q_p = nC_p \Delta T$$Work is done if volume changes thus
$$\Delta E_{int}  = Q_p - W$$For an ideal gas!
$$c_p - c_v = r$$
$r$ is specific heat constant, depeds on the gas 
($r = R/M$ where M is molar mass in kg/mol).
$c_p$ and $c_v$ are specific heats.
$$C_p - C_v = R$$
$R$ is universal gas constant.
$C_p$ and $C_v$ are molar specific heats.

For a monatomic ideal gas, the **intergal energy** is
$$E_{int} = n\bigg( \frac{3}{2}R\bigg) T = \frac{3}{2}nRT$$

How a gas behaves when it expands/contracts without exchanging heat. (**adiabatic process**).

Tells you how much more heat is needed at constant pressure than at constant volume.

$$\gamma= \frac{c_p}{c_v} = \frac{C_p}{C_v}$$
When $Q = 0, \gamma$ appears in the equations.
$$PV^{\gamma} = \text{constant}$$

**Finding the speed of the sound**
$$v = \sqrt\frac{\text{restoring force}}{\text{intertia}}$$
As we remember, restoring force is the tendency of the medium to return to its original state after being disturbed (like tension in a string, elasticity in a spring).

Inertia: The resistance of the medium to being moved or accelerated (like mass or density.

Sound wave in a gas:

$$v = \sqrt\frac{B}{\rho}$$
As we know, 
$$B = -V\frac{dP}{dV}$$
Also
$$PV^{\gamma} = \text{constant}$$$$\frac{d}{dV}(PV^{\gamma}) = 0$$
$$\gamma PV^{\gamma - 1} + V^{\gamma}\frac{dP}{dV} = 0$$
$$\frac{dP}{dV} = -\gamma\frac{P}{V}$$
Plug this into definition of $B$.
$$ B = -V\bigg(-\gamma\frac{P}{V}\bigg)$$
$$ B = \gamma P$$

We again know
$$v = \sqrt\frac{\gamma P}{\rho}$$

Now we relate pressure and density using the ideal gas law.
$$PV = nRT$$
$$PV = m/M\cdot RT$$
$$P = \frac{\rho RT}{M}$$
$$v = \sqrt\frac{\gamma RT}{M}$$

**Energy Transfer Mechanisms in Thermal Processes**

**Conduction** is the transfer of thermal energy through a material without the movement of the material as a whole. It happens by **direct contact:** Hot, fast-moving molecules bump into slower, cooler ones and transfer energy. Mostly in solids, also in liquids/gases (less effective).

$$Q = \frac{kA \Delta T}{d} t$$

$Q$: heat transferred (Joules)
 $k$: thermal conductivity (how well a material conducts heat)
$A$ area through which heat is transferred
$\Delta T$: temperature difference
 $d$: thickness of the material
  $t$: time

**Convection** is the transfer of heat by the bulk movement of a fluid (liquid or gas). As parts of a fluid are heated, they become less dense and **rise**, while cooler, denser parts **sink.** This sets up a **convection current**.

**Natural convection:** Movement due to density changes from heating (like boiling water). 
**Forced convection**: Movement caused by a fan or pump (like air blown by a hairdryer).

$$Q = hA \Delta T t$$
$h$: convection heat transfer coefficient (depends on fluid and flow)
$A$: surface area

**Radiation** is the transfer of energy by electromagnetic waves (mainly infrared). No medium needed—can occur through a vacuum (like sunlight reaching Earth).
$$P = \sigma e A T^4$$
$P$: power radiated (watts, J/s) 
$\sigma$: Stefan-Boltzmann constant $(5.67 \times 10^{-8} \frac{\text{W}}{\text{m}^2\cdot\text{K}^4}$)
 $e$: emissivity (how well an object radiates, from 0 to 1) 
 $A$ surface area
$T$: absolute temperature (Kelvin)

**All objects emit radiation**: Hotter objects emit **more energy**, and at shorter wavelengths.

Chapter 21
---
$$PV = Nk_BT$$
$k_B$: Boltzmann constant ($1.38 \times10^{-23} J/K)$

**Pressure from molecular collisions**
$$P = \frac{1}{3} \frac{N}{V} m \overline{v^2}$$
$\overline{v^2}$: average of the square of the speed

Pressure is caused by molecules hitting the container walls.

**Molar Specific Heat of an Ideal Gas**
$$Q = nC\Delta T$$$$C_p = C_v + R$$

It takes **more energy** to heat a gas at constant pressure ($C_p$) than at constant volume ($C_v$) because the gas does work as it expands.

 **The Equipartition of  Energy**   
**Equipartition theorem:** Each degree of freedom of a molecule has average energy $\frac{1}{2}k_BT$
**Degree of freedom:** An independent way a molecule can move (translation, rotation, vibration). For a monatomic gas (like He, Ne): 3 degrees (x, y, z translation). For a diaotmic gas: 5 degrees (x, y, z + 2 rotational)

$k_B$ tells you how much energy **one molecule** has per degree of temperature.
$k_B \times N_A$ gives you $R$, energy per mole per degree of temperature.

$$\text{Average energy per molecule} = \frac{f}{2}k_BT$$
$f$ is the number of degrees freedom

If we multiply by $N$, as in $N$ molecules, as $N = nN_A$ and $k_BN_A = R$

$$\text{Total internal energy} = U = \frac{f}{2} nRT$$

**Adiabatic Processes for an Ideal Gas**
As it is adiabatic, no heat is transferred in or out ($Q = 0$)
$$PV^{\gamma} = \text{constant}$$
$$TV^{\gamma -1} = \text{constant}$$
$$\gamma = \frac{C_p}{C_v}$$

Gas cools down if it expands adiabatically,; heats up if compressed.

**Distribution of Molecular Speeds**
**Not all molecules** move at the same speed---they follow a spread called the **Maxwell-Boltzmann distribution**.
At any temperature, some move slowly, some extremely fast.

**Root mean square speed:**
The square root of the average of the squares of all molecular speeds. It’s important for kinetic energy calculations. It gives more weight to faster molecules.
$$v_{\text{rms}} = \sqrt{\frac{3k_BT}{m}}$$
**Most probable speed**:
The speed that the largest number of molecules of have, peak of distribution.
$$v_{\text{mp}} = \sqrt{\frac{2k_BT}{m}}$$
**Average speed:**
The mathematical average of all molecular speeds.
$$v_{\text{avg}} = \sqrt{\frac{8k_BT}{\pi m}}$$

As temperature increases, molecules move faster (all three speeds increase). The distribution gets wider (more spread out) at higher temperatures.

$C_v = \frac{d}{dT}\left(\frac{f}{2}RT\right) = \frac{f}{2}R$

Thus, $f  = 3$ for monatomic, $C_v = \frac{3R}{2}$
$f = 5$ for diatomic, $C_v = \frac{5R}{2}$

Chapter 22
---
**Heat Engines and the Second Law of Thermodynamics**

A heat engine is a device that takes in energy by heat $Q_h$ from a hot source, does work $W$, and expels less heat $Q_c$ to a cold sink.

$$W_{eng} = Q_h - Q_c$$

Second Law: No engine operating between two heat reservoirs can be 100% efficient.

$$e = \frac{W}{Q_h} = 1 - \frac{Q_c}{Q_h}$$
$$W = eQ_h$$

**Heat Pumps and Refrigerators**

Coefficient of Performance (COP): 
For refrigerators: $$COP_{ref} = \frac{Q_c}{W}$$
For heat pumps: $$COP_{hp} = \frac{Q_h}{W}$$ 

$Q_c$ and $Q_h$ is the energy that is being moved.
$W$ is the work you do. COP > 1 almost always.

$$W= Q_h - Q_c$$
Structurally same formula with the heat engines, but W is the input you must supply. In heat engines $W_{eng}$ is output, engine does work on something else.

**Reversible and Irreversible Processes**

**Reversible process**: An ideal process that can be reversed by an infinitesimal change, leaving no net change in the universe.
 **Irreversible process**: Real-life processes; always some energy lost to friction, turbulence, etc. Why: Only reversible processes achieve maximum theoretical efficiency (like Carnot).
All real engines are less efficient because of irreversibilities.

**The Carnot Engine**
An idealized heat engine that operates in a reversible cycle between two temperatures $T_h$ and $T_c$.

No engine can be more efficient that Carnot. All reversible engines between two temperatures have the same efficiency (Carnot’s theorem). Carnot cycle sets the theoretical maximum for efficiency.

Carnot Theorem, (or carnot efficiency)
$$\frac{Q_c}{Q_h} = \frac{T_c}{T_h}$$

For real engines, irreversibility and losses mean that $Q_c/Q_h$ is generally greater than $T_c/T_h$, so actual efficiency is always less than Carnot efficiency.

**Isothermal Expansion at $T_h$**
Gas expands slowly, absorbs heat $Q_h$ from hot reservoir. Work is done by the gas.
$T$ does not change.

$$W = nRT \ln\left(\frac{V_\text{final}}{V_\text{initial}}\right)$$

**Adiabatic Expansion**
Gas expands without heat exchange (Q = 0)
Temperature drops from $T_h$ to $T_c$.

**Isothermal Compression at $T_c$**
Gas is compressed at constant cold temperature, releases heat $Q_c$ to cold reservoir.
Work is done ON the gas.

$$W = nRT \ln\left(\frac{V_\text{final}}{V_\text{initial}}\right)$$

**Adiabatic Compression**
Gas is compressed without heat exchange.
Temperatuer rises from $T_c$, back to $T_h$

$$e_{Carnot} = 1 - \frac{T_c}{T_h}$$

$T_h$ Hot reservoir temperature (K) 
$T_c$: Cold reservoir temperature (K)
No real engine can be more efficient than a Carnot engine between the same two temperatures.

Why? Might be an exam question.

Carnot cycle on a PV diagram (isothermal and adiabatic processes). !!!


**Gasoline and Diesel Engines**
Convert chemical energy in fuel into mechanical work via combustion inside the engine.

Four-stroke Otto cycle:
**Intake**
Air-fuel mixture drawn into cylinder, approximated as **isobaric**
**Compression**
Mixture compressed adiabatically. (No heat exchange $\Delta Q$ = 0, rapid compression)
$P$ and $T$ increases.
**Power (Ignition)**
Spark ignites mixture; rapid combustion increases pressure and temperature (ideally at constant volume), pushing piston (does work).
Heat added at constant volume, idealized as isochoric addition. Followed by an adiabatic expansion, gas expands; pushing piston down (doing work), no heat exchanged.
**Exhaust**
Piston moves up again, pushing out exhaust gases. Heat expelled at constant volume (isochoric removal, idelly)
Then isobaric exhaust.

$$e = 1 - \frac{1}{r^{\gamma-1}}$$
$r = \frac{V_{max}}{V_{min}}$: compression ratio
$\gamma = \frac{C_p}{C_v}$: ratio of specific heats

**Diesel Engines**
It is similar to Otto, but only air is compressed (to higher ratio, higher temp).
Injected fuel ignites spontaneously (no spark).
**Diesel engines are more efficient** (higher compression ratio, higher $\gamma$).

**Entropy**

$S$: A measure of the disorder or randomness of a system. Also a measure of energy unfit for work.
 State function: Depends only on the state, not the path.

$\Delta S = \int_{i}^{f} \frac{dQ_{rev}}{T}$

Entropy increases when energy spreads out (more disorder). Adding heat at higher temperature increases entropy less than at low temperature.

**Changes in Entropy for Thermodynamic Systems**

!! important
Reversible path

$$\Delta S = \int_{A}^{B} \frac{dQ_{rev}}{T}$$

For temperature changes (no phase change):
$$\Delta S = nC_m \ln\left(\frac{T_f}{T_i}\right)$$$$\Delta S = mc \ln\left(\frac{T_f}{T_i}\right)$$

For phase changes (melting, boiling):
It is also used where heat Q is transferred at **constant temperature**, only if reversible:
$$\Delta S = \frac{Q}{T}$$

For an Isothermal process (constant temperature):
$$\Delta S = nR \ln\left(\frac{V_f}{V_i}\right)$$


$Q$ heat absorbed or released during phase change (at constant $T$).

For mixing or free expansion of gases:
$$\Delta S = nR \ln\left(\frac{V_f}{V_i}\right)$$

**Irreversible Processes** 
Total entropy (system + surroundings) increases. For calculation, use a hypothetical reversible path between same initial and final states.

Entropy is a state fuction, it only depends on the initial and final states of the system--not the path taken. To calculate entropy, imagine a **reversible** (ideal, slow, no friction) path connecting the same states, even if the real process is messy and irreversible.


**Entropy and the Second Law**

In any real (irreversible) process, the total entropy of the universe increases:
$$\Delta S_{univ} = \Delta S_{sys} + \Delta S_{surr} > 0$$
For a reversible process:
$$\Delta S_{univ} = 0$$

**Spontaneity and Direction Processes** happen spontaneously in the direction of increasing total entropy. 
Example: Heat flows from hot to cold, not the reverse. 
**Heat Death of the Universe** If all processes increase entropy, eventually all energy becomes uniformly spread out (no more work can be done). 
**Microscopic View Entropy** measures the number of microscopic arrangements (microstates) that correspond to a system’s macroscopic state.

For an ideal gas,

$Q = nC_p(T_2 - T_1)$
$\Delta U = nC_v(T_2 - T_1)$

Remember what the laws are!

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0NzE4NTUxMjddfQ==
-->