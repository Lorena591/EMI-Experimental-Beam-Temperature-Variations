
# EMI-Experimental-Beam-Temperature-Variations

 <div align="justify">EMI-Experimental-Beam-Temperature-Variations contains a set of data and information relating to researches involving Structural Integrity Monitoring (SHM) via Electromechanical Impedance (EMI) technique. The studies were carried out on a 6063-T5 aluminum alloy beam with a PSI-5H4E piezoelectric transducer (PTZ) from Piezo Systems attached to its surface. This benchmark presents the experimental methods used for the EMI technique. The experiments consists of collectioning signals for undamaged structural conditions under temperature variations. The data set is valuable for validating SHM algorithms at different temperatures.

## Data Access

Data are available for non-commercial research under the following terms: (i) the GMSINT Laboratory and UNESP/Ilha Solteira should be recognized as the source of the data; (ii) publications should include references pertinent to the publications of GMSINT members; (iii) it is necessary to cite this benchmark.

To learn more about the reserach group GMSINT: https://bit.ly/3RSReVl

The experimental signals measured are stored in the folder "Experimental_Signals_EMI" (https://github.com/Lorena591/EMI-Experimental-Beam-Temperature-Variations/tree/main/Experimental_Signals_EMI) contained in the main branch.

## Experiment to collect EMI signals

The experiment consisted of collecting electromechanical impedance signals from a 6063-T5 aluminum alloy beam containing a PSI-5H4E piezoelectric transducer from Piezo Systems attached to its surface, as shown in the digure below.

![https://github.com/Lorena591/Pesquisa-Doutorado-Direto/blob/main/VigaPZT.jpg](https://github.com/Lorena591/Pesquisa-Doutorado-Direto/blob/main/VigaPZT.JPG)

The figure below shows a schematic of the experimental setup utilized. It was used a National Instruments board, model NI-USB 6211 (16 bits); a computer containing the software with the impedance analyzer developed by Baptista and Filho (2009) in LabVIEW environment; and a protoboard containing a resistance of 10 kΩ, which acts as an auxiliary circuit whose function is to limit the voltage in the piezoelectric transducer, thus avoiding potential damage to this device. The data acquisition (DAQ) board is responsible for capturing the response signal and, simultaneously, transmitting the excitation signal to the piezoelectric transducer. The excitation signal is generated by the impedance analyzer, which also calculates the electromechanical impedance based on the response signal captured by the DAQ. This software includes procedures for adjusting the measurement system and the excitation signal according to the user's wishes. 

![setup](https://github.com/Lorena591/Pesquisa-Doutorado-Direto/blob/main/Setup.JPG)

The aluminum beam was placed inside a thermal chamber from the brand Thermotron S-Series to simulate ambient temperature variations, showed in the figure below(a). This beam was positioned on a foam layer to simulated a free-free boundary condition, as shown in the figure below(b). Geometric and material properties of the piezoelectric transducer and the beam at 24°C are presented in the tables below.

![camara_viga](https://github.com/Lorena591/Pesquisa-Doutorado-Direto/blob/main/camara_viga.JPG)

Table 1 - Geometric and material properties of the PSI-5H4E piezoelectric transducer at 24°C.
| Property | Symbol | Value |                                                                 
| -- | -- | -- |                                                                                                   
|Length | $$L_p$$ | 13 mm|                     
|Width |$$b_p$$ |12 mm|
|Thickness |$$h_p$$ |0.2667 mm|
|Compliance |$${S}_{11}^E$$|11 1.6129×10−11 Pa−1|
|Density |$$\rho_p$$ |7800 kg/m3|
|Piezoelectric constant |$$\bar{d}_{31}$$ |-327.18×10−12 m/V|
|Dielectric constant |$$\bar{\varepsilon}_{33}^T$$ |3.24783.3630×10−8 F/m|
|Distance from the first PZT’s end to the origin| $$x_1$$ |81 mm|
|Distance from the second PZT’s end to the origin| $$x_2$$| $$x_1+L_p = 94 mm$$   |

Table 2 - Geometric and material properties of the 6063-T5 aluminum alloy beam at 24°C.
| Property | Symbol | Value |                                                                 
| -- | -- | -- |           
|Length | $$L_b$$| 498 mm |
|Width | $$b_b$$ | 12 mm |
|Thickness | $$h_b$$ | 3 mm |
|Young's modulus | $$\bar{E}_b$$ | 69 GPa|
|Density | $$\bar{\rho}_b$$| 2680 kg/m3|
|Coefficient | $$\alpha$$| 0.0011 |
|Coefficient | $$\beta$$ | 3.5315×10−8 |

The signals were measured in a temperature range from 24°C to 70°C, which correspond to a large portion of the structures in operation. It was utilized a step of 5°C for the non-damage condition. In order to excite the structure, it was applied a sinusoidal frequency sweep with an amplitude of ±1 V in a frequency range of 1 Hz to 100 kHz, with a step size of 1 Hz. The signals were gauged only during heating. Thirty signals were collected for each temperature and a sampling rate of 250 kS/s was employed.

#### References
Baptista, F.G. and Filho, J.V., 2009. “A new impedance measurement system for pzt based structural health monitoring”. IEEE Transaction on Instrumentation and Measurement, Vol. 58, No. 10, pp. 3602–3608

## Authors
- Lorena Lopes Dias (UNESP/FEIS)
  - e-mail: lorena.dias@unesp.br
  - ORCID: https://orcid.org/0000-0002-1870-6103
  - Lattes: https://lattes.cnpq.br/0026374599165487
- Camila Gianini Gonsalez-Bueno (UNESP/FEIS)
  - e-mail: camila.gg.bueno@unesp.br
  - Lattes: http://lattes.cnpq.br/8692204806659405
- Douglas Domingues Bueno (UNESP/FEIS)
  - e-mail: douglas.bueno@unesp.br
  - Lattes: http://lattes.cnpq.br/3453163833110618

## How to cite

Dias, L. L., Bueno, D. D. & Gonsalez-Bueno, C. G. (2023), EMI-Experimental-Beam-Temperatura-Variations, GitHub repository, https://github.com/charlespwd/project-title

This dataset was used in this publication:
- Dias, L. L., Bueno, D. D. & Gonsalez-Bueno, C. G. (2023), `SHM based on the Electromechanical Impedance Technique with Temperature Variations: Theoretical and Experimental Approach', 27th International Congress of Mechanical Engineering (COBEM), doi: 10.26678/ABCM.COBEM2023.COB2023-1251

## Funding
São Paulo Research Foundation (FAPESP), Grant Number 2021/12008-2

![fapesp](https://github.com/Lorena591/Pesquisa-Doutorado-Direto/blob/main/fapesp.png)


</div>
