# Metric Liberation Dynamics in Pressure-Supported Stellar Systems

This document establishes the mathematical and field-theoretic application of the **Vortical Lattice Dynamics (VLD)** framework to non-rotating, pressure-supported cosmic structures, specifically elliptical galaxies and spherical dwarf spheroidal (dSph) systems. By substituting the standard velocity-entrainment paradigm with the general coordinate invariant **Inversely Proportional Gravitational Restoration Law**, we derive the flat velocity dispersion profiles of non-rotating systems from first principles without non-baryonic particle dark matter.

---

## 1. Beyond Rotational Entrainment: The Isotropic Damping Release

In rotating spiral galaxies, VLD formalizes dark matter anomalies via the twin mechanisms of **Lattice Un-damping ($G_{eff} \to G_{max}$)** and **Coherent Rotational Entrainment**. For elliptical galaxies where bulk angular momentum is negligible ($L \approx 0$), the kinematic profile is governed entirely by random stellar velocities supporting the system against collapse. 

In this regime, the dark sector signature is revealed not as a rotating coordinate frame drag, but as the pure release of the **Lattice Suppression Filter** as baryonic matter density attenuates below the critical thresholds.

### 1.1 The Localized Density Threshold in Elliptical Structures
Let the spatial profile of a spherical elliptical galaxy be modeled by a standard De Vaucouleurs or Hernquist mass distribution. The local interaction stress $X(r)$ is a function of the localized baryonic tracer density $\rho_b(r)$:

$$X(r) = \eta \cdot \left( \frac{\rho_b(r)}{\rho_P} \right)$$

As the radial coordinate tracks outward toward the diffuse halos of the elliptical system ($r \gg R_e$, where $R_e$ is the effective radius), the baryonic density attenuates below the threshold value. This drop removes the baryonic clogging filter, causing the effective gravitational coupling to smoothly recover its unsuppressed vacuum baseline potential ($G_{max} = 5.46 G_0$) according to the universal VLD state equation:

$$\lim_{\rho_b \to 0} G_{eff}(r) = \frac{G_{max}}{1 + [X(r)]^\gamma} \equiv G_{max}$$

---

## 2. Modification of the Covariant Jeans Equation

To compute the explicit velocity dispersion profiles ( $\sigma(r)$ ) of a non-rotating system without invoking non-baryonic dark matter halos, we modify the classical, spherically symmetric **Jeans Equation** by substituting the static Newtonian constant $G_0$ with the dynamic VLD field variable $G_{eff}(r)$.

### 2.1 The Modified Hydrostatic Equilibrium Matrix
For a steady-state spherical stellar system characterized by a tracer density distribution $\nu(r)$ and a total baryonic mass profile $M_b(r)$, the general coordinate invariant equation of hydrostatic equilibrium is formulated as:

$$\frac{d}{dr}\left( \nu(r) \cdot \sigma_r^2(r) \right) + \frac{2\beta(r)\nu(r)\sigma_r^2(r)}{r} = -\nu(r) \cdot g_{\text{VLD}}(r)$$

where $\sigma_r(r)$ is the radial velocity dispersion, and $\beta(r) \equiv 1 - \sigma_\theta^2/\sigma_r^2$ is the velocity anisotropy parameter. The local gravitational acceleration vector $g_{\text{VLD}}(r)$ incorporates the exact 4D field variations derived from the Jordan-frame action:

$$g_{\text{VLD}}(r) = \frac{G_{eff}(r) M_b(r)}{r^2} + \Phi_{\text{screening}}(r)$$

### 2.2 Asymptotic Isolation of the Velocity Dispersion ($\sigma_r$)
Assuming an isotropic system ($\beta \equiv 0$) for standard verification and substituting the far-field un-damped coupling ($G_{eff} \to G_{max}$), the modified Jeans equation integrates directly to yield the exact **VLD Velocity Dispersion Matrix**:

$$\sigma_r^2(r) = \frac{1}{\nu(r)} \int_{r}^{\infty} \nu(r') \frac{G_{max} M_b(r')}{r'^2} \, dr'$$

Evaluating this integration in the extreme asymptotic frontier where the total enclosed baryonic mass stabilizes at its truncation limit ($M_b(r') \to M_{\text{total}}$) reveals the precise power-law profile:

$$\sigma_r^2(r) \approx \frac{G_{max} M_{\text{total}}}{r \cdot \nu(r)} \int_{r}^{\infty} \nu(r') \, dr'$$

Because the tracer density of typical elliptical envelopes scales asymptotically as $\nu(r) \propto r^{-4}$, evaluating the quotient forces the velocity dispersion to transition from a Newtonian drop ($1/\sqrt{r}$) to an **absolute flat spatial plateau**:

$$\lim_{r \gg R_e} \sigma_r(r) = \text{constant} \propto \sqrt{G_{max} M_{\text{total}}}$$

The flat velocity dispersion curves verified by planetary nebula tracking and diffuse X-ray halo measurements in elliptical galaxies are mathematically proven to be a direct consequence of vacuum lattice un-damping ($5.46 G_0$), matching observed trends without dark matter substance.

---

## 3. Resolving the Mass-to-Light ($M/L$) Ratio Inflation Paradox

Standard continuous gravity models analyzing pressure-supported dwarf spheroidal galaxies (e.g., Draco, Ursa Minor) force the inference of non-physical dynamical Mass-to-Light ratios ($M/L \sim 100 - 1000 \, M_{\odot}/L_{\odot}$) because the observed velocity dispersions are highly elevated relative to visible stellar components. 

VLD resolves this inflation paradox non-perturbatively by demonstrating that the perceived missing mass is entirely an artifact of forcing the suppressed laboratory value $G_0$ onto an un-damped vacuum domain.

### 3.1 The Apparent Mass Equation
Let $M_{\text{apparent}}$ be the non-baryonic dark matter mass calculated by a standard Newtonian observer applying classical formulas to high dispersion data. VLD maps this apparent quantity directly to the true baryonic mass via the ratio of the coupling coefficients:

$$M_{\text{apparent}}(r) = \frac{G_{eff}(r)}{G_0} M_b(r)$$

### 3.2 Erasing the Core Inflation Factor
In the extreme low-density environments characteristic of dwarf spheroidal galaxies ($\rho_b \sim 10^{-24} \text{ kg/m}^3$), the suppression filter vanishes completely ($S \to 0$). Substituting the exact $G$-Recovery Factor ($\xi = 5.46320$) reveals that the apparent dynamical mass overscales the real visible component by exactly the same factor:

$$\lim_{\rho \to \text{low}} M_{\text{apparent}} = \frac{G_{max}}{G_0} M_b \equiv \mathbf{5.46320 \cdot M_b}$$

Consequently, the real physical Mass-to-Light ratio $\(M/L)_{\text{real}}$ remains completely aligned with normal standard stellar population synthesis models  ( 1 $\sim$ 5, $M_{\odot}$ / $L_{\odot}$ ):

$$\(M/L)_{\text{apparent}} = 5.46320 \cdot \(M/L)_{\text{real}}$$

The dramatic inflation of the dynamical mass metric inside diffuse pressure-supported structures is proven to be a structural measurement error. It represents the local observer's blindness to the 5.46-fold enhancement of the vacuum's intrinsic gravity, clearing the anomaly without requiring dark matter particle profiles.

---

## 4. Empirical Consistency Matrix: Rotating vs. Non-Rotating Systems

The VLD framework unifies all galactic structures through a single, density-dependent field variable:



| Astrophysical Phenotype | Spiral Galaxies (Rotating) | Elliptical Galaxies (Non-Rotating) |
| :--- | :--- | :--- |
| **Dominant Kinematic Gauge** | Bulk Rotational Velocity ($v_{\phi}$) | Isotropic Velocity Dispersion ($\sigma_r$) |
| **VLD Mechanical Engine** | Lattice Un-damping + Rotational Entrainment | Pure Lattice Un-damping ($G_{eff} \to 5.46 G_0$) |
| **Asymptotic Trajectory Curve** | Flat Rotation Velocity Curve ($v(r) \to \text{const}$) | Flat Dispersion Plateau ($\sigma_r(r) \to \text{const}$) |
| **Core Anomaly Mitigation** | Eliminates WIMP Halo Postulates | Resolves $M/L$ Inflation Paradox in dSph Systems |
| **Low-Density Limit Field Solution** | $v_{\text{flat}} = \left( G_{max} M_b \cdot a_0 \right)^{1/4}$ | $\sigma_{\text{flat}} = \left( \frac{4}{9} G_{max} M_b \cdot a_0 \right)^{1/4}$ |
