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

## Learning Layer Added for Every Formula

This section adds four teaching aids for each numbered formula in the main table:

- `Derivation Link`: a compact path from the general law to the simplified school formula.
- `Approximation / Error Range`: when the simplification is valid and how large the approximation error can be.
- `Visual Hierarchy`: conceptual dependency chain.
- `School Example`: typical classroom, lab, or board-exam style usage.

| # | Derivation Link | Approximation / Error Range | Visual Hierarchy | School Example |
|---|---|---|---|---|
| 1 | Cauchy stress tensor -> normal component -> uniform normal load gives P = F/A | Exact when force is perpendicular and uniform on area; otherwise use differential form | Continuum stress -> pressure -> force on surface | Nail vs broad pin pressure comparison |
| 2 | Work definition as line integral -> constant force parallel to motion gives W = Fd | If angle ignored, relative error is 1 - cos(theta); less than 1.5 percent for theta less than 10 degrees | Energy transfer -> work integral -> constant-force case | Pulling a block on a smooth floor |
| 3 | Torque from cross product r x F -> perpendicular case gives tau = rF | If sin(theta) approximated as 1, error is 1 - sin(theta); about 1.5 percent at 80 degrees | Rotational effect -> moment arm -> torque magnitude | Spanner turning a nut |
| 4 | Newton second law in momentum form F = dp/dt -> constant mass gives F = ma | Exact for constant mass systems; rockets need dp/dt full form | Momentum law -> constant-mass dynamics | Trolley acceleration in school lab |
| 5 | Relativistic momentum p = gamma m0 v -> low-speed limit gamma about 1 gives p = mv | Error about 0.5 percent at 0.1c and about 5 percent at 0.3c | Relativity -> momentum -> classical limit | Cricket ball momentum comparison |
| 6 | Relativistic kinetic energy K = (gamma - 1)m0c^2 -> low-speed expansion gives 1/2 mv^2 | Error about 0.8 percent at 0.1c and about 7 percent at 0.3c | Relativity -> energy -> classical KE | Braking distance and kinetic energy problems |
| 7 | Gravitational potential U = -GMm/r -> near Earth surface expansion gives U about mgh | Relative error about h/Rearth; about 0.016 percent at h = 1 km | Universal gravity -> potential -> near-surface model | Lifting a schoolbag to a desk |
| 8 | Radial acceleration in circular motion -> Fc = mv^2/r for uniform circular motion | Valid for constant speed and circular path; non-uniform motion needs tangential term too | Curvilinear motion -> centripetal acceleration -> force | Stone tied to string in circle |
| 9 | Microscopic Ohm law J = sigma E -> uniform wire gives V = IR | Valid for ohmic materials and stable temperature; fails for diode and filament extremes | Charge transport -> conductivity -> circuit law | Resistor network current-voltage graph |
| 10 | Electric field defined by test-charge limit E = lim(F/q) | Exact in test-charge limit; finite test charge perturbs field | Field concept -> test charge -> measurable force | Force on tiny charge near charged sphere |
| 11 | Electrostatics from Maxwell equations -> inverse-square force for static point charges | Valid for point charges at rest in vacuum; moving charges require magnetic terms | Maxwell theory -> electrostatics -> Coulomb force | Two charged pith balls experiment |
| 12 | Electromagnetic power density J dot E integrated over volume -> lumped circuit gives P = VI | Exact for steady resistive DC element; reactive AC needs phase treatment | EM energy flow -> device power -> circuit formula | Power rating of bulb and heater |
| 13 | Real gas equation reduces to ideal gas when interactions and molecular volume are negligible | Use compressibility factor Z near 1; often within a few percent near room conditions at low pressure | Equation of state -> idealization -> PV = nRT | Gas syringe temperature-pressure exercise |
| 14 | Heat transfer dQ = mc(T)dT -> constant c over interval gives Q = mc delta T | Good over small temperature ranges away from phase change | Thermal energy -> specific heat model -> linear form | Mixing hot and cold water calorimetry |
| 15 | Wave phase relation gives speed = frequency times wavelength | Exact in non-dispersive medium; in dispersive media v depends on frequency | Wave solution -> phase speed -> v = f lambda | Measuring wave speed on stretched string |
| 16 | Fermat minimum-time path or boundary conditions -> Snell law | Valid for isotropic media and ray optics scale | Variational optics -> refraction law -> ray tracing | Refraction through glass slab |
| 17 | Photon quantum postulate E = hf and massless relation E = pc | Exact for free photons; material medium introduces effective models | Quantum light -> photon energy -> spectroscopy | LED color and photon energy estimate |
| 18 | Integrate constant acceleration over time to get v = u + at | Exact only for constant acceleration; with jerk j error in v is about 0.5 j t^2 | Kinematics integral -> constant-a velocity equation | Car speeding up uniformly problem |
| 19 | Integrate v(t) with constant acceleration to get s = ut + 1/2 at^2 | Exact for constant acceleration and chosen origin | Kinematics integration -> displacement equation | Free-fall distance after t seconds |
| 20 | Dot-product integral of acceleration with displacement gives v^2 relation for constant aligned acceleration | Requires 1D alignment and constant a | Work-kinematics link -> constant-a identity | Braking and stopping distance calculation |
| 21 | Angular momentum integral over mass distribution -> principal-axis rigid body gives L = I omega | Exact for rigid body about principal axis; otherwise tensor form needed | Rotational dynamics -> inertia tensor -> scalar shortcut | Flywheel angular momentum question |
| 22 | Rotational kinetic energy quadratic form with inertia tensor -> fixed-axis scalar form | Exact for fixed axis with scalar I | Rotational energy -> tensor form -> scalar form | Rotating disc energy in lab |
| 23 | Torque equals dL/dt -> fixed-axis rigid body with constant I gives tau = I alpha | Omits gyroscopic coupling term omega x (I omega) | Angular momentum rate -> torque law -> fixed-axis rule | Motor torque needed for wheel acceleration |
| 24 | Hydrostatic equilibrium gradient equation integrated in constant density fluid gives P = P0 + rho g h | Accurate for incompressible liquids and near-uniform g | Fluid statics -> pressure gradient -> depth formula | Pressure at bottom of water tank |
| 25 | Integrate pressure over immersed surface to obtain net buoyant force; uniform fluid gives rho V g | Valid in nearly uniform density and g field | Pressure distribution -> net upthrust -> Archimedes form | Floating wood block in beaker |
| 26 | Mass conservation continuity equation -> steady incompressible 1D stream gives A1v1 = A2v2 | Valid when density constant and flow approximately 1D | Conservation of mass -> continuity -> pipe flow relation | Narrow nozzle water speed increase |
| 27 | Bernoulli from simplified Navier-Stokes along streamline with no viscous losses | Breaks with strong viscosity, turbulence, pumps, or shocks | Fluid dynamics -> Bernoulli energy balance | Venturi meter school demonstration |
| 28 | Creeping-flow Navier-Stokes solution around sphere gives Stokes drag 6pi eta r v | Valid for Reynolds number much less than 1 | Viscous flow -> drag law -> linear velocity drag | Oil drop slow-fall estimate |
| 29 | Linear elasticity stress proportional strain -> 1D spring model gives F = -kx | Valid in elastic limit, typically small strain about less than 1 percent for many solids | Material response -> linear model -> spring force | Spring extension in Hooke law lab |
| 30 | Young modulus from stress over strain in linear elastic regime | Valid for isotropic material and small deformation | Elasticity tensor -> uniaxial stress-strain -> Young modulus | Wire stretching with hanging masses |
| 31 | Solve undamped mass-spring ODE to get period 2pi sqrt(m/k) | If spring mass ms not negligible, use effective mass m + ms/3; damping increases period slightly | SHM equation -> natural frequency -> period | Time-period measurement with spring mass |
| 32 | Pendulum nonlinear equation -> small-angle sin(theta) about theta gives SHM period | Fractional error about theta0^2/16; about 0.2 percent at 10 degrees and 0.8 percent at 20 degrees | Pendulum dynamics -> small-angle SHM -> period formula | School pendulum g experiment |
| 33 | Einstein gravity reduces to Newton inverse-square law in weak-field low-speed limit | Good when gravitational potential magnitude is much less than c^2 and speeds much less than c | GR field equations -> Newtonian limit -> force law | Planet-satellite force problems |
| 34 | Gauss law for gravity with spherical symmetry gives g = GM/r^2 outside sphere | Requires spherical mass symmetry | Gravitational field equations -> symmetry -> inverse-square g | Finding g at planet surface |
| 35 | Potential energy from path integral of conservative gravitational force gives U = -GMm/r | Reference chosen at infinity; valid for point or spherical masses | Conservative force -> potential definition -> gravity potential | Satellite energy at orbital radius |
| 36 | Maxwell-Boltzmann speed distribution moments give vrms expression | Exact for ideal monatomic gas in classical regime | Statistical mechanics -> distribution -> rms speed | Gas molecule speed at room temperature |
| 37 | First law with composition terms reduces to delta U = Q - W for closed system | Closed system with no mass transfer; sign convention must be consistent | Energy conservation -> thermodynamics first law -> closed-system form | Gas in piston heat-work accounting |
| 38 | Boundary work integral over pressure-volume path -> constant-pressure gives W = P delta V | Exact for isobaric path; otherwise integrate actual P(V) curve | Thermodynamic process -> PV work -> isobaric shortcut | Expansion of gas against constant load |
| 39 | Integrate thermal expansion coefficient over temperature; constant alpha gives linear relation | Good for modest delta T where alpha nearly constant | Material thermal response -> integral law -> linear expansion | Expansion of metal rod on heating |
| 40 | Capacitance definition Q/V with uniform field between large plates gives epsilon A/d | Fringing negligible when plate size is much larger than separation | Electrostatics -> field and potential -> parallel-plate capacitance | Capacitor design worksheet |
| 41 | Potential from continuous charge integral; point charge density gives kq/r | Exact for point charge or spherical symmetric outside region | Charge distribution -> potential integral -> point-charge potential | Potential near charged conducting sphere |
| 42 | Full Gauss law surface integral -> high-symmetry surfaces give E constant and parallel to dA | Symmetry requirement is strict; otherwise full integral needed | Maxwell equation -> Gaussian surface method -> simplified E expression | Infinite sheet and long wire field questions |
| 43 | Field energy density integrated in space or capacitor work integral gives U = 1/2 CV^2 | Valid for linear dielectric and negligible leakage | Electrostatic energy -> capacitor model -> energy formula | Energy stored in camera flash capacitor |
| 44 | Differential resistance with varying geometry integrated over length; uniform case gives rho L/A | Exact for homogeneous uniform conductor | Microscopic transport -> resistance integral -> uniform-wire formula | Choosing wire gauge in circuits |
| 45 | Current equals charge carrier density times charge times drift speed times area from J = nqvd | Assumes single dominant carrier and uniform drift | Carrier motion -> current density -> conductor current | Drift speed in copper wire problem |
| 46 | Loop rule with source emf and internal drop gives terminal voltage relation | Internal resistance model assumed constant with current and temperature | Circuit loop law -> source model -> terminal voltage | Battery under load voltage drop |
| 47 | Magnetic force on wire from differential element Idl x B integrated; straight perpendicular case gives BIL | Error if field non-uniform or wire angled; use sin(theta) and integration | Lorentz force on current -> wire force -> lab formula | Force on wire between magnet poles |
| 48 | Lorentz magnetic term magnitude qvB sin(theta) -> perpendicular gives qvB | Ignoring angle gives error 1 - sin(theta) | Charged-particle dynamics -> magnetic force magnitude | Radius of electron path in magnetic field |
| 49 | Biot-Savart law integrated for infinite straight wire gives mu0 I over 2pi r | Finite wire correction important when r not much smaller than wire length | Current element field -> Biot-Savart -> long-wire result | Compass deflection near long conductor |
| 50 | Ampere circuital law with long uniform solenoid symmetry gives B = mu0 n I | Good near center when solenoid length is much greater than radius | Maxwell-Ampere law -> symmetric loop -> solenoid field | Field in solenoid practical file |
| 51 | Faraday induction law flux rate form; average over finite interval gives N deltaPhi over delta t | Instantaneous emf is N dPhi/dt; average form used in school numericals | Maxwell-Faraday curl equation -> flux law -> coil emf | Rotating coil generator question |
| 52 | Motional emf from line integral of v x B along moving conductor; straight perpendicular rod gives Blv | Requires rigid rod length l moving perpendicular to uniform B | Induction by motion -> motional emf integral -> Blv | Sliding rod on rails problem |
| 53 | RMS definition of periodic signal; sine-wave integral gives V0/sqrt(2) | Exact only for pure sinusoid | AC waveform -> RMS definition -> sinusoidal value | AC mains peak to RMS conversion |
| 54 | Coupled Faraday laws in ideal transformer give turns ratio equals voltage ratio | Real transformers have copper, hysteresis, and leakage losses | Electromagnetic induction -> transformer equations -> ideal ratio | Step-down transformer turns calculation |
| 55 | Paraxial ray tracing for thin lens or mirror gives 1/f = 1/v + 1/u | Valid for small-angle paraxial rays and thin element | Geometrical optics -> paraxial imaging -> lens equation | Image distance from convex lens |
| 56 | Similar triangles in paraxial optics yield magnification m = -v/u | Sign convention sensitive; holds in paraxial regime | Image geometry -> magnification relation | Object-image height ratio numericals |
| 57 | Refracting spherical surfaces combined in thin limit gives lens-maker equation | Valid for thin lens in air with small thickness relative to radii | Refraction at surfaces -> equivalent power -> lens-maker form | Focal length from lens curvatures |
| 58 | Snell law at plane interface and paraxial normal viewing gives apparent depth rule | Accurate near normal incidence; oblique viewing needs cosine correction | Refraction geometry -> apparent position -> depth formula | Coin in beaker appears raised |
| 59 | Path difference exact expression in double slit; small-angle far-screen limit gives fringe spacing y = lambda L/d | Valid when L much greater than d and y much less than L | Interference path difference -> maxima condition -> fringe width | Young double-slit fringe calculation |
| 60 | Diffraction integral in Fraunhofer limit gives principal maxima condition a sin(theta) = n lambda | Far-field condition roughly L much greater than a^2/lambda | Wave optics integral -> far-field diffraction -> maxima rule | Diffraction grating spectrum problem |
| 61 | Polarization projection from EM wave amplitudes gives Malus law I = I0 cos^2(theta) | Ideal polarizers assumed; real sheets have finite extinction ratio | Polarization physics -> analyzer projection -> intensity law | Rotate analyzer and record intensity |
| 62 | Matter-wave postulate gives de Broglie wavelength lambda = h/p | Exact as definition with relativistic momentum p | Quantum duality -> momentum relation -> wavelength | Electron diffraction wavelength estimate |
| 63 | Energy conservation in photoelectric effect gives Kmax = hf - work function | Threshold frequency required; multielectron effects neglected in simple model | Photon absorption -> energy balance -> stopping potential | Stopping voltage vs frequency graph |
| 64 | Solve hydrogen atom in Coulomb potential and simplify to Bohr-like energies for non-relativistic case | Corrections from reduced mass and fine structure are small but measurable | Quantum atom model -> hydrogen spectrum -> En formula | Balmer series wavelength problems |
| 65 | Bohr quantization postulate mvr = nh/2pi as semiclassical orbital model | Conceptual model, not exact modern QM orbitals | Early quantum model -> quantized angular momentum -> orbital radius | Historical derivation in school modern physics chapter |
| 66 | Relativistic energy-momentum relation at zero momentum gives rest-energy equivalence | Exact at rest; for moving systems use full E^2 relation | Relativity -> mass-energy equivalence -> nuclear energy | Mass defect to binding energy conversion |
| 67 | Constant decay probability leads to exponential decay law N = N0 exp(-lambda t) | Works for large ensembles; individual nuclei decay stochastically | Nuclear statistics -> decay constant -> activity law | Carbon dating style question |
| 68 | Set N/N0 = 1/2 in decay law to derive T1/2 = ln2/lambda | Exact consequence of exponential model | Decay law -> half-life definition -> formula | Remaining fraction after several half-lives |
| 69 | FLRW cosmology Taylor expansion at low redshift gives linear Hubble law v = H0 d | Valid for z much less than 1; higher z needs full cosmology | Cosmology metric -> recession relation -> linear law | Galaxy recession speed estimate |
| 70 | Escape speed from total energy equals zero in Newtonian potential | GR corrections needed near compact massive bodies | Gravitation energy -> escape condition -> speed formula | Earth and Moon escape velocity numericals |
| 71 | Two-body Newtonian gravitation and circular orbit balance give T^2 proportional r^3 | Exact for point masses circular orbit; elliptical uses semi-major axis | Orbital dynamics -> Kepler law -> period-radius relation | Satellite orbital period around Earth |
| 72 | Integrate blackbody spectral radiance over all frequencies and area to get L = 4pi R^2 sigma T^4 | Valid when object approximates blackbody with near-uniform surface temperature | Thermal radiation -> Stefan-Boltzmann law -> stellar luminosity | Estimating star luminosity from radius and temperature |

## Extra School-Style Examples (Across Boards)

These are additional common patterns seen in CBSE, ICSE, IB, A-Level, and AP style assignments and exams.

1. `Work-Energy`: A crate is pulled by force at 30 degrees; compare `W = Fd` versus `W = Fd cos(theta)` and compute percentage error.
2. `SHM`: Measure time for 20 oscillations of a spring and estimate `k` using `T = 2pi sqrt(m/k)`.
3. `Pendulum`: Measure `g` using different amplitudes (5 degrees, 10 degrees, 20 degrees) and discuss small-angle error.
4. `Refraction`: Verify Snell law for glass block and estimate refractive index from slope of `sin i` versus `sin r`.
5. `Lens`: Find focal length by plotting `1/v` versus `1/u` and compare with lens-maker estimate.
6. `Electric Circuits`: Plot `V-I` graph for resistor, bulb, and diode to identify ohmic versus non-ohmic behavior.
7. `Capacitors`: Compute stored energy two ways: `1/2 CV^2` and area under `Q-V` graph.
8. `Magnetic Force`: Predict force change when wire angle to magnetic field changes from 90 degrees to 60 degrees.
9. `Induction`: Sliding rod setup to verify proportionality of induced emf with `B`, `l`, and `v`.
10. `Gas Laws`: Test ideal-gas assumption limits by discussing deviations at high pressure.
11. `Thermal Expansion`: Determine expansion coefficient of metal wire and comment on linearity range.
12. `Buoyancy`: Compare apparent weight in air and water to estimate density of unknown solid.
13. `Bernoulli`: Explain why fluid speed increases in narrow tube and connect with pressure drop.
14. `Atomic Physics`: Use hydrogen line wavelengths to back-calculate energy level transitions.
15. `Photoelectric Effect`: Use stopping-potential graph to estimate Planck constant and work function.
16. `Nuclear Decay`: Solve multi-step half-life problems with both fraction and activity forms.
17. `Astronomy`: Use Kepler third law to compare orbital periods of two satellites at different radii.
18. `Stellar Physics`: Estimate star luminosity ratio from given `R` and `T` relative to the Sun.

## Visual Master Hierarchies (Big Picture)

1. `Mechanics`: Newton laws -> momentum/work-energy -> kinematics/rotation formulas.
2. `E&M`: Maxwell equations -> electrostatics/current laws -> circuit and magnetism formulas.
3. `Thermal/Fluids`: Conservation laws + equation of state -> hydrostatics/flow/heat formulas.
4. `Waves/Optics`: Wave equation + boundary conditions -> interference/diffraction/refraction shortcuts.
5. `Modern Physics`: Quantum postulates + relativity -> atomic, nuclear, and astrophysical school formulas.
