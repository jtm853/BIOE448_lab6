This code was written during a Microcontrollers lab on February 26, 2025 taught by Dr. James Long.

Here, we use a pulse sensor and an Arduino to measure and calculate a patient's heart rate (BPM). The driving code for this project is found in this repository.
In order to do signal processing on a constantly updating waveform, we use a series of checkpoints and flags with threshold values to know when we are between peaks. We then measure the pulse duration and calculate a BPM which is displayed on the serial plotter.
