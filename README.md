
# EMI-Experimental-Temperature-Variations

 <div align="justify">EMI-Experimental-Temperature-Variations contains a set of data and information relating to researches involving Structural Integrity Monitoring (SHM) via Electromechanical Impedance (EMI) technique. The studies were carried out on a 6063-T5 aluminum alloy beam with PSI-5H4E piezoelectrics transducers (PTZs) from *Piezo Systems*$$^\circledR$$ attached to its surface. This benchmark presents the experimental methods used for the EMI technique. The experiments consist of collecting EMI signals for undamaged structural conditions under temperature variations considering the use of PZTs in symmetrical and asymmetrical configuration, since the nature of the waves - longitudinal or flexural - generated in a structure by piezoelectric transducers depends directly on their physical arrangement. Symmetrical PZTs generate longitudinal and flexural waves separately, while asymmetrical PZTs produce both types of waves simultaneously. In addition, EMI signals were also measured for the PZT in the free condition, i.e. decoupled from the structure. The data set is valuable for validating SHM algorithms at different temperatures.

![VigaPZT](https://github.com/Lorena591/EMI-Experimental-Temperature-Variations/blob/main/PZTDesacoplado.pdf)

## 1. Data Access

Data are available for non-commercial research under the following terms: (i) the GMSINT Laboratory and UNESP/Ilha Solteira should be recognized as the source of the data; (ii) publications should include references pertinent to the publications of GMSINT members; (iii) it is necessary to cite this benchmark.

To learn more about the reserach group GMSINT: https://bit.ly/3RSReVl

To download the dataset (experimental signals) of the benchmark, please fill the form: https://bit.ly/3VINLtA

## 2. Experiment to collect EMI signals

This section presents the series of experimental tests conducted. The methodology for measuring the electromechanical impedance (EMI) signals is outlined in three stages: first, for a beam coupled with a PZT in an asymmetric configuration; then, in a symmetric configuration, with two piezoelectric elements attached to opposite sides of the beam; and finally, for EMI signals of an uncoupled PZT.

### 2.1. Asymmetrical PZT

The experiment consisted of collecting electromechanical impedance signals from a 6063-T5 aluminum alloy beam containing a PSI-5H4E piezoelectric transducer from *Piezo Systems*$$^\circledR$$ attached to its surface in the asymmetrical configuration, as shown in the digure below.

![https://github.com/Lorena591/Pesquisa-Doutorado-Direto/blob/main/VigaPZT.jpg](https://github.com/Lorena591/Pesquisa-Doutorado-Direto/blob/main/VigaPZT.JPG)

The figure below shows a schematic of the experimental setup utilized. It was used a National Instruments board, model NI-USB 6211 (16 bits); a computer containing the software with the impedance analyzer developed by Baptista and Filho (2009) in LabVIEW environment; and a protoboard containing a resistance of 10 *k*Ω, which acts as an auxiliary circuit whose function is to limit the voltage in the piezoelectric transducer, thus avoiding potential damage to this device. The data acquisition (DAQ) board is responsible for capturing the response signal and, simultaneously, transmitting the excitation signal to the piezoelectric transducer. The excitation signal is generated by the impedance analyzer, which also calculates the electromechanical impedance based on the response signal captured by the DAQ. This software includes procedures for adjusting the measurement system and the excitation signal according to the user's wishes. 

![setup](https://github.com/Lorena591/Pesquisa-Doutorado-Direto/blob/main/Setup.JPG)

The aluminum beam was placed inside a thermal chamber from the brand *Thermotron*$$^\circledR$$ *S-Series* to simulate ambient temperature variations, showed in the figure below(a). This beam was positioned on a foam layer to simulated a free-free boundary condition, as shown in the figure below(b). Geometric and material properties of the piezoelectric transducer and the beam at 24°C are presented in the tables below.

![camara_viga](https://github.com/Lorena591/Pesquisa-Doutorado-Direto/blob/main/camara_viga.JPG)

Table 1 - Geometric and material properties of the PSI-5H4E piezoelectric transducer at 24°C.
| Property | Symbol | Value |                                                                 
| -- | -- | -- |                                                                                                   
|Length | $$L_p$$ | 13 mm|                     
|Width |$$b_p$$ |12 mm|
|Thickness |$$h_p$$ |0.2667 mm|
|Compliance |$${S}_{11}^E$$|11 1.6129×10−11 Pa−1|
|Density |$$\rho_p$$ |7800 kg/m3|
|Piezoelectric constant |$$d_{31}$$ |-327.18×10−12 m/V|
|Dielectric constant |$$\varepsilon_{33}^T$$ |3.24783.3630×10−8 F/m|
|Distance from the first PZT’s end to the origin| $$x_1$$ |81 mm|
|Distance from the second PZT’s end to the origin| $$x_2$$| $$x_1+L_p = 94 mm$$   |

Table 2 - Geometric and material properties of the 6063-T5 aluminum alloy beam at 24°C.
| Property | Symbol | Value |                                                                 
| -- | -- | -- |           
|Length | $$L_b$$| 498 mm |
|Width | $$b_b$$ | 12 mm |
|Thickness | $$h_b$$ | 3 mm |
|Young's modulus | $$E_b$$ | 69 GPa|
|Density | $$rho_b$$| 2680 kg/m3|

The signals were measured in a temperature range from 24°C to 70°C, which correspond to a large portion of the structures in operation. It was utilized a step of 5°C for the non-damage condition. In order to excite the structure, it was applied a sinusoidal frequency sweep with an amplitude of ±1 V in a frequency range of 1 Hz to 100 *k*Hz, with a step size of 1 Hz. The signals were gauged only during heating. Thirty signals were collected for each temperature and a sampling rate of 250 *k*S/s was employed.

### 2.2. Symmetrical PZT

To obtain the electromechanical impedance signals corresponding to the different structural dynamics (longitudinal and flexural), two PSI-5H4E piezoelectric transducers were symmetrically coupled to the 6063-T5 aluminum alloy beam, as shown in the figure below. The experimental setup used for data acquisition was identical to that one used in the Subsection 2.1, except that in this case the object of study is a beam with two piezoelectric transducers coupled instead of only one (asymmetric PZT). The geometric properties of the PZTs and the beam are shown in Tabs. 3 and 4, respectively. As the same piezoelectric ceramics and beam used in the previous analysis (detailed in Subsection 2.1 and outlined in Tabs. 1 and 2) were applied here, the material properties of this device and the beam have been excluded from Tabs. 3 and 4 to avoid redundancy.

Table 3 - Geometric properties of symmetrical PSI-5H4E PZTs.
| Property | Symbol | Value |                                                                 
| -- | -- | -- |                                                                                                   
|Length | $$L_p$$ | 12 mm|                     
|Width |$$b_p$$ |12 mm|
|Thickness |$$h_p$$ |0.2667 mm|
|Distance from the first PZT’s end to the origin| $$x_1$$ |81 mm|
|Distance from the second PZT’s end to the origin| $$x_2$$| $$x_1+L_p = 93 mm$$   |

Table 4 - Geometric properties of the 6063-T5 aluminum alloy beam cont.
| Property | Symbol | Value |                                                                 
| -- | -- | -- |           
|Length | $$L_b$$| 499 mm |
|Width | $$b_b$$ | 12 mm |
|Thickness | $$h_b$$ | 3 mm |

The connection arrangement between the piezoelectric transducers for generating longitudinal and flexural waves is shown in the figure below. This configuration is essential for the proper excitation of the different dynamics, allowing the PZTs to operate in a complementary manner and promote the appropriate stresses, be they axial forces (longitudinal dynamics) or bending moments (flexural dynamics). 

The electromechanical impedance signals were acquired over a temperature range of 24°C to 65°C, with increments of 10°C. The beam, inserted in a thermal chamber (see figure below), was excited by a frequency sweep sinusoidal signal (*chirp*) with an amplitude of ±1 V, covering a range from 1 Hz to 100 *k*Hz, with a step of 1 Hz. In order to guarantee the reliability of the results, 10 sets of data were collected for each temperature, exclusively during the heating of the beam. The sampling rate used was 250 *k*S/s.


### 2.3. Free PZT

The experimental tests consisted of collecting electromechanical impedance signals from the PSI-5H4E piezoelectric transducer, from *Piezo Systems*$$^\circledR$$, shown in the figure below. The geometric characteristics of this transducer are detailed in Tab. 5. These properties are identical to those used in the experimental tests of the coupled system (beam and asymmetrical PZT), guaranteeing repeatability of the test conditions.

Table 5 - Geometric properties of the free PSI-5H4E PZT.
| Property | Symbol | Value |                                                                 
| -- | -- | -- |                                                                                                   
|Length | $$L_p$$ | 13 mm|                     
|Width |$$b_p$$ |12 mm|
|Thickness |$$h_p$$ |0.2667 mm|

The experimental setup employed for data acquisition was identical to that used in Subsection 2.1, with the exception that, in this case, the object of study is a free piezoelectric transducer. Electromechanical impedance signals were collected at temperatures of 24°C, 45°C and 70°C. This was achieved using a *chirp* sinusoidal sweep with an amplitude of ±1 V, spanning a frequency range from 1 Hz to 100 *k*Hz, in increments of 1 Hz. The sampling rate was 250 *k*S/s, and 10 sets of signals were obtained for each temperature. The measurements were taken exclusively during the heating process of the piezoelectric element. It should be noted that the high fragility of the PZT, combined with the vibrations of the thermal chamber itself and, above all, the circulating air currents within, caused disturbances to the piezoelectric transducer, which compromised the EMI and led to negative interference in the signals, such as increased noise.

#### References
Baptista, F.G. and Filho, J.V., 2009. “A new impedance measurement system for pzt based structural health monitoring”. IEEE Transaction on Instrumentation and Measurement, Vol. 58, No. 10, pp. 3602–3608

## 3. Authors
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

## 4. How to cite

Cite Github repository:

 - Dias, L. L., Gonsalez-Bueno, C. G. & Bueno, D. D. (2023), EMI-Experimental-Beam-Temperatura-Variations, GitHub Repository, https://github.com/Lorena591/EMI-Experimental-Beam-Temperature-Variations

If you are using a LaTeX Editor, you can cite this repository using the BibTeX citation:

```
@misc{GithubDias2023,
	author         = {Dias, L. L. and Gonsalez-Bueno. C. G. and Bueno, D. D.},
	title          = {EMI-Experimental-Beam-Temperatura-Variations},
	year           = {2023},
	note           = {Github Repository, \url{https://github.com/Lorena591/EMI-Experimental-Beam-Temperature-Variations}}
}
```

The dataset, pertaining to the EMI collected from a beam with an asymmetrically attached PZT on its surface, was utilized in this publication:

- Dias, L. L., Bueno, D. D. & Gonsalez-Bueno, C. G. (2023), `SHM based on the Electromechanical Impedance Technique with Temperature Variations: Theoretical and Experimental Approach', _in_ 27th International Congress of Mechanical Engineering (COBEM), doi: 10.26678/ABCM.COBEM2023.COB2023-1251

If you are using a LaTeX Editor, you can cite this article using the BibTeX citation:

```
@inproceedings{Dias2023,
  author         = {Dias, L. L. and Bueno, D. D. and Gonsalez-Bueno, C. G.},
  title          = {{SHM} based on the Electromechanical Impedance Technique with Temperature Variations: theoretical and experimental approach},
  booktitle      = {27th International Congress of Mechanical Engineering (COBEM)},
  year           = {2023},
  adress         = {Florianópolis, SC, Brazil},
  note           = {doi: 10.26678/ABCM.COBEM2023.COB2023-1251},
 }
```

## 5. Funding
São Paulo Research Foundation (FAPESP), Grant Number 2021/12008-2.

![fapesp](https://github.com/Lorena591/Pesquisa-Doutorado-Direto/blob/main/fapesp.png)


</div>
