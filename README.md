# 7th_semester_Project
Design and Simulation of Double Metal Ge-pocket Double Gate TFET as LIF Neurons.

Here,we're simulating the DG-TFET as LIF Neurons because it has better performance than its counter part i.e. MOSFET like it has low subthreshold swing and it works on Band to Band Tunneling so Short channel effects would not be there.
The silicon based Ge-pocket Double Gate tunnel field effect transistor (DG-TFET) demonstrates artificial neuromorphic property for leaky-integrate-fire (LIF) neurons.
DG-TFET based LIF neuron is a potential solution for implementing large-scale spiking neural networks (SNN) because of its compact circuitry and better efficiency.

![image](https://github.com/Ajay051839/7th_semester_Project/assets/81469239/84008cf5-b352-4673-9f49-a3762f921e1a)-Basic structure of Ge-pocket DGTFET.
In DG-TFET metal electrodes are used for source and drain terminals are chosen to induce n+ drain and p+ source in the intrinsic silicon film to realize the p+-i-n+ structure.

############LIF(Leaky Integrate Fire) Neurons--------------------------
LIF neurons mimic natural neurons, guiding the development of artificial systems for advanced cognitive tasks, mirroring the human brain.
Dendrites, serving as receptive branches in LIF neurons, gather and transmit impulses, while the connections to the cell body, analogous to synaptic weights, influence the neuron's response, reflecting the role of synapses in biological neurons.
Synaptic weights in LIF neurons determine connection strength, mimicking biological synapses in signal transmission.
Artificial neurons, inspired by LIF neurons, employ algorithms for signal integration, resembling the summation process from dendrites to the cell body, mirroring the biological activation state.

DG-TFET as LIF Neuron---
The DG-TFET device working as a LIF neuron reported around 0.6 THz spiking frequency which is approximately 9 orders higher as compared to that of a biological neuron (f0 = 10 Hz). 
DG-TFET exhibits a very low threshold voltage of 0.5V and minimum energy of  1.5aJ to fire a spike signal which is very low approximately 4 orders lower power consumption as compared to the actual neuron (∼10−14 J/spike).
The TFET LIF neuron relies on the band-to-band tunneling mechanism for signal processing. This tunneling process contributes to the device's ability to transmit signals efficiently, enabling the TFET to function as a neuromorphic element with reduced energy consumption compared to traditional transistor-based neurons.

The DG-TFET LIF neuron operates efficiently in the subthreshold range, utilizing tunneling processes and consuming around four orders of magnitude less power compared to a real neuron.
![image](https://github.com/Ajay051839/7th_semester_Project/assets/81469239/3e4eaada-2d64-4b40-ab95-7cf130c126e5)




Our simulated Obtained structure of DMG Ge-Pocket DG-TFET-![image](https://github.com/Ajay051839/7th_semester_Project/assets/81469239/2b80b296-2704-4719-a5d7-f9451243c47b)

Results---
![image](https://github.com/Ajay051839/7th_semester_Project/assets/81469239/fe131ce9-b4b3-46ca-98b4-9b2584e4beb6)
![image](https://github.com/Ajay051839/7th_semester_Project/assets/81469239/424868b8-ea94-4e5d-aa0f-9980ea3b64d2)

Conclusion- We obtained steeper slope in Id vs Vgs Characteristics of TFET which helps in faster switching and is also energy efficient than MOSFET. Also Saturation will be reached faster in case of DG-TFET.






