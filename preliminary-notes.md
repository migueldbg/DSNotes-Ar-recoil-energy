# Overview of Detection Principles

 * Signature of the WIMP-atomic nuclei interaction: a nuclear recoil with energy in the keV range.
 * In dark matter direct detection experiments, two different backgrounds can be distinguished:
	* one resulting in electron recoils (due to gamma ray interactions) and
	* another resulting in **nuclear (atomic) recoils** in the VOI of the detector. These are the most dangerous, as the resulting signal are indistinguishable from those WIMPs would produce.
 * Due to their high spatial resolution, double-phase noble element detectors are capable of determining particle interaction sites in three dimensions. With this, one can achieve very effective fiducialization, crucial for background reduction.
 * Better discrimation efficiency between eletric and nuclear recoils can be achieved if, in addition to primary scinitillation, the ionization signal is also measured.

The workings of most dual phase noble detectors can be represented by the illustration below.

![Illustration of the operation principle of a dual phase noble detector](https://github.com/migueldbg/DSNotes-Ar-recoil-energy/blob/master/figures/V.%20Chepel%20and%20H.%20Ara%C3%BAjo%20(arxiv:1207.2292)%20-%20FIgure%202.png)

More explicitly, the detector works in the following manner:
 
1. An incoming particle collides with the target atoms in the liquid phase, transfering energy to it by different methods. This first collision results in the primary **scintillation signal** (S1).
1. Due to the energy imparted onto the atoms, ionization may occur. A fraction of the free electrons escape recombination and drift up towards the gas phase due to an external eletric field.
1. Once the electron is at the boundary between phases, a stronger eletric field allows it to transition into the gas phase. Once in the gas phase, a secondary scintillation occurs, giving rise to the tipically named **ionization signal** (S2).

It's important to note that even though both signals are detected in the form of light, S2 is called the *ionization* signal to emphasis the fact its origin is due to the *ionization* process. As a result of this, its size (pulse area) is directly correlated with the number of electrons extracted from the particle track.

These two signals, S1 and S2, can the be used to differentiate between a nuclear recoil and a electron recoil. In general terms, for a give eletric field strength, the fraction of electrons that escape recombination with positive ions is grater for eletron than for nuclear recoils. This phenomena results in the following behaviour for the two signals:
* **Nuclear Recoils:** more energy is drawn into the luminous signal (S1) than into the observable ionization signal (S2).
* **Electron Recoils:** more energy is drawn into the observable ionization signal (S2) than into the luminous signal (S1).

This effect can be clearly seen in the following figure:

![Plots of signals after the elastic scattering of a neutron and from a gamma-ray](https://github.com/migueldbg/DSNotes-Ar-recoil-energy/blob/master/figures/V.%20Chepel%20and%20H.%20Ara%C3%BAjo%20(arxiv:1207.2292)%20-%20Figure%203.png)

As we can see from the image, the ionization signal (S2) is much greater for the gamma-ray, which generates electron recoils. The use of this ocurrence to discriminate between electron and neutron recoils is called **pulse shape discrimination (PSD)** and it's extremely effecient at rejecting electronic interactions above ~10 keV.

To garner useful information from the detector, we must know how to reconstruct the energy trasnferred by a particle to the medium from the signals detected. Doing so is no easy task and requires determing a plethora of different properties of the experiment, such as: relative scintillation efficiency for electrons and nucleon recoils, their dependence on recoil energy and eletric field strength, the probability of an electron so escape recombination as well as the transfer efficiency from liquid to gas. None of these are simple problems, such that we must consider theoretical models to construct and test our predictions. We do so in the main notes.
