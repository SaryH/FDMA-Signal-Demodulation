# FDMA-Signal-Demodulation
Project required for my Communication Systems course at Birzeit University. We are given an FDMA signal that contains sevel audio files mixed together, modulated using Double Side Band Suppress Carrier modulation (DSB-SC), the code first demodulates the signal by multiplying it with the cosine of one of the carrier frequencies, it then passes the signal to a low pass filter, and then to a downsampler. Only then the original audio files can be heard one by one.

Note: Code structure and the low pass filter implementation are inspired from my professor's code (@mkjubran).
