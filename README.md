# Neuron transfer impedance (_Z_<sub>c</sub>)

Calculation of transfer impedance (_Z_<sub>c</sub>) was done as previously descrirbed (Jaffe, 1999).
The following formula was used to compute average _Z_<sub>c</sub>, 

<img src="https://user-images.githubusercontent.com/42112716/117706410-8acc7800-b1cd-11eb-9ccd-e1a674a2b021.png" width="250"/>

Where _V_<sub>soma</sub> is the peak voltage at the soma _I_<sub>syn</sub> is peak current at the location of the synapse, _D_<sub>syn</sub> is synaptic density per μm<sup>-1</sup> and (_d_<sub>seg</sub> x π x _L_<sub>seg</sub>) is the segment cylinder surface μm<sup>-1</sup>. To generate synaptic current, we attached a bi-exponential conductance-based synapse model to the spine head with rise time τ<sub>1</sub> of 0.2 ms, a decay of τ<sub>2</sub> of 3 ms, a peak conductance density of 0.291 nS and a reversal potential of 0 mV to approximate the experimentally determined current amplitude and time course corresponding to unitary EPSP amplitude in the soma in the range of 0.2 - 0.8 mV (Popovic, 2015). Average density of excitatory synapse (D, synapse μm<sup>-2</sup>) was adjusted to 1 synapse 1 synapse μm<sup>-2</sup>, to match the data from high-resolution confocal microscopy measurement (rodent )
