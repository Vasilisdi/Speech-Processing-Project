# Voice Processing and Synthesis Project

## Project Description

This project focuses on processing and analyzing voice signals using MATLAB. It has been carried out for academic purposes - PGS671 Advanced Topics in Speech and Language Processing), as part of the curriculum of the Department of Electrical and Computer Engineering: 

### Part A: Basic Voice Parameter Estimation Algorithms

- **Recording:** Record your name with a sampling frequency of either 16 kHz or 22,050 kHz.
- **Voice Signal Spectrogram:** Plot the spectrogram of the recorded voice signal using Hamming windows of length around 10 ms and 100 ms, with a shift of approximately 5 ms.
- **Voiced/Unvoiced Segments Estimation:** Design an algorithm to distinguish voiced, unvoiced, and silent segments of the signal using energy and zero-crossing rate calculations.
- **Fundamental Frequency Estimation:** Implement a method to find the fundamental frequency (pitch) of voiced segments using methods like autocorrelation or cepstrum.

Searching voiced, unvoiced and silenced segments of the waveform frames. Here the fundamental frequency of each frame has been calculated too. 

![Waveform Frames Analysis](https://github.com/Vasilisdi/Speech-Processing-Project/assets/24864439/1801f03a-daca-41ca-8236-30a3f8a4b1a1)


### Part B: Simple Voice Synthesis System

- **Synthetic Sound Generation:** Generate a synthetic sound signal with a sampling frequency of 10 kHz and a duration of 3 seconds, composed of six vowels (/AO/, /IY/, /UH/, /EH/, /AH/, /IH/) each lasting 0.5 seconds.
- **Glottal Pulse Model:** Model the glottal pulse using the given equations and parameters.
- **Vocal Tract Model:** Model the vocal tract as a filter using the given formant frequencies and bandwidths.
- **Radiation Load Model:** Model the radiation load using the provided equation.
- **Sound Synthesis:** Synthesize the voice signal by convolving the above components.
- **Signal Analysis:** Analyze the synthesized signals and compare them with natural voice signals.

### Details about the Project:

#### P(z) Calculation:
![P(z) Calculation](https://github.com/Vasilisdi/Speech-Processing-Project/assets/24864439/0b647f07-c5dc-4d37-9744-6ce04ad2feb1)

#### G(z) Calculation:
![G(z) Calculation](https://github.com/Vasilisdi/Speech-Processing-Project/assets/24864439/39cb6242-797f-4f01-8aa6-f7b4a542fd1f)

#### V(z) Calculation:
![V(z) Calculation](https://github.com/Vasilisdi/Speech-Processing-Project/assets/24864439/7f6ba69b-55b5-4f16-bc17-df4df808226c)

#### R(z) Calculation:
![R(z) Calculation](https://github.com/Vasilisdi/Speech-Processing-Project/assets/24864439/9e34f35d-1ac0-49e6-9ab4-4c33c4a8a351)

#### S(z) Combined Transfer Function:
![S(z) Combined Transfer Function](https://github.com/Vasilisdi/Speech-Processing-Project/assets/24864439/c3df9c8e-08c0-4686-8194-a420d2e96b8f)


## Usage

To use the MATLAB code provided in this repository, simply clone or download the repository and run the MATLAB scripts in a MATLAB environment.


## Contributors

- Paschalis Moschogiannis (Contact: [pmoschogiannis@uth.gr](mailto:pmoschogiannis@uth.gr))
- Vasileios Dimitriou (Contact: [vasildimitriou@uth.gr](mailto:vasildimitriou@uth.gr))

## License

This project is licensed under the

⚖ [GNU General Public License Version 3 (GPLv3)](LICENSE)

</br>

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-purple.svg)](https://www.gnu.org/licenses/gpl-3.0)
