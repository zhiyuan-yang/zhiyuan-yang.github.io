## GP-Regression-Extended-Target-Tracking
time: December, 2022

code implementation: https://github.com/zhiyuan-yang/GP-Regression-Extended-Target-Tracking

Based on paper [1], we use Gaussian process regression to recursively get the measurement function of extended target and then use Extended Kalman Filter(EKF) to track it.
Future work can be done by subsituting the EKF with more advanced non-linear filter such as Rao-Blackwellised Particle filter, Variation Bayes Filter, etc.

[1] N. Wahlström and E. Özkan, ‘Extended Target Tracking Using Gaussian Processes’, IEEE Transactions on Signal Processing, vol. 63, no. 16, pp. 4165–4178, Aug. 2015, doi: 10.1109/TSP.2015.2424194.

## Radar Emitter Identification based on CNN
time: May, 2022

code implementation: https://github.com/zhiyuan-yang/Radar-Emitter-Identification-based-on-CNN

In this project, we use Pseudo Wigner-Ville Distribution to extract the time-frequency feature of different modulated radar signals and then 
using convolution neural network(CNN) to classify the radar signals. The article has been received by the 14th Chinese Institute of Electroincs(CIE) DSP Conference.