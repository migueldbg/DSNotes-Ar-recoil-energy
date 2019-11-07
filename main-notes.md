# Main

## Particle Energy Trasfer

The total energy <img src="https://tex.s2cms.ru/svg/E_0" alt="E_0" /> trasnferred to a medium by an incomming particle can be divided in three portions: ionization, excitation and heat. For an electron, we can write the following equation:

<img src="https://tex.s2cms.ru/svg/E_0%20%3D%20N_iE_i%20%2B%20N_%7Bex%7DE_%7Bex%7D%20%2B%20N_i%20%5Cvarepsilon" alt="E_0 = N_iE_i + N_{ex}E_{ex} + N_i \varepsilon" />

where <img src="https://tex.s2cms.ru/svg/E_%7Bex%7D" alt="E_{ex}" /> and <img src="https://tex.s2cms.ru/svg/E_i" alt="E_i" /> are the mean energies necessary to ionize or excite an atom; <img src="https://tex.s2cms.ru/svg/N_i" alt="N_i" /> and <img src="https://tex.s2cms.ru/svg/N_%7Bex%7D" alt="N_{ex}" /> are the mean number of ionized and excited atoms, respectively; and <img src="https://tex.s2cms.ru/svg/%5Cvarepsilon" alt="\varepsilon" /> is the mean energy of sub-excitation electrons immediately after the last collision to result in either ionization or excitation. Below such energy, electrons will participate only in elastic collisions with atoms, therefore increasing the temperature of the medium.

For nuclear recoils, a considerable portion of the energy is spent in nuclear recoils, which produce neither ionizations or excitations. As such, when considering nuclear recoils, an additional term must be included in the equation of total energy to account for this effect.

In the gas phase, we can relate the energies described above to the atomic ionization potential <img src="https://tex.s2cms.ru/svg/I" alt="I" />:

<img src="https://tex.s2cms.ru/svg/%5Cfrac%7BE_0%7D%7BI%7D%20%3D%20N_%7Bi%7D%5Cfrac%7BE_%7Bi%7D%7D%7BI%7D%20%2B%20N_%7Bex%7D%5Cfrac%7BE_%7Bex%7D%7D%7BI%7D%20%2B%20N_i%5Cfrac%7B%5Cvarepsilon%7D%7BI%7D" alt="\frac{E_0}{I} = N_{i}\frac{E_{i}}{I} + N_{ex}\frac{E_{ex}}{I} + N_i\frac{\varepsilon}{I}" />

where <img src="https://tex.s2cms.ru/svg/I%20%3D%2015.75%5C%20%5Ctext%7BeV%7D" alt="I = 15.75\ \text{eV}" /> for argon. In the case of the liquified argon (LAr), it exhibits a band structure, such that we must replace the ionization potential with the band gap, <img src="https://tex.s2cms.ru/svg/E_g" alt="E_g" /> and we obtain

<<<<<<< HEAD
<img src="https://tex.s2cms.ru/svg/%5Cfrac%7BE_0%7D%7BE_g%7D%20%3D%20N_%7Bi%7D%5Cfrac%7BE_%7Bi%7D%7D%7BE_g%7D%20%2B%20N_%7Bex%7D%5Cfrac%7BE_%7Bex%7D%7D%7BE_g%7D%20%2B%20N_i%5Cfrac%7B%5Cvarepsilon%7D%7BE_g%7D" alt="\frac{E_0}{E_g} = N_{i}\frac{E_{i}}{E_g} + N_{ex}\frac{E_{ex}}{E_g} + N_i\frac{\varepsilon}{E_g}" />
=======
<img src="https://tex.s2cms.ru/svg/%5Cfrac%7BE_0%7D%7BI%7D%20%3D%20N_%7Bi%7D%5Cfrac%7BE_%7Bi%7D%7D%7BI%7D%20%2B%20N_%7Bex%7D%5Cfrac%7BE_%7Bex%7D%7D%7BI%7D%20%2B%20N_i%5Cfrac%7B%5Cvarepsilon%7D%7BI%7D" alt="\frac{E_0}{I} = N_{i}\frac{E_{i}}{I} + N_{ex}\frac{E_{ex}}{I} + N_i\frac{\varepsilon}{I}" /> 
>>>>>>> 43aaff6c42b4ceef0aca524729ce3db0aeff2743

where <img src="https://tex.s2cms.ru/svg/E_g%20%3D%2014.2%5C%20%5Ctext%7BeV%7D" alt="E_g = 14.2\ \text{eV}" /> for solid Ar. The value for the liquid phase is currently unknown. For the sake of comparison, the band gap for solid Xe is <img src="https://tex.s2cms.ru/svg/9.28%5C%20%5Ctext%7BeV%7D" alt="9.28\ \text{eV}" /> and for liquid Xe it's <img src="https://tex.s2cms.ru/svg/9.22%5C%20%5Ctext%7BeV%7D" alt="9.22\ \text{eV}" />.

We can rewrite the equation above using a quantity called the <img src="https://tex.s2cms.ru/svg/W" alt="W" />- value, defined as the mean energy necessary to create an ion-electron pair. For this case, we have that <img src="https://tex.s2cms.ru/svg/W%20%3D%20E_0%2FN_i" alt="W = E_0/N_i" />, such that the equation for total energy becomes:

<img src="https://tex.s2cms.ru/svg/%5Cfrac%7BW%7D%7BE_g%7D%20%3D%20%5Cfrac%7BE_i%7D%7BE_g%7D%20%2B%20%5Cfrac%7BE_%7Bex%7D%7D%7BE_g%7D%20%5Ccdot%20%5Cfrac%7BN_%7Bex%7D%7D%7BN_i%7D%20%2B%20%5Cfrac%7B%5Cvarepsilon%7D%7BE_g%7D.%20" alt="\frac{W}{E_g} = \frac{E_i}{E_g} + \frac{E_{ex}}{E_g} \cdot \frac{N_{ex}}{N_i} + \frac{\varepsilon}{E_g}. " /> 

For the case of liquid argon, considering electron recoils, we have that <img src="https://tex.s2cms.ru/svg/N_%7Bex%7D%2FN_i%20%5Capprox%200.2" alt="N_{ex}/N_i \approx 0.2" />.

It's important to relate the parameters in the equation with what is detected. In a general sense, the scintillation and ionization signal are proportional to <img src="https://tex.s2cms.ru/svg/N_%7Bex%7D" alt="N_{ex}" /> and <img src="https://tex.s2cms.ru/svg/N_i" alt="N_i" />, but not as directly as we may first consider. Due to the presence of recombination, the number of collected electrons at an anode is less than <img src="https://tex.s2cms.ru/svg/N_i" alt="N_i" /> and depends both on the ionizing particle and the applied electric field. To better understand how these quantities translate to the signal we detected, we must delve deeper into the physics of the reactions that result in the photons detected.

### A Qualitative Overview

The basis of a dual-phase noble detector is the combination of the scintillation and ionization signals. We briefly mentioned how these signals are related to some of the physical parameters present when considering the energy imparted by an incoming particle and that they depend on a process called **recombination**. This is simply the process by which ion-electron pairs recombine, forming a neutral molecule and releasing energy in the form of light. The exact overall process involved and how recombination plays a roll in it will be better explained in other notes, but for now, let's develop an initial qualitative sense of how recombination may affect the signals detected.

Let's consider three distinct cases, differing from each other by their **ionization densities**. This is simply the density of ions present in the particle track after it has penetrated the medium and imparted some of its energy into it. Typically, high energy particles will produce tracks with higher ionization densities, as they have more energy available to ionize bound electrons. We have three cases:

* **Zero field, low ionization density:** some electrons escape recombination even with the absence of an electric field due to the scarcity of ions, such that <img src="https://tex.s2cms.ru/svg/N_%7Bph%7D%20%3C%20N_%7Bex%7D%20%2B%20N_i" alt="N_{ph} &lt; N_{ex} + N_i" />.
* **Zero field, medium ionization density:** practically all ion-electron pairs initially recombine and result in recombination luminesce, such that the scintillation yield is at maximum, resulting in <img src="https://tex.s2cms.ru/svg/N_%7Bph%7D%20%5Capprox%20N_%7Bex%7D%20%2B%20N_i" alt="N_{ph} \approx N_{ex} + N_i" />.
* **High ionization density:** this results in a track with a high number of ionized and excited species. In this region, the luminescence signal can be suppressed due to the high probability of collisions between excited species. This process is called **bi-excitonic quenching** and will be further elaborated later on.
