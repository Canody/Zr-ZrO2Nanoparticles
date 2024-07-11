
# Supplementary Data Codes 

**Three-dimensional atomic interface between metal and oxide in Zr-ZrO~2~ nanoparticles**

Yao Zhang^1,5^, Zezhou Li^1,5^, Xing Tong^2,5^, Zhiheng Xie^1^, Siwei Huang^1^, Yue-E Zhang^2,3^, Hai-Bo Ke^2*^, Wei-Hua Wang^2,4^, Jihan Zhou^1*^

*^1^Beijing National Laboratory for Molecular Sciences, Center for Integrated Spectroscopy, College of Chemistry and Molecular Engineering, Peking University; Beijing, 100871, China.*

*^2^Songshan Lake Materials Laboratory, Dongguan 523808, China.*

*^3^College of Physics, Liaoning University, Shenyang 110036, China.*

*^4^Institute of Physics, Chinese Academy of Sciences, Beijing 100190, China.*

*^5^These authors contributed equally to this work.*

*\*Correspondence and requests for materials should be addressed to H.-B. K. (email:*[*kehaibo@sslab.org.cn*](mailto:kehaibo@sslab.org.cn)*) and J. Z. (email:* [*jhzhou@pku.edu.cn*](mailto:jhzhou@pku.edu.cn)).

## Contents

- [Overview](#Overview)
- [System Requirements](#System Requirements)
- [Repository Contents](#Repository Contents)

# Overview

Metal-oxide interfaces with poor coherency have unique properties comparing to the bulk materials and offer broad applications in the fields of heterogeneous catalysis, battery, and electronics. However, current understanding of the three-dimensional (3D) atomic metal-oxide interfaces remains limited because of their inherent structural complexity and limitations of conventional two-dimensional imaging techniques. Here, we determine the 3D atomic structure of metal-oxide interfaces in zirconium-zirconia nanoparticles using atomic-resolution electron tomography. We quantitatively analyze the atomic concentration and the degree of oxidation, and find the coherency and translational symmetry of the interfaces are broken. Moreover, we observe porous structures such as Zr vacancies and nano-pores and investigate their distribution. Our findings provide a clear 3D atomic picture of metal-oxide interface with direct experimental evidence. We anticipate this work could encourage future studies on fundamental problems of oxides such as interfacial structures in semiconductor and atomic motion during oxidation process. 

# System Requirements

All codes have been tested on Windows 10, MATLAB 2022b.

# Repository Contents

### 1. Experiment Data

Folder: [Raw_data](./1_Raw_data)

This folder contains the experimental projections before and after denoising and alignment as well as their corresponding angles for all the Zr-ZrO~2~ nanoparticles.

### 2. Reconstructed 3D Volume

Folder: [Final_reconstruction_volume](./2_Final_reconstruction_volume)

This folder contains the 3D volume of all the Zr-ZrO~2~ nanoparticles reconstructed from experimental projections and angles in [Measured_data](./1_Raw_data+Preprocessing_code). 
The reconstruction codes can be found in [RESIRE_package](https://github.com/AET-MetallicGlass/Supplementary-Data-Codes/tree/master/2_RESIRE_package).

### 3. Experimental Atomic Model

Folder: [Final_atomic_model](./3_Final_atomic_model)

This folder contains the final 3D atomic models of the Zr-ZrO~2~ nanoparticles. 
The tracing codes can be found in [Tracing_codes](https://github.com/AET-MetallicGlass/Supplementary-Data-Codes/tree/master/4_Tracing_and_classification).
