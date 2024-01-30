# ECOMAN - Exploring the COnsequences of Mechanical ANisotropy

ECOMAN is a software package that (i) simulates the development of strain-induced mantle fabrics (LPO+SPO) and (ii) tests the effects of the mechanical (elastic and viscous) anisotropy associated with these fabrics on seismic imaging and mantle convection. It is composed of programs that compute rock fabrics and the related elastic and viscous tensors (ECOMAN-geodynamics), and programs for anisotropic seismological modelling (ECOMAN-seismology-PSI).

ECOMAN builds on the original D-REX software [Kaminski et al., 2004], and includes routines from FSTRACK software [Becker et al., 2006] for synthetic SKS splitting calculation, MATLAB scripts from MTEX Toolbox [Mainprice et al., 2011] to plot singleaggregate textures, thermodynamic databases of the density and isotropic elastic moduli for selected rock compositions at relevant  mantle  P-T  conditions  and  generated with MMA_EoS [Chust et al., 2017].

ECOMAN is supported by the ERC StG 758199 NEWTON

# General information and Installation

ECOMAN-geodynamics include programs for computing rock fabrics and related elastic and viscous tensors, as well as programs for visualization of the tensor properties and generation of input files for seismological synthetics. It is mostly written in Fortran, and where most of the routines are parallelized with shared memory architecture (OpenMP), providing good scalability with increasing number of cores. Notably, D-REX_M is parallelized with a hybrid MPI-OpenMP architecture.

ECOMAN-geodynamics requires installation of the Intel Fortran compilers and HDF5 libraries.

Software compilation: from the directory of each software, execute ./bash_compile

More detailed information and instructions are provided in the user [manual](https://newtonproject.geoscienze.unipd.it/wp-content/uploads/2021/04/ECOMAN1.0_manual.pdf). 

# Software website

https://newtonproject.geoscienze.unipd.it/ecoman/


# Developers

[Manuele Faccenda](mailto:manuele.faccenda@unipd.it)

[Brandon VanderBeek](mailto:brandon.p.vanderbeek@gmail.com)

Albert de Montserrat

Jianfeng Yang
