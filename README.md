
# Pesquisa-Doutorado-Direto

 <div align="justify">Pesquisa-Doutorado-Direto contains a set of data and information relating to researches involving Structural Integrity Monitoring (SHM) via Electromechanical Impedance (EMI) and Guided Waves (GW). The studies were carried out on a 6063-T5 aluminum alloy beam with PSI-5H4E piezoelectric transducers from Piezo Systems attached to its surface. This benchmark presents the experimental methods used for both techniques (EMI and GW). The experiments involve the collection of signals considering structural conditions without damage, with damage and periocity under temperature variations. The data set is valuable for validating SHM algorithms at different temperatures and structural conditions.

Computer codes were also developed involving the modeling of EMI and GW techniques for these different structural and environmental conditions.

## Data Access

Data are available for non-commercial research under the following terms: (i) the GMSInt Laboratory and UNESP/Ilha Solteira should be recognized as the source of the data; (ii) publications should include references pertinent to the publications of GMSInt members and SHM Lab UNESP/Ilha Solteira; (iii) it is necessary to cite this benchmark.

To download the benchmark dataset, including the experimental signals collected and the developed computational codes, request access to: ...

## Experiments for the collection of EMI signals

The experiment consisted of collecting electromechanical impedance signals from a 6063-T5 aluminum alloy beam containing a PSI-5H4E piezoelectric transducer from Piezo Systems attached to its surface, as shown in the Figure below.

![https://github.com/Lorena591/Pesquisa-Doutorado-Direto/blob/main/VigaPZT.jpg](https://github.com/Lorena591/Pesquisa-Doutorado-Direto/blob/main/VigaPZT.JPG)

The figure below shows a schematic of the experimental setup utilized. It was used a National Instruments board, model NI-USB 6211 (16 bits); a computer containing the software with the impedance analyzer developed by Baptista and Filho (2009) in LabVIEW environment; and a protoboard containing a resistance of 10 k&#969, which acts as an auxiliary circuit whose function is to limit the voltage in the piezoelectric transducer, thus avoiding potential damage to this device. The data acquisition (DAQ) board is responsible for capturing the response signal and, simultaneously, transmitting the excitation signal to the piezoelectric transducer. The excitation signal is generated by the impedance analyzer, which also calculates the electromechanical impedance based on the response signal captured by the DAQ. This software includes procedures for adjusting the measurement system and the excitation signal according to the user's wishes. 

The aluminum beam was placed inside a thermal chamber from the brand Thermotron S-Series to simulate ambient temperature variations. This beam was positioned on a foam layer to simulated a free-free boundary condition. Geometric and material properties of the piezoelectric transducer and the beam at 24°C are presented in Tabs. \ref{tab:PZT} and \ref{tab:Viga}, respectively.


The signals were measured in a temperature range from 24°C to 70°C, which correspond to a large portion of the structures in operation. It was utilized a step of 5°C for the non-damage condition. In order to excite the structure, it was applied a sinusoidal frequency sweep with an amplitude of 1 V in a frequency range of 1 Hz to 100 kHz, with a step size of 1 Hz. The signals were gauged only during heating. Thirty signals were collected for each temperature and a sampling rate of 250 kS/s was employed.

#### References
Baptista, F.G. and Filho, J.V., 2009. “A new impedance measurement system for pzt based structural health monitoring”. IEEE Transaction on Instrumentation and Measurement, Vol. 58, No. 10, pp. 3602–3608

## Authors
- Lorena Lopes Dias (UNESP/FEIS)
- Camila Gianini Gonsalez-Bueno (UNESP/FEIS)
- Douglas Domingues Bueno (UNESP/FEIS)

## How to cite

This dataset was used in these publications:



## Funding
São Paulo Research Foundation (FAPESP), Grant Number 2021/12008-2

![fapesp](https://github.com/Lorena591/Pesquisa-Doutorado-Direto/blob/main/fapesp.png)


</div>
