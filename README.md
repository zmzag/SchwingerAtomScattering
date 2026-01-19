# SchwingerAtomScattering
Various codes which produce different figures of scattering results

FeynmanDiagramsFinal.nb and QuantumScatteringCorrectionsFinal.nb are the main documents which calculate lots of scattering processes and prepare figures
which compare different ones.  FeynmanDiagramsFinal.nb mostly looks at different cross sections vs energy of outgoing particles, whereas 
QuantumScatteringCorrectionsFinal.nb looks more at transmission and reflection depending on the number of excitations in the bound state.

The other scripts produce some specialized figures.  decayratesgkappa.nb calculates the decay rate from the lowest level it is energetically possible
for the bound state to decay from and prepares plots which compare these for different g,\kappa.  transref0p5.nb looks specifically at transmission and 
reflection for various scattering processes with g,\kappa held constant.  CrossSectionAsFnOfInputEnergy.nb calculates the cross section for a meson scattering 
process as a function of the input energy (good for showing that the coefficients of these processes tends to decrease with k, preventing integrals
that show up from being divergent).
