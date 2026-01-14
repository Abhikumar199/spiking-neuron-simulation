# Hodgkin–Huxley–type Cortical Neuron Models  
**NEURON Simulator + Python Interface**

## Overview
This repository contains simulations of **conductance-based cortical neuron models** reproduced from **ModelDB** using the **NEURON simulator** with a **Python interface**.  
The project focuses on understanding **biophysically realistic neuronal firing behavior**, such as regular spiking, in response to injected current.

Cortical pyramidal neurons are the main neurons in the brain cortex (thinking, memory, perception).


### What is a cortical pyramidal neuron?

Found in the cerebral cortex
Shape: pyramid-like cell body
Function:
Thinking
Learning
Memory
Decision making

They are excitatory neurons (send signals forward)
They are the most common neurons in the cortex.
The models are based on Hodgkin–Huxley–type ion channel dynamics and represent different cortical neuron types (e.g., pyramidal neurons, interneurons).

---

## Model Source
- **Repository:** ModelDB  
- **Model:** Hodgkin–Huxley–type Cortical Neuron Models  
- **Simulator:** NEURON  
- **Language:** HOC + MOD (model definition), Python (control & analysis)

All original `.hoc` and `.mod` files are provided by the model authors via ModelDB.

---

## Workflow

### 1. Model Selection
- Selected a published cortical neuron model from **ModelDB**
- Downloaded the complete model as a **ZIP archive**

### 2. File Setup
- Unzipped all files into a single project folder
- The folder contains:
  - `.mod` files → ion channel mechanisms
  - `.hoc` files → neuron templates and demo scripts
  - README and reference figures

### 3. Compilation (Windows)
- Opened **Command Prompt / Anaconda Prompt** (not Git Bash)
- Navigated to the folder containing the `.mod` files
- Compiled mechanisms using:
  ```bash
  mknrndll


###One golden rule (remember forever)

Always load mosinit.hoc before any demo_*.hoc file


