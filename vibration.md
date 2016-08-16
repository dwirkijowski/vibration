# Vibration Testing

## Overview

This project proposes a new method of Structural Identification **(St -Id)** for the safety assessment of structural-foundation systems. Modern St-Id methods largely focus on low-level mechanism responses that do not completely represent a structure's response to higher levels of excitation. Exploring these higher levels approach the safety limit of destroying a structure but provide valuable data to understand nonlinear interaction between the substructure and foundation.

## Project Objectives

1. Develop, evaluate, and refine a series of force vibration testing and control strategies to capture response measurements indicative of key performance attributes of substructure/foundation and superstructure systems

2. Develop, evaluate, and refine a series of both model-free and model-based data interpretation frameworks for structural system identification and assessment

3. Perform a validation of the testing/control strategies and data interpretation frameworks on an operating structure with known substructure, foundation, and soil characteristics.

## Literature Review

Below are a list of sources relevant to the topics of vibration monitoring and foundation-substructure modeling.

##### Rao, *"Mechanical Vibrations, Fifth Edition"*, Pearson Education Inc, 2011
###### 10.7 Dynamic Testing of Machines and Structures (900)
* Use of operational deflection-shape measurements under steady-state frequency of the system.
* Deflected shape measured w.r.t. operating conditions only

###### 10.8 Experimental Modal Analysis (900)
* Resonance response when force frequency is equal to natural frequency.
* **Exciter** is used to input known force into the structure.
* **Transducer** measures structural response.
* **Signal Conditioner** translates transducer output for signal analysis
* **Analyzer** processes signal, commonly using *first Fourier transform __(FFT)__* analysis. Analog time-domain signals *x(t)* converted into digital frequency-domain data.
* **Coherence Function** defined as measure of noise present in signals.
* **Single Degree of Freedom (SOF)** approach analyzes frequency response partitioned into several frequency ranges such that each range brackets one peak.
