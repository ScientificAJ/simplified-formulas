# Simplified Physics Formulas – Overview

This document lists common physics formulas that are simplified forms of more general equations. Textbooks across many education boards (CBSE, ICSE, IB, A-Levels, AP, etc.) often present simplified versions first for ease of learning.

These simplified equations are used when certain assumptions hold (ideal systems, aligned vectors, constant parameters). In more advanced physics, vector calculus, tensor formulations, and relativistic corrections replace many of these simplified forms.

## Comprehensive List of Formulas

The following table breaks down the simplified equations commonly taught in foundational physics courses worldwide. It contrasts the high school textbook formulas with their generalized university-level counterparts and explicitly states the mathematical and physical approximations being made.

| # | Simplified Textbook Formula | Full / General Equation | Key Assumptions for Simplification | Physics Topic Category |
|---|---|---|---|---|
| 1 | $P = F/A$ | $\mathbf{T} = -p\mathbf{I} + \boldsymbol{\tau}$ or $P = \frac{dF_\perp}{dA}$ | Assumes perpendicular force, uniform distribution over area. | Mechanics |
| 2 | $W = Fd$ | $W = \int \vec{F} \cdot d\vec{r}$ | Assumes force is perfectly parallel to displacement, constant force. | Mechanics |
| 3 | $\tau = rF$ | $\vec{\tau} = \vec{r} \times \vec{F}$ | Assumes force is applied perfectly perpendicular to the lever arm. | Mechanics |
| 4 | $F = ma$ | $\vec{F} = \frac{d\vec{p}}{dt}$ | Assumes constant mass (no mass ejection/accretion). | Mechanics |
| 5 | $p = mv$ | $\vec{p} = \gamma m_0 \vec{v}$ | Classical speeds (non-relativistic, $v \ll c$). | Mechanics |
| 6 | $KE = \frac{1}{2}mv^2$ | $K = (\gamma - 1)m_0c^2$ | Classical speeds (non-relativistic, $v \ll c$). | Mechanics |
| 7 | $U = mgh$ | $U = -G\frac{Mm}{r}$ | Near Earth's surface, assumes constant $g$ and flat reference frame. | Mechanics |
| 8 | $F_c = \frac{mv^2}{r}$ | $\vec{F} = m\vec{\omega} \times (\vec{\omega} \times \vec{r})$ | Uniform circular motion, perfectly circular path. | Mechanics |
| 9 | $V = IR$ | $\vec{J} = \sigma \vec{E}$ | Ohmic materials, uniform temperature, macroscopic scale. | Electricity & Magnetism |
| 10 | $E = F/q$ | $\vec{E} = \lim_{q \to 0} \frac{\vec{F}}{q}$ | Ideal "test charge" approximation (charge doesn't distort the field). | Electricity & Magnetism |
| 11 | $F = k\frac{q_1 q_2}{r^2}$ | Maxwell's Equations (general electrodynamics) | Perfect point charges, stationary relative to each other, in vacuum. | Electricity & Magnetism |
| 12 | $P = VI$ | $P = \int \vec{J} \cdot \vec{E} dV$ | Steady DC conditions, completely resistive load. | Electricity & Magnetism |
| 13 | $PV = nRT$ | Van der Waals / Virial Expansion | Ideal gas assumption (no intermolecular forces, zero molecular volume). | Thermodynamics |
| 14 | $Q = mc\Delta T$ | $Q = \int m c(T) dT$ | No phase change, specific heat $c$ assumed perfectly constant. | Thermodynamics |
| 15 | $v = f\lambda$ | Wave Equation solutions | Uniform medium, non-dispersive (all frequencies travel at same speed). | Waves & Optics |
| 16 | $n_1 \sin\theta_1 = n_2 \sin\theta_2$ | Fermat's Principle / Maxwell boundary conditions | Isotropic media, geometric ray approximation. | Waves & Optics |
| 17 | $E = hf$ | $E^2 = (pc)^2 + (m_0c^2)^2$ (with $m_0=0$) | Quantum approximation, purely for massless photons. | Modern Physics |
| 18 | $v = u + at$ | $\vec{v}(t) = \vec{v}_0 + \int_0^t \vec{a}(t') dt'$ | 1D motion, constant acceleration, no jerk. | Kinematics |
| 19 | $s = ut + \frac{1}{2}at^2$ | $\vec{r}(t) = \vec{r}_0 + \int_0^t \vec{v}(t') dt'$ | 1D motion, constant acceleration, origin at $s=0$. | Kinematics |
| 20 | $v^2 = u^2 + 2as$ | $\int_{\vec{v}_0}^{\vec{v}} \vec{v} \cdot d\vec{v} = \int_{\vec{r}_0}^{\vec{r}} \vec{a} \cdot d\vec{r}$ | 1D motion, constant acceleration, vector alignment. | Kinematics |
| 21 | $L = I\omega$ | $\vec{L} = \mathbf{I} \vec{\omega}$ or $\vec{L} = \int (\vec{r} \times \vec{v}) dm$ | Rotation about a principal axis of symmetry, rigid body. | Rotational Mechanics |
| 22 | $K_{rot} = \frac{1}{2}I\omega^2$ | $K = \frac{1}{2} \vec{\omega}^T \mathbf{I} \vec{\omega}$ | Fixed axis of rotation, rigid body, scalar inertia. | Rotational Mechanics |
| 23 | $\tau = I\alpha$ | $\vec{\tau} = \frac{d\vec{L}}{dt} = \mathbf{I}\vec{\alpha} + \vec{\omega} \times (\mathbf{I}\vec{\omega})$ | Fixed rotation axis, constant moment of inertia. | Rotational Mechanics |
| 24 | $P = P_0 + \rho gh$ | $\nabla P = \rho \vec{g}$ (Hydrostatic equation) | Incompressible fluid (constant $\rho$), uniform $g$ field. | Fluid Mechanics |
| 25 | $F_B = \rho V g$ | $\vec{F}_B = -\oint_S P d\vec{A}$ | Uniform $g$ field, completely uniform fluid density. | Fluid Mechanics |
| 26 | $A_1 v_1 = A_2 v_2$ | $\frac{\partial \rho}{\partial t} + \nabla \cdot (\rho \vec{v}) = 0$ (Continuity) | Steady flow, incompressible fluid ($\rho = \text{const}$), 1D streamline. | Fluid Mechanics |
| 27 | $P + \frac{1}{2}\rho v^2 + \rho gh = \text{const}$ | Navier-Stokes Equations | Inviscid (no viscosity), incompressible, steady, irrotational flow. | Fluid Mechanics |
| 28 | $F = 6\pi \eta r v$ | General drag from Navier-Stokes | Perfectly spherical object, very low Reynolds number (laminar). | Fluid Mechanics |
| 29 | $F = -kx$ | $\sigma_{ij} = C_{ijkl} \epsilon_{kl}$ (Generalized Hooke's) | 1D deformation, ideal linear elastic material, no hysteresis. | Elasticity |
| 30 | $Y = \frac{F/A}{\Delta L/L_0}$ | Stress-Strain Tensor relationship | Isotropic material, uniform 1D stress, small elastic deformation. | Elasticity |
| 31 | $T = 2\pi\sqrt{\frac{m}{k}}$ | $m\frac{d^2x}{dt^2} + c\frac{dx}{dt} + kx = 0$ | Ideal massless spring, strictly linear restoring force, no damping. | Oscillations & SHM |
| 32 | $T = 2\pi\sqrt{\frac{L}{g}}$ | $\frac{d^2\theta}{dt^2} + \frac{g}{L}\sin\theta = 0$ | Small angle approx ($\sin\theta \approx \theta$), massless string, point mass. | Oscillations & SHM |
| 33 | $F = G\frac{m_1 m_2}{r^2}$ | $G_{\mu\nu} = \frac{8\pi G}{c^4}T_{\mu\nu}$ (Einstein Field Eq.) | Weak gravitational field, non-relativistic speeds, point/spherical masses. | Gravitation |
| 34 | $g = G\frac{M}{r^2}$ | $\nabla \cdot \vec{g} = -4\pi G\rho$ | Perfectly spherical, non-rotating mass distribution. | Gravitation |
| 35 | $U = -G\frac{m_1 m_2}{r}$ | $U = -\int_{\infty}^r \vec{F}_g \cdot d\vec{r}$ | Point masses, $U=0$ exactly at infinite distance. | Gravitation |
| 36 | $v_{rms} = \sqrt{\frac{3RT}{M}}$ | Maxwell-Boltzmann Distribution | Ideal gas model, non-relativistic speeds, point particles. | Kinetic Theory |
| 37 | $\Delta U = Q - W$ | $dE = \delta Q - \delta W + \sum \mu_i dN_i$ | Closed system (no mass transfer), quasi-static process. | Thermodynamics |
| 38 | $W = P\Delta V$ | $W = \int_{V_1}^{V_2} P(V) dV$ | Isobaric (constant pressure) or quasi-static volume change. | Thermodynamics |
| 39 | $\Delta L = \alpha L_0 \Delta T$ | $L(T) = L_0 \exp\left(\int \alpha(T) dT\right)$ | Small temperature range, $\alpha$ assumed constant, linear expansion. | Thermodynamics |
| 40 | $C = \frac{\epsilon_0 A}{d}$ | $C = \frac{\oint \vec{D} \cdot d\vec{A}}{\int \vec{E} \cdot d\vec{l}}$ | Infinite parallel plates (ignoring edge/fringing effects), uniform vacuum/dielectric. | Electrostatics |
| 41 | $V = k\frac{q}{r}$ | $V(\vec{r}) = \frac{1}{4\pi\epsilon_0} \int \frac{\rho(\vec{r'})}{\|\vec{r} - \vec{r'}\|} d^3r'$ | Continuous charge distribution integral form of potential. | Electrostatics |
| 42 | $EA = \frac{q_{enc}}{\epsilon_0}$ | $\oint \vec{E} \cdot d\vec{A} = \frac{Q_{enc}}{\epsilon_0}$ | Highly symmetric charge distribution, $\vec{E}$ perfectly parallel to $d\vec{A}$. | Electrostatics |
| 43 | $U = \frac{1}{2}CV^2$ | $U = \frac{1}{2} \int \rho V d^3r = \frac{\epsilon_0}{2} \int E^2 d^3r$ | Linear dielectric, no charge leakage, ideal capacitor. | Electrostatics |
| 44 | $R = \rho\frac{L}{A}$ | $R = \int_0^L \frac{\rho(x)}{A(x)} dx$ | Uniform cross-sectional area, homogeneous material (constant $\rho$). | Current Electricity |
| 45 | $I = nAev_d$ | $\vec{J} = \sum_i n_i q_i \vec{v}_i$ | Steady state, uniform current density, single type of charge carrier. | Current Electricity |
| 46 | $V_T = \mathcal{E} - Ir$ | Kirchhoff's Voltage Law | Constant internal resistance, non-ideal DC battery model. | Current Electricity |
| 47 | $F = BIL$ | $\vec{F} = \int I (d\vec{l} \times \vec{B})$ | Perfectly straight wire, uniform B-field, wire perpendicular to field. | Magnetism |
| 48 | $F = qvB$ | $\vec{F} = q(\vec{v} \times \vec{B})$ (Lorentz Force) | Velocity vector completely perpendicular to magnetic field vector. | Magnetism |
| 49 | $B = \frac{\mu_0 I}{2\pi r}$ | $\vec{B}(\vec{r}) = \frac{\mu_0 I}{4\pi} \int \frac{d\vec{l} \times \hat{r}'}{r'^2}$ | Infinitely long, infinitely thin straight wire. | Magnetism |
| 50 | $B = \mu_0 n I$ | $\oint \vec{B} \cdot d\vec{l} = \mu_0 I_{enc}$ | Infinitely long solenoid, empty core, uniform tightly packed windings. | Magnetism |
| 51 | $\mathcal{E} = N\frac{\Delta \Phi}{\Delta t}$ | $\nabla \times \vec{E} = -\frac{\partial \vec{B}}{\partial t}$ | Uniform spatially constant flux over coil area, average EMF over time. | EM Induction |
| 52 | $\mathcal{E} = Blv$ | $\mathcal{E} = \oint (\vec{v} \times \vec{B}) \cdot d\vec{l}$ | Straight conductor moving perfectly perpendicular to uniform B-field. | EM Induction |
| 53 | $V_{rms} = \frac{V_0}{\sqrt{2}}$ | $V_{rms} = \sqrt{\frac{1}{T} \int_0^T V(t)^2 dt}$ | Pure sinusoidal waveform, no harmonic distortion. | Alternating Current |
| 54 | $\frac{V_s}{V_p} = \frac{N_s}{N_p}$ | Derived via coupled Faraday's Law | Ideal transformer: 100% flux linkage, zero resistance/eddy currents. | Alternating Current |
| 55 | $\frac{1}{f} = \frac{1}{v} + \frac{1}{u}$ | Exact geometric ray tracing via Snell's Law | Paraxial approximation (small angles), perfectly thin lens/mirror. | Ray Optics |
| 56 | $m = -\frac{v}{u}$ | General magnification geometry | Paraxial rays, flat object perpendicular to optical axis. | Ray Optics |
| 57 | $\frac{1}{f} = (n-1)\left(\frac{1}{R_1} - \frac{1}{R_2}\right)$ | Thick lens equation (Gullstrand's equation) | Thin lens approximation, lens immersed in air ($n_{out} \approx 1$). | Ray Optics |
| 58 | $n = \frac{\text{real depth}}{\text{apparent depth}}$ | $d' = d \left(\frac{n_2}{n_1}\right) \frac{\cos\theta_2}{\cos\theta_1}$ | Viewing from exactly normal incidence (directly above), paraxial rays. | Ray Optics |
| 59 | $y = \frac{\lambda L}{d}$ | $\Delta x = \sqrt{L^2 + (y+d/2)^2} - \sqrt{L^2 + (y-d/2)^2}$ | Screen distance $L \gg d$, small angle approx ($y \ll L$). | Wave Optics |
| 60 | $a \sin\theta = n\lambda$ | Fresnel-Kirchhoff diffraction integral | Fraunhofer diffraction (parallel rays, screen at infinity or focused). | Wave Optics |
| 61 | $I = I_0 \cos^2\theta$ | Maxwell's equations boundary limits | Ideal linear polarizer, perfectly unpolarized initial light. | Wave Optics |
| 62 | $\lambda = \frac{h}{p}$ | Relativistic Quantum Field Theory | Free particle, valid for non-relativistic and relativistic momentum. | Quantum Physics |
| 63 | $K_{max} = hf - \Phi$ | Quantum Electrodynamics (QED) | Single photon absorption, instantaneous emission, work function constant. | Quantum Physics |
| 64 | $E_n = -\frac{13.6 \text{ eV}}{n^2}$ | Dirac/Schrodinger Equation for central potential | Infinite nuclear mass, non-relativistic electron, no fine/hyperfine structure. | Atomic Physics |
| 65 | $mvr = \frac{nh}{2\pi}$ | Spherical harmonics in quantum mechanics | Semiclassical Bohr model (circular orbits), assumes quantized angular momentum. | Atomic Physics |
| 66 | $E = \Delta mc^2$ | $E^2 = (pc)^2 + (m_0c^2)^2$ | Particle/system strictly at rest ($p=0$), total mass-energy equivalence. | Nuclear Physics |
| 67 | $N = N_0 e^{-\lambda t}$ | Stochastic quantum decay master equations | Statistically large number of nuclei, constant decay probability over time. | Nuclear Physics |
| 68 | $T_{1/2} = \frac{\ln 2}{\lambda}$ | Derived from $e^{-\lambda t} = 1/2$ | Direct consequence of the exponential decay approximation. | Nuclear Physics |
| 69 | $v = H_0 d$ | FLRW Metric in General Relativity | Low redshift ($z \ll 1$), perfectly isotropic and homogeneous universe. | Astrophysics |
| 70 | $v_{esc} = \sqrt{\frac{2GM}{R}}$ | Exact GR Schwarzschild Metric (geodesics) | Newtonian kinetic/potential approx, non-rotating spherical body, no drag. | Astrophysics |
| 71 | $T^2 = \frac{4\pi^2}{GM}r^3$ | General two-body problem (barycenter focus) | Orbiting mass is negligible ($m \ll M$), perfectly circular orbit assumption. | Astrophysics |
| 72 | $L = 4\pi R^2 \sigma T^4$ | Integral of Planck's Law over all frequencies | Star is modeled as a perfect blackbody sphere of uniform temperature. | Astrophysics |


Feel free to add stuff.
