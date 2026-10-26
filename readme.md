# Parameter Estimation of Time-Varying Amplitude Chirp Signal Based on FRFT [with MATLAB Code]

Through this article, we believe that using the fractional Fourier transform to estimate parameters and time delays for time-varying amplitude Chirp signals is feasible. This is particularly true when the signal-to-noise ratio is high, with the estimation accuracy almost on par with that of constant amplitude Chirp signals. Moreover, even in cases where the signal amplitude is unknown or varies over time, it is still possible to accurately estimate parameters and time delays, demonstrating the excellent adaptability and practical significance of the FRFT method.
Introduction - Chirp signals, also known as linear frequency modulation (LFM), are a representative type of signal in the field of signal processing. They have extensive applications in various research fields such as radar, sonar, communication, geological exploration, seismic detection, and medical imaging [1][2].
For instance, in seismic exploration, we use controllable sources of vibrations [3][4]. The controllable sources are essentially Chirp signals because these signals can achieve high resolution and increase estimation accuracy. After being amplified by power amplifiers, the Chirp signals drive vibrator devices, which convert electrical signals into mechanical vibrations. These vibrations then penetrate the earth's crust through a dense coupling baseplate to form seismic waves. When these waves encounter a reflective interface, they are reflected back, and the surface sensor arrays receive them [5]. By analyzing and processing the scanned signals and echo signals using relevant methods, we can determine the time delay of the Chirp signal, thereby locating the seismic reflection surface. The principle of controllable sources is illustrated in Figure 1.1.
Additionally, Chirp signals have numerous applications in other fields, such as for space linear arrays where the signal distributed along the array can be approximated as a Chirp signal when the source is located near the array. In the field of wireless communication, Chirp signals and time-varying filters are often used for system identification [6]. The study of Chirp signals holds significant theoretical and practical importance.
Currently, there are many methods for estimating parameters and delays of constant amplitude Chirp signals, such as the Wigner-Ville distribution method [7], phase expansion method [8], higher order statistics [9], and modern mutual spectrum estimation, etc. These methods can achieve high precision in estimating parameters and delays of constant amplitude Chirp signals.
In fact, time-varying amplitude Chirp signals are more widely used in practical engineering applications. When performing actual signal processing, the amplitude of the signal may not remain constant due to factors such as attenuation or other reasons. For example, Gaussian minimum shift keying signals used in mobile communications are baseband signals with Gaussian pulses, which are not ordinary square waves, representing time-varying amplitude Chirp signals; radar detection system echo signals can also be considered time-varying amplitude Chirp signals because the echo signals are influenced by two factors: Doppler shift caused by moving targets detected by the radar, and distortion of signal amplitude due to scattering, as well as interference modulation during transmission and recording processes [11]. In electrocardiogram recorders, interference from power line disturbances and modulation effects caused by ionospheric scintillations in short wave communication also produce time-varying amplitude Chirp signals. Therefore, estimating parameters and delays of time-varying amplitude Chirp signals holds more practical engineering significance.
The current research status on the estimation of time-varying amplitude Chirp signals is as follows:
1. Time-varying amplitude Chirp signals can be viewed as AM-FM signals. Currently, there are three main methods for estimating time-varying amplitudes: energy separation-based methods, differential equation-based methods, and cyclic stability-based methods.
(I) Energy Separation Method
The essence of the energy separation method is to define an energy operator that acts on the time-varying amplitude Chirp signal, resulting in a signal energy function. The parameters of the signal can then be estimated through the energy function [12]. This method is only applicable to single-component time-varying amplitude Chirp signals, and it requires the use of a discrete-time Teager-Kaiser energy function to extract the AM and FM information from the discrete-time time-varying amplitude Chirp signal, along with the corresponding filter bank being digitally implemented. This method is still difficult to implement in practice.
(II) Differential Equation Method
Compared to the energy separation method, the differential equation method can analyze the parameters of multi-component time-varying amplitude Chirp signals. It describes a time-varying amplitude Chirp signal using differential equations. If the coefficients of the differential equations and their characteristic equation pole values can be obtained, the parameters of the signal can be estimated. However, in practical applications, the coefficients of the differential equations cannot be predicted. Literature [13] proposes some methods for estimating the coefficients of the differential equations, but they are very complex to calculate.
(III) Cyclic Stability Method
The essence of the cyclic stability method is to transform the time-domain time-varying amplitude Chirp signal into a constant-amplitude harmonic process in the lag domain τ, and then the "harmonic amplitude" can be obtained using the harmonic restoration method. This method leverages the idea of polynomial reduction. Like the energy separation method, this method is also not suitable for multi-component signals, and in the presence of additive noise, the modeling of the signal is also more complex [14].
The theoretical foundation of fractional Fourier transforms For the traditional Fourier transform, it can be seen as a transformation that rotates the time axis counterclockwise by 90 degrees to the frequency axis. On the other hand, fractional-order Fourier transform breaks the rotation angle limit, meaning that the rotation angle of fractional-order Fourier transform can be any angle α. Therefore, fractional Fourier transform can be regarded as a generalized Fourier transform, which not only retains the original properties and characteristics of traditional Fourier transform but also adds new features.
Definition of fractional Fourier transform
There are various different definitions for fractional Fourier transforms. These definitions are equivalent to each other. Different physical interpretations correspond to different definition forms. This section will provide the basic definition of fractional Fourier transform from a mathematical perspective.
Parameter Estimation of Time-Varying Amplitude Chirp Signal Based on FRFT
MATLAB Simulation
\n        \n  
\n        \n  
\n        \n      \n        \n  

## Images

![Parameter Estimation of Time-Varying Amplitude Chirp Signal Based on FRFT [with MATLAB Code]](01.jpg)
![Parameter Estimation of Time-Varying Amplitude Chirp Signal Based on FRFT [with MATLAB Code]](02.jpg)
![Parameter Estimation of Time-Varying Amplitude Chirp Signal Based on FRFT [with MATLAB Code]](03.jpg)
![Parameter Estimation of Time-Varying Amplitude Chirp Signal Based on FRFT [with MATLAB Code]](04.jpg)
![Parameter Estimation of Time-Varying Amplitude Chirp Signal Based on FRFT [with MATLAB Code]](05.jpg)
![Parameter Estimation of Time-Varying Amplitude Chirp Signal Based on FRFT [with MATLAB Code]](06.jpg)
![Parameter Estimation of Time-Varying Amplitude Chirp Signal Based on FRFT [with MATLAB Code]](07.jpg)
![Parameter Estimation of Time-Varying Amplitude Chirp Signal Based on FRFT [with MATLAB Code]](08.jpg)
![Parameter Estimation of Time-Varying Amplitude Chirp Signal Based on FRFT [with MATLAB Code]](09.jpg)
![Parameter Estimation of Time-Varying Amplitude Chirp Signal Based on FRFT [with MATLAB Code]](10.jpg)
![Parameter Estimation of Time-Varying Amplitude Chirp Signal Based on FRFT [with MATLAB Code]](11.jpg)
![Parameter Estimation of Time-Varying Amplitude Chirp Signal Based on FRFT [with MATLAB Code]](12.jpg)
![Parameter Estimation of Time-Varying Amplitude Chirp Signal Based on FRFT [with MATLAB Code]](13.jpg)
![Parameter Estimation of Time-Varying Amplitude Chirp Signal Based on FRFT [with MATLAB Code]](14.jpg)
![Parameter Estimation of Time-Varying Amplitude Chirp Signal Based on FRFT [with MATLAB Code]](15.jpg)
![Parameter Estimation of Time-Varying Amplitude Chirp Signal Based on FRFT [with MATLAB Code]](16.jpg)
![Parameter Estimation of Time-Varying Amplitude Chirp Signal Based on FRFT [with MATLAB Code]](17.png)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
