# A-Bayesian-State-Space-Approach-to-Mapping-Directional-Brain-Networks
Matlab codes for implementing the Bayesian approach to identify directional brain networks.
## Installation

Please download all the functions and add them to search path before using any of them. We also provide a function addContainingDirAndSubDir.m in our toolbox to do so. You may want to put our toolbox in your current working directory and execute addContainingDirAndSubDir() before 
using any other functions.  

## Usage

Detailed guidelines on using these functions can be found in BSBM\_manual.pdf.

- BSBM_ContPnl.m: The control panel of BSBM. It shows how to analyze the simulated data step by step and serves as an example of using our toolbox;
- BSBM_EM.m: The primary function of the EM algorithm, which is used to set starting values and hyperparameter for the MCMC algorithm. Other functions in the subfolder *EM* are the updating steps in the EM algorithm; 
- BSBM_MCMC.m: The primary function of the MCMC algorithm, which is developed for the posterior inference. Other functions in the subfolder *MCMC* are the simulation steps in the MCMC algorithm.


## Data
iEEG data analyzed in the paper were collected from an epileptic patient who received epilepsy diagnosis and treatment at the University of Virginia (UVA) Hospital. The authors analyzed the de-identified iEEG data of the patient. The de-identified data from the UVA hospital are stored on a password protected server, which is managed by UVA Health System IT. The authors are not allowed to share the data with a third party. 

The UVA hospital owns all the iEEG data. The third party can request the data directly from the UVA Health System. For questions regarding the data, please contact the co-author Mark Quigg via email at MSQ6G@hscmail.mcc.virginia.edu .

This toolbox contains the simulated datasets we used in our paper.

- Simulation1.mat: The simulated data presented in Section 3.1 in the paper;
- Simulation2_1.mat: The simulated data presented in Section 3.2, with 2714 time points;
- Simulation2_2.mat: The simulated data presented in Section 3.2, with 1000 time points.

The systems and the error structures we used to generate these simulated datasets are described in Section 3.1 and Section 3.2 of our paper in detail.
