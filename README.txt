Run mosinit.hoc file
Press the init & run button to generate a figure with the membrane potential simulated in two recording sites: axon-initial-segment (AIS) and soma. You may zoom-in to note the firing delay between two compartments. 

--
To check how AIS length modify the spontaneous firing rate, use "L" NEURON parameter by typing: ais.L 
Original reconstruction length is  41.45 microns, try changing it to 10 or 100 microns to see the effect on firing rate. 
From our results, the range of AIS length of 16 dopaminergic neuron reconstructions is from 19 to 58 microns.

--
To check how distance AIS-to-soma modify the spontaneous firing rate, use "L" NEURON parameter by typing: dend[25].L
The section "dend[25]" corresponds to a dendrite between AIS and the soma. 
AIS of dopaminergic neurons origins from a dendrite, consequently AIS distance to the soma is considerably variable (from our results, from 13 to 71 microns.)

--
To better visualize the effect you may select "Keep Lines" mode before changing the AIS length parameter, by pressing and releasing the option "Keep Lines" in the Graph menu with the right mouse button.
