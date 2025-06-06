# Double Pendulum Simulation and Chaos Visualization - DSC 330

This project models the motion of a **double pendulum** using numerical integration techniques in Python. The double pendulum is a canonical example of a deterministic chaotic system, where small changes in initial conditions can lead to dramatically different outcomes. The simulation explores the physics, energy conservation, and chaotic behavior of the system.

---

## Overview

The notebook performs:
- Derivation and implementation of the nonlinear equations of motion
- Numerical integration using `scipy.integrate.odeint`
- Visualization of angular positions, phase space, and total energy
- Demonstration of sensitive dependence on initial conditions (chaos)

---

## Scientific Context

The double pendulum consists of two pendulums attached end-to-end, forming a simple but rich dynamical system governed by nonlinear coupled differential equations. Unlike the simple pendulum, the double pendulum exhibits **chaotic behavior** — it is deterministic, yet extremely sensitive to initial conditions. This system is a foundational model in nonlinear dynamics and chaos theory.

---

## Model Summary

- **Degrees of Freedom**: Two angles (θ₁, θ₂) and their velocities
- **Integration Method**: `scipy.integrate.odeint`
- **Key Outputs**:
  - Angular displacement vs. time
  - Phase space plots (θ vs. ω)
  - Energy conservation validation
- **Libraries Used**:
  - `NumPy`
  - `SciPy`
  - `Matplotlib`
