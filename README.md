# DEXSY_pulse_sequence
Diffusion Exchange Spectroscopy (DEXSY) pulse sequence for NMR MOUSE and Kea2 (Magritek, Aachen, Germany) system. Uses the strong static gradient for diffusion encoding. This pulse sequence was first used to collect data for Williamson & Ravin et al., elife, 2019. Please cite accordingly.

This pulse sequence was written and implemented in Prospa 3.22. DEXSY_singleScan_2_pp is the pulse program. DEXSY_singlescan_2.mac is the macro file. Generally, the pulse sequence is called through a backdoor macro. For an example, DEXSY_diagonalSlice_SEdec_interleaveBD.mac is included (note that this file calls additional pulse programs available in prospa.
