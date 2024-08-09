# Development-of-Novel-Quantum-Algorithms
Womanium Quantum+AI 2024 Projects

**Please review the participation guidelines [here](https://github.com/womanium-quantum/Quantum-AI-2024) before starting the project.**

_**Do NOT delete/ edit the format of this read.me file.**_

_**Include all necessary information only as per the given format.**_

## Project Information:

### Team Size:
  - Maximum team size = 3
  - While individual participation is also welcome, we highly recommend team participation :)

### Eligibility:
  - All nationalities, genders, and age groups are welcome to participate in the projects.
  - All team participants must be enrolled in Womanium Quantum+AI 2024.
  - Everyone is eligible to participate in this project and win Womanium grants.
  - All successful project submissions earn the Womanium Project Certificate.
  - Best participants win Womanium QSL fellowships with Classiq. Please review the eligibility criteria for QSL fellowships in the project description below.

### Project Description:
  - Click [here](https://drive.google.com/file/d/1PGNUShboB4ik_JHZGcIPTh3KYi-aajzp/view?usp=sharing) to view the project description.

## Project Submission:
All information in this section will be considered for project submission and judging.

Ensure your repository is public and submitted by **August 9, 2024, 23:59pm US ET**.

Ensure your repository does not contain any personal or team tokens/access information to access backends. Ensure your repository does not contain any third-party intellectual property (logos, company names, copied literature, or code). Any resources used must be open source or appropriately referenced.

### Team Information:
Team Member 1:
 - Full Name: Weronika Golletz
 - Womanium Program Enrollment ID (see Welcome Email, format- WQ24-xxxxxxxxxxxxxxx): WQ24-BktFZydbEFIvGry


Team Member 2:
 - Full Name: Czcibor Ciostek
 - Womanium Program Enrollment ID (see Welcome Email, format- WQ24-xxxxxxxxxxxxxxx): WQ24-Ur8piOw3PkG3bGc


### Project Solution:
We simulate the 1D transverse-field Ising model as a toy model and discussed the building blocks of the quantum circuit. 
Then extend it to the 2D transverse-field Ising model, perform resource estimation.
As the last step, we take into account the architecture of the hardware and optimize the connections between spins according to the qubit connections in the hardware.
Additionally, we discussed using zero-noise extrapolation as an error mitigation method.
Our work is based on the paper: ["Evidence for the utility of quantum computing before fault tolerance"](https://www.nature.com/articles/s41586-023-06096-3) written by Y. Kim, et. al.

0. [The entire report:](https://github.com/wegolletz/Development-of-Novel-Quantum-Algorithms/blob/main/final-report.ipynb)
   It includes all the codes and notes.
   [Slides](https://github.com/wegolletz/Development-of-Novel-Quantum-Algorithms/blob/main/QWomanium2024-Project-slides.pdf)

The codes listed below are contained in the general report.
Standalone codes:
1. Toy model:
   - [jupyter notebook](https://github.com/wegolletz/Development-of-Novel-Quantum-Algorithms/blob/main/1D-Ising-model.ipynb)
   - [qprog](https://github.com/wegolletz/Development-of-Novel-Quantum-Algorithms/blob/main/1D-Ising-model.qprog)
   - [qmod](https://github.com/wegolletz/Development-of-Novel-Quantum-Algorithms/blob/main/1D-Ising-model.qmod)
2. Enlarged model:
   System 3x3 spins
   - [jupyter notebook](https://github.com/wegolletz/Development-of-Novel-Quantum-Algorithms/blob/main/2D-Ising-model-3x3.ipynb)
   - [qprog](https://github.com/wegolletz/Development-of-Novel-Quantum-Algorithms/blob/main/2D-Ising-model-3x3.qprog)
   - [qmod](https://github.com/wegolletz/Development-of-Novel-Quantum-Algorithms/blob/main/2D-Ising-model-3x3.qmod)
   System 5x5 spins
   - [jupyter notebook](https://github.com/wegolletz/Development-of-Novel-Quantum-Algorithms/blob/main/2D-Ising-model-5x5.ipynb)
   - [qprog](https://github.com/wegolletz/Development-of-Novel-Quantum-Algorithms/blob/main/2D-Ising-model-5x5.qprog)
   - [qmod](https://github.com/wegolletz/Development-of-Novel-Quantum-Algorithms/blob/main/2D-Ising-model-5x5.qmod)
3. Model optimized for the hardware:
   - [jupyter notebook](https://github.com/wegolletz/Development-of-Novel-Quantum-Algorithms/blob/main/2D-Ising-model-5x5-ibm-hardware.ipynb)
   - [qprog](https://github.com/wegolletz/Development-of-Novel-Quantum-Algorithms/blob/main/2D-Ising-model-5x5-ibm-hardware.qprog)
   - [qmod](https://github.com/wegolletz/Development-of-Novel-Quantum-Algorithms/blob/main/2D-Ising-model-5x5-ibm-hardware.qmod)


### Project Presentation Deck:
[Slides](https://github.com/wegolletz/Development-of-Novel-Quantum-Algorithms/blob/main/QWomanium2024-Project-slides.pdf)


See project presentation guidelines [here](https://docs.google.com/document/d/13nWF8AxFAfFYTWEYPT3BpPdYkqtxxSAjmuXj_zcMh-E/edit?usp=sharing)

