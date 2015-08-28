# Option_pricing


This repository contains a code for option pricing using fourier methods when the underlying follows an exponential Levy  dynamic. An important element in option pricing models is modeling stock prices with jumps. Jump (Levy) processes can describe the observed reality of financial markets in a more accurate way than basic diffusion models based onBrownian motion. This  repository contains also  a code to simulate different type of Levy processes (jump diffusion models and infinite activity  models).

By a Discrete Fourier Transform we can obtain an option pice approximation (DFT code).In some cases (the characteristic function and the fourier transform of the payoff are known analytically, when the characteristic function is known but the fourier transform of the payoff is unknown and when calculating the Fourier transform of the payoff is relatively difficult), we can apply FFT algorithm to value options both in the real and fourier spaces (price FFT_real,price FFT_fourier).
