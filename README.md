<h1 align="center"> HOC Coding & NEURON Simulation Repository</h1>

<p align="center">
  <strong>Computational Neuroscience • Hodgkin–Huxley Modeling • NEURON Simulator • NeuroAI</strong>
</p>

<p align="center">
  A complete beginner-to-advanced guide for learning HOC, NEURON, Python integration, ion channel modeling, 
  and electrophysiological simulations.
</p>

---

## Overview

This repository is a comprehensive collection of:

- ✔ HOC scripts + Description
- ✔ Python–NEURON integration examples  
- ✔ Hodgkin–Huxley (HH) models  
- ✔ Compartmental neuron modeling  
- ✔ Current clamp stimulation  
- ✔ Documentation & explanations  
- ✔ Visualization of membrane voltage and ion currents  

It is for prcatice  in **Computational Neuroscience, Biomedical Engineering, AI + Brain modeling**,

---

#  **What Will Learn**

### 🔹 Basics of NEURON & HOC  
- What is a `Section`?  
- Understanding `soma`, dendrites, etc.  
- Membrane mechanisms (`hh`, `pas`, etc.)  
- Recording of variables  

### 🔹 Ion Channel Dynamics  
- Sodium current (`ina`)  
- Potassium current (`ik`)  
- Leak current (`il`)  
- Gating variables (`m`, `h`, `n`)  

### 🔹 Python + NEURON  
- Running NEURON from Python  
- Using `h.load_file("stdrun.hoc")`  
- Recording vectors & plotting  

### 🔹 Building Realistic Neuron Models  
- Multi-compartment modeling  
- Injecting currents  
- Generating spikes  
- Plotting voltage traces & ionic currents  

---

#  Installation Guide

## Install NEURON

 install NEURON via website:

https://neuron.yale.edu/neuron/

Or via pip:

```bash
pip install neuron




## Parameter Perturbation & Spike Analysis

Parameter perturbation analysis was performed by systematically varying the sodium channel conductance while keeping all other parameters constant. For each perturbation, neuronal activity was simulated using a Hodgkin–Huxley model, and spike times were detected using a voltage threshold crossing method. Increasing sodium conductance led to enhanced excitability and increased firing rates, while reduced conductance suppressed spike generation. This demonstrates the sensitivity of spike dynamics to ion-channel parameters.