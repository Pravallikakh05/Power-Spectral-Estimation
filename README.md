# Power-Spectral-Estimation
**Spectral Density Estimation (SDE)** is a process which is used to estimate the power spectral density of a random signal from a sequence of time samples of the signal. The spectral density characterizes the frequency content of the signal. One purpose of estimating the spectral density is to detect any periodicities in the data, by observing peaks at the frequencies corresponding to these periodicities.

**Spectrum analysis**, also referred to as frequency domain analysis or spectral density estimation, is the technical process of decomposing a complex signal into simpler parts. Spectrum analysis can be performed on the entire signal. Alternatively, a signal can be broken into short segments, and spectrum analysis may be applied to these segments.

The techniques for spectral estimation can generally be divided into non-parametric and parametric methods.

The **non-parametric approaches** explicitly estimate the covariance or the spectrum of the process without assuming that the process has any particular structure. Some of the most common estimators in use for basic applications (e.g. Welch's method) are non-parametric estimators closely related to the periodogram.

A few examples of non-parametric spectral density estimation techniques are Periodogram, Bartlett's method, Welch's method, Least-squares spectral analysis, Singular spectrum analysis, and Short-time Fourier transform. 

By contrast, the **parametric approaches** assume that the underlying stationary stochastic process has a certain structure that can be described using a small number of parameters (for example, using an auto-regressive or moving average model). In these approaches, the task is to estimate the parameters of the model that describes the stochastic process. 

A few examples of parametric techniques are Autoregressive model (AR) estimation, Moving-average model (MA) estimation, Autoregressive moving average (ARMA) estimation, and MUltiple SIgnal Classification (MUSIC).

The different methods in this project are implemented on two datasets.
**Data Set 1**: A 128-point real data sequence consisting of unit-amplitude sinusoids at 5 Hz, 15 Hz, and 16 Hz and has sampling frequency fs = 64 samples/second.
**Data Set 2**: Created identical to Data Set #1, but white noise is added such that the signal-to-noise ratio (SNR) is 0 dB.
