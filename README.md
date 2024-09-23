# Computational Neuroscience Course - 2022  
## Neuronal Modeling and Simulation

### Course Overview
This course is centered on the implementation and analysis of neuronal models and learning mechanisms, providing insights into how individual neurons and neural networks operate. The main objective is to simulate neuron behavior, examine synaptic plasticity, and explore neural interactions through computational experiments. Python, along with libraries like NumPy and Matplotlib, is used for coding simulations and visualizing results.

### Course Assignments

#### **Assignment 1: Neuronal Model Implementation**
In this assignment, the focus was on simulating and analyzing three different neuronal models:

- **LIF (Leaky Integrate-and-Fire)**
- **ALIF (Adaptive Leaky Integrate-and-Fire)**
- **AELIF (Adaptive Exponential Leaky Integrate-and-Fire)**

The objective was to simulate the response of these neuron models to various input currents (constant, linear, and sinusoidal) and study their behavior by plotting voltage over time, input currents, and firing rates. The experiment investigated how different model parameters influence neuron spiking activity and frequency.

#### **Assignment 2: Neuronal Population Simulation**
Building on the first assignment, this task involved simulating populations of neurons. The key goals included:

- **Neuron-to-Neuron Connection**: Establishing connections between pairs of neurons, applying different excitatory and inhibitory currents, and analyzing how they interact.
- **Neuronal Population**: Simulating a network of excitatory and inhibitory neurons to observe collective behavior, visualized using raster plots to track spiking activity.
- **Inter-Population Connections**: Connecting multiple neuronal populations, analyzing their interactions over time, and studying how spiking in one population influences another.

#### **Assignment 3: Learning Processes in Neurons**
This assignment explored neural learning mechanisms, focusing on Spike-Timing Dependent Plasticity (STDP). Two main experiments were conducted:

- **STDP Learning**: Simulating a network of three interconnected neurons under varying input currents (constant, sinusoidal, and step-function) to study how spike timing impacts synaptic weight changes.
- **Reward-Based STDP Learning**: A simple input-output neural network was trained using reward-based STDP. Synaptic weights were adjusted based on reward signals, allowing the network to learn to produce the correct spike outputs. Training was performed using a dataset of predefined input currents and expected spike outputs.

### Course Objectives
- Implement and simulate different neuronal models (LIF, ALIF, AELIF).
- Analyze neuronal behavior under different input conditions.
- Understand neuronal population dynamics and interactions.
- Explore neural learning mechanisms using STDP and reward-based learning.

# Upload Format
Your directory name should be ** NAME-STUDENTNUMBER **

and you have to create a directory for each project in your directory

ComputationalNeuroscienceProjects    
│
└───Projects
│   │   
│   └───AliSaleh-9722053
|       |      |
│       │      └───Project1
│       │      |    project1.py
│       │      |    project1-report.pdf
│       │      |
│       │      └───Project2
│       │      |    project2.py
│       │      |    project2-report.pdf

