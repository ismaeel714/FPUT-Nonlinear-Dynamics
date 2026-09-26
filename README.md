# FPUT Nonlinear Dynamics

A numerical investigation of the Fermi–Pasta–Ulam–Tsingou (FPUT) problem, exploring nonlinear dynamics and energy recurrence in a system of coupled particles.

## Overview

The FPUT problem originated from an early numerical experiment investigating how energy spreads through a nonlinear system. Contrary to expectations of thermal equilibrium, energy was observed to return periodically towards its initial state — a phenomenon known as FPUT recurrence.

This project investigates this behaviour through numerical simulation of the FPUT system.

## Numerical Simulation

The simulation was implemented in Python using NumPy and models a chain of 32 particles with nonlinear interactions.

- Implemented the FPUT-α and FPUT-β models
- Used the velocity Verlet symplectic integration method
- Simulated 50,000 time steps with Δt = 0.01
- Analysed energy transfer between vibrational modes
- Investigated how nonlinear interaction strength affects recurrence behaviour

## Results

The simulations demonstrate the characteristic FPUT recurrence: energy initially spreads from the first vibrational mode into higher modes before partially returning to the initial mode.

Increasing the nonlinear interaction strength also produces less regular recurrence behaviour.

## Research Poster

The full methodology, mathematical model, results and discussion are available in the [research poster](FPUT_Research_Poster.pdf).

## Technologies

Python · NumPy · Numerical Methods · Data Visualisation
