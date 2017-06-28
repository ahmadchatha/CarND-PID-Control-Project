# Reflections

## describe the effect of the P, I, D component of the PID algorithm in their implementation. Is it what you expected?
The final values selected for PID components are as follows:
Kp = 0.1
Ki = 0.001
Kd = 3.0
The p (propotional) component is propotional to the cross track error. The idea is to stay close to a CTE value of 0 so that the car stays around the center.
The i (integral) component sums up the cross track error to conteract the bias such as poorly alligned steering.
The d (differential) component acts against the oscillations produced by the p component and contributes to the smoothness.

## how were the final hyperparameters chosen(P, I, D coefficients)?
The final parameters were chosen through trail and error based on the effects of the P,I and D components as stated above.
