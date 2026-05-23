# Dynamic-hysteresis-losses-of-magnetic-nanoparticles-used-in-magnetic-hyperthermia
This repository contains two independent Mathematica implementations for estimating the dynamic hysteresis loops of magnetic nanoparticles under alternating magnetic fields, relevant to magnetic hyperthermia applications.
The first code describes the nonlinear magnetization dynamics of single-domain ferromagnetic nanoparticles using a stochastic double-well rate-equation model based on the Stoner–Wohlfarth theory. The second code implements Linear Response Theory (LRT) for superparamagnetic nanoparticles, where magnetization follows the applied field linearly through relaxation dynamics and AC susceptibility.
Both models are computationally efficient alternatives to full micromagnetic simulations based on the Landau–Lifshitz–Gilbert (LLG) equation and are particularly suitable for ensemble-level studies involving large numbers of nanoparticles and statistical distributions of particle properties.

1. Double-Well Rate Equation Model (File name: Dynamic loop FM_SD)
Dynamic Hysteresis of Single-Domain Ferromagnetic Nanoparticles
Overview
This Mathematica code estimates the dynamic hysteresis loop of magnetic nanoparticles by modeling each nanoparticle as a bistable magnetic system with two energy minima separated by an energy barrier. The model is based on:
The Stoner–Wohlfarth coherent rotation model, Thermal activation over anisotropy energy barriers, Néel–Brown relaxation theory
Master/rate equations for occupation probabilities, The code is designed for magnetic hyperthermia studies where nonlinear hysteresis losses dominate energy dissipation.
2. Linear Response Theory (LRT) Model (File name: Dynamic loop SPM)
Dynamic Hysteresis of Superparamagnetic Nanoparticles
Overview
This Mathematica code implements Linear Response Theory for superparamagnetic nanoparticles subjected to weak alternating magnetic fields.
The model assumes:
Linear relation between magnetization and applied field, Small field amplitudes, No irreversible switching,Dynamic magnetization governed by magnetic relaxation
