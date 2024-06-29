# Tectonic Subsidence Calculation Including Sedimentation

## Introduction

This document outlines the calculation of tectonic subsidence considering sedimentation, where a sediment layer of thickness $H_s$ and density $\rho_s$ is present between the crust and the water/air interface.

## Equations

### Initial State (Isostatic Equilibrium)

Initially, the lithospheric column consists of:
- Crust: Thickness $L_c$ and density $\rho_c$.
- Mantle: Thickness $L - L_c$ and density $\rho_m$.

The initial isostatic balance equation is:
$$
\rho_c L_c + \rho_m (L - L_c)
$$

### Final State (After Stretching and Sedimentation)

After stretching the crust by a factor $B$ and adding a sediment layer:
- Stretched Crust: Thickness $L_c / B$.
- Sediment Layer: Thickness $H_s$ and density $\rho_s$.
- Mantle and Asthenosphere: Thickness $L - \frac{L_c}{B} - H_s - s$, where $s$ is the subsidence.

The equation for the final state is:

$$
(\rho_w - \rho_a) s + \rho_c \frac{L_c}{B} + \rho_s H_s + \rho_m \left( L - \frac{L_c}{B} - H_s \right)
$$

### Equating Initial and Final States

Equate the initial and final states to find $s$:

$$
\rho_c L_c + \rho_m (L - L_c) = (\rho_w - \rho_a) s + \rho_c \frac{L_c}{B} + \rho_s H_s + \rho_m \left( L - \frac{L_c}{B} - H_s \right)
$$

### Solve for $s$

Rearrange the equation to solve for $s$:

$$
\rho_c L_c + \rho_m L - \rho_m L_c = (\rho_w - \rho_a) s + \rho_c \frac{L_c}{B} + \rho_s H_s + \rho_m L - \rho_m \frac{L_c}{B} - \rho_m H_s
$$

Combine like terms:

$$
\rho_c L_c - \rho_m L_c = (\rho_w - \rho_a) s + \rho_c \frac{L_c}{B} + \rho_s H_s - \rho_m \frac{L_c}{B} - \rho_m H_s
$$

Factor out $L_c$:

$$
(\rho_c - \rho_m) L_c \left( 1 - \frac{1}{B} \right) = (\rho_w - \rho_a) s + \rho_s H_s - \rho_m H_s
$$

Solve for $s$:

$$
s = \frac{(\rho_c - \rho_m) L_c \left( 1 - \frac{1}{B} \right) + \rho_s H_s - \rho_m H_s}{\rho_w - \rho_a}
$$

Therefore, incorporating sedimentation with a sediment layer of thickness $H_s$ and density $\rho_s$, the equation for the change in tectonic subsidence $s$ due to crustal stretching becomes:

$$
s = \frac{(\rho_c - \rho_m) L_c \left( 1 - \frac{1}{B} \right) + \rho_s H_s - \rho_m H_s}{\rho_w - \rho_a}
$$

This equation accounts for both the stretching of the crust (represented by $L_c / B$) and the additional sediment layer (represented by $H_s$).
