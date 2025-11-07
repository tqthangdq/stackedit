
# Deep Learning-Based CSI Feedback for Wi-Fi Systems with Temporal Correlation
## Abstract
The framework employs encoder and decoder networks to compress and reconstruct CSI angle parameters:
- Using a trainable vector quantization (VQ) module that enables finite-bit representation through end-to-end training.
- Introduce an angle-difference feedback strategy that exploits the temporal correlation of the angle parameters by feeding back the difference between the current and previous values.
- Preprocessing handles the periodicity of angles.
- Tailored VQ modules compensate for residual quantization errors.
- A Deep Learning-based CSI refinement module at the Access Point, which improve reconstruction by jointly using current and prior feedback.
- Simulation results show that the proposed framework outperforms both standard Wi-Fi feedback and exsting DL-based feedback methods.

## Introduction
- Begin by emphasizing the wireless networks are rapidly evolving to support higher data rate transmission.
- It is assumed that the new wireless technology achieves better throughput by full utilizing Channel State Information CSI.
- 
<!--stackedit_data:
eyJoaXN0b3J5IjpbNjQ0Mjk2MjI2LDQwNTAxMDgyNCwtMTQ2OT
kwNzQ0Niw0OTUxNjQwMjksLTE0MjE0Njk2MjgsLTQwNjgyMzAy
OCw0OTc4MTg4MTAsLTIxMTIxNDYzOTEsOTIzNzMwMjkwXX0=
-->