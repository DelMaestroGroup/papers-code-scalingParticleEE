[![Paper](https://img.shields.io/badge/paper-arXiv%3A2302.09093-B31B1B.svg)](https://arxiv.org/abs/2302.09093)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7644079.svg)](https://doi.org/10.5281/zenodo.7644078)

# A Scaling Function for the Particle Entanglement of Fermions

Harini Radhakrishnan, Matthias Thamm, Hatem Barghathi, Bernd Rosenow, and Adrian Del Maestro

[arXiv:2302.09093](https://arxiv.org/abs/2302.09093)

### Abstract
Entanglement entropy under a particle bipartition provides complementary information to mode entanglement as it is sensitive to interactions and particle statistics at leading order and does not depend on any externally imposed length scale.  In this paper, we investigate the particle entanglement entropy in a system of $N$ interacting lattice spinless fermions in one spatial dimension by combining bosonization techniques with exact and approximate numerical methods. We introduce a general scaling form for the fermionic particle entanglement entropy captured by a shape function that enters as a extensive interaction induced correction to a known free fermion result. A general asymptotic expansion in the total number of particles demonstrates that its form is robust for different values of the R{\'e}nyi index and highlights how quantum correlations are encoded in the $n$ particle density matrix of a pure many-body quantum state. 

### Description
This repository includes links, code, scripts, and data to to perform data analysis and the figures for the corresponding paper on studying the scaling of the n-particle entanglement in the J-V model describing interacting, spinless fermions in 1D.

### Requirements
The data in this project was generated via exact diagonalization and DMRG.  Everything included in the [data](https://github.com/DelMaestroGroup/papers-code-scalingParticleEE/tree/main/data) directory was generated via:

* [ED code](https://github.com/DelMaestroGroup/tVDiagonalizeParticleEntanglementEntropyEquilibrium)
* [DMRG code](https://github.com/DelMaestroGroup/tVparticleEEdmrg_julia)

To run the code needed to generate the analysis and plots you may need to install 
* [dgutils](https://github.com/delmaestrogroup/dgutils)

You can install a minimal environment to run this code via: `pip install -r requirements.txt` 


### Support
The creation of these materials was supported in part by the National Science Foundation under Award No. DMR-1553991.

[<img width="100px" src="https://www.nsf.gov/images/logos/NSF_4-Color_bitmap_Logo.png">](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1553991)

### Figures

#### Figure 01: Visual of n-particle entanglement entropy for N=8 interacting fermions on a 1D lattice
<img src="https://github.com/DelMaestroGroup/papers-code-scalingParticleEE/blob/main/figures/Fig01_particleentdiagram.svg" width="400px">

#### Figure 02: Phase diagram for interacting fermions in one dimension
<img src="https://github.com/DelMaestroGroup/papers-code-scalingParticleEE/blob/main/figures/Fig02_spinlessfermionphasediagram.svg" width="400px">

#### Figure 03: Dependence of the parameter g on interaction strength
<img src="https://github.com/DelMaestroGroup/papers-code-scalingParticleEE/blob/main/figures/Fig03_gvalues.svg" width="400px">

#### Figure 04: Comparison of the exponentiated negative corrections to the 1-particle entanglement entropy of Rényi index 2 for different interaction strengths
<img src="https://github.com/DelMaestroGroup/papers-code-scalingParticleEE/blob/main/figures/Fig04_alpha2diffV.svg" width="400px">

#### Figure 05: Comparison of the exponentiated negative corrections to the 1-particle entanglement entropy of Rényi index 1 for different interaction strengths
<img src="https://github.com/DelMaestroGroup/papers-code-scalingParticleEE/blob/main/figures/Fig05_alpha1diffV.svg" width="400px">


#### Figure 06: Comparison of the exponentiated negative corrections to the 1-particle entanglement entropy for different Rényi indices
<img src="https://github.com/DelMaestroGroup/papers-code-scalingParticleEE/blob/main/figures/Fig06_n1diffalphas.svg" width="400px">


#### Figure 07: Constant in fitting form of the exponentiated negative corrections to the 1-particle entanglement entropy as a function of the parameter g and the Rényi index
<img src="https://github.com/DelMaestroGroup/papers-code-scalingParticleEE/blob/main/figures/Fig07_constants.svg" width="400px">

#### Figure 08: Comparison of the exponentiated negative corrections to the n-particle entanglement entropy for different values of n 
<img src="https://github.com/DelMaestroGroup/papers-code-scalingParticleEE/blob/main/figures/Fig08_diffn.svg" width="400px">

#### Figure 09: Scaling of constant term in the correction n-particle entanglement entropy with n
<img src="https://github.com/DelMaestroGroup/papers-code-scalingParticleEE/blob/main/figures/Fig09_linearn.svg" width="400px">

#### Figure 10: Scaling of the correction to the n-particle entanglement entropy with N at fixed n/N
<img src="https://github.com/DelMaestroGroup/papers-code-scalingParticleEE/blob/main/figures/Fig10_fixedratiosv1.75double.svg" width="400px">

#### Figure 11: Fitting of the correction to the n-particle entanglement entropy divided by N as a function of n/N for all data
<img src="https://github.com/DelMaestroGroup/papers-code-scalingParticleEE/blob/main/figures/Fig11_fulldataset%2B1.75.svg" width="400px">

#### Figure 12: Interpolated surface of Phi_0 as a function of n/N and v/J
<img src="https://github.com/DelMaestroGroup/papers-code-scalingParticleEE/blob/main/figures/Fig12_interpolatedphi.svg" width="400px">

This figure is released under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) and can be freely copied, redistributed and remixed.

