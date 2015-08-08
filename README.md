# REMARC-NanoSim
Development of REMARC set of scripts for translation of DFT data to kinetics and thermodynamics (NanoSim project).

REaction Mechanism And Rate Calculator (REMARC) consists of scripts to calculate rate constants and thermodynamics data and classify corresponding reaction mechanisms from DFT output. It fits rate constants to a convenient functional form and also creates input for running simple kinetics models (coupled rate equations) for further use of the detailed rate constants. The output data can also be used for Kinetic Monte Carlo (KMC) simulations for use and processing the detailed rate constants. An upcoming update will allow for the fit of KMC output rate data to kinetics parameters for overall reactions, i.e., not including intermediate species but only initial reactants and final products.

So far REMARC only processes VASP data, but functionality to process other DFT output will be added later.
