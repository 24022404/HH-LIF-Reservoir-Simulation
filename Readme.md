# Assignment: Exploring Neuron Models and Neural Networks

## Đề bài

Quiz (20%) = Gửi code và báo cáo việc thực hiện mô phỏng 3 mô hình 
(Hodgkin-Huxley, Leaky Integrate-and-Fire, Reservoir NN), theo 
hướng dẫn Assignment (đã giao 3/11) về Exploring Neuron Models and 
Neural Networks. Deadline: 30/12.

---

## Objective
Investigate and simulate classic biological neuron models and brain-inspired neural network architectures.

## 1. Theoretical Investigation of Neuron Models
Study the following neuron models and learning algorithm:
- The Hodgkin-Huxley (HH) Model.
- The Leaky Integrate-and-Fire (LIF) Model.
- The Hebbian Learning algorithm.

## 2. Theoretical Investigation of Spiking Networks
Study neural network architectures that utilize spiking mechanisms, inspired by the brain:
- Spiking Neural Networks (SNNs).
- Reservoir Neural Networks (RNNs).

## 3. Programming Simulation (Python)
Implement Python simulations for the models based on the following specific requirements:

### (i) Hodgkin-Huxley Model Simulation for Action Potential:
**Requirement:** Define all necessary parameters and the six rate functions (αx, βx) of the ion channels. Use an initial membrane potential V0 = −65 mV and apply an external input current Ix (Step Input with magnitude 20 µA/cm²).

Plot the membrane potential (V), the Sodium current (INa), and the Potassium current (IK) over time. Explain the roles of INa and IK during depolarization and repolarization.

### (ii) Leaky Integrate-and-Fire (LIF) Model Simulation:
Simulate the change in the membrane potential of a neuron when it receives a square wave input current using the LIF model.

### (iii) Reservoir Neural Network for Time Series Prediction:
Use the Reservoir Neural Network model (e.g., Echo State Network) to simulate a time series prediction experiment (e.g., using the Mackey-Glass series), demonstrating the accurate prediction of both near-future (x(t + 10)) and far-future (x(t + 100)) values.

---

## References

### On Hodgkin-Huxley, LIF Models and Hebbian Learning:
[1] Trappenberg, T. P. (2023). Fundamentals of computational neuroscience (3rd ed.). Oxford University Press.

[2] Dayan, P., & Abbott, L. F. (2001). Theoretical neuroscience: Computational and mathematical modeling of neural systems (1st ed.). MIT Press.

### On Spiking Neural Networks and Reservoir Computing:
[3] Tavanaei, A., Ghodrati, M., Kheradpisheh, S. R., Masquelier, T., & Maida, A. S. (2019). Deep learning in spiking neural networks. Neural Networks, 111, 47–52.

[4] Lukoˇseviˇcius, M., & Jaeger, H. (2009). Reservoir computing approaches to recurrent neural network training. Computer Science Review, 3 (3), 5–17.