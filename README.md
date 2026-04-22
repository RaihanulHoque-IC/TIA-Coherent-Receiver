# Fully Differential TIA for Coherent Receiver
Designed a high-speed fully differential TIA for coherent optical receiver. 
## Key Specs
| Performance Parameter | Achieved Value |
| :--- | :--- |
| Photodiode Capacitance | 25 fF |
| Transimpedance Gain | 64 dB $\ohm$ | 
| Bandwidth | 80.93 GHz |
| Input-Referred Noise | 14.37 pA/sqrt (Hz) |
| Group-Delay Variation | 5 ps | 
| THD | 3% @ 10 GHz, with 10 Harmonics | 
| Dynamic Range | 37 dB | 
| Output Voltage (p-p) | 500 mV |
| Power Dissipation | 300 mW | 
| DC Offset Compensation | 5 mA | 

## Circuit Schematic
[Shunt Feedback Topology](SFTIA.png)
[Four Quadrant Multiplier VGA](VGA.png)
[Emitter Follower](EF.png)
[Output Buffer](Buffer.png)
[Testbench Setup](Top_view.png)


## Layout 

<figure>
  <img src="./Thesis_Figures_png/SFB_layout.png" width="500">
  <figcaption><b>Fig:Shunt Feedback Toplogy</b> </figcaption>
</figure>

<figure>
  <img src="./Thesis_Figures_png/VGA Layout.png" width="500">
  <figcaption><b>Fig:VGA</b> </figcaption>
</figure>

<figure>
  <img src="./Thesis_Figures_png/EF Layout.png" width="500">
  <figcaption><b>Fig:Emitter Follower</b> </figcaption>
</figure>

<figure>
  <img src="./Thesis_Figures_png/Overall Layout.png" width="500">
  <figcaption><b>Fig:Overall </b> </figcaption>
</figure>

<figure>
  <img src="./Thesis_Figures_png/RFPro.png" width="500">
</figure>


## Post-Layout Simulation Results

<figure>
  <img src="./Thesis_Figures_png/Gain_comparison.png" width="500">
  <figcaption><b>Fig:</b> Pre- and Post-Layout Overall Frequency Response.</figcaption>
</figure>

<figure>
  <img src="./Thesis_Figures_png/Normalized value.png" width="500">
  <figcaption><b>Fig:</b>Gain Normalized at Maximum Value- Multistage Equalization.</figcaption>
</figure>

<figure>
  <img src="./Thesis_Figures_png/S_parameter.png" width="500">
  <figcaption><b>Fig:</b>|𝑆_11 |, |𝑆_22 |<−10 dB up to 80 GHz. </figcaption>
</figure>

<figure>
  <img src="./Thesis_Figures_png/GDV.png" width="500">
  <figcaption><b> Fig:</b>5 ps at aroung 80 GHz.</figcaption>
</figure>

<figure>
  <img src="./Thesis_Figures_png/THD.png" width="500">
  <figcaption><b> Fig:</b>THD=3% at 10 GHz and 10 Harmonics, 500mV p-p Output voltage</figcaption>
</figure>

<figure>
  <img src="./Thesis_Figures_png/AIRN.png" width="500">
  <figcaption><b> Fig:</b>Avereage Input Referred Noise=14 pA/sqrt(Hz) upto 100 GHz.</figcaption>
</figure>

<figure>
  <img src="./Thesis_Figures_png/DR.png" width="500">
  <figcaption><b> Fig:</b>37 dB dynamic range varying control voltage from 1mV to 150 mV.</figcaption>
</figure>

<figure>
  <img src="./Thesis_Figures_png/NRZ.png" width="500">
  <figcaption><b> Fig:</b>NRZ</figcaption>
</figure>

<figure>
  <img src="./Thesis_Figures_png/PAM4.png" width="500">
  <figcaption><b> Fig:</b>PAM4</figcaption>
</figure>

<figure>
  <img src="./Thesis_Figures_png/IDCC results.png" width="500">
  <figcaption><b> Fig:</b>Input DC Current Compensation (Low cur off frequency =250 KHz)</figcaption>
</figure>

<figure>
  <img src="./Thesis_Figures_png/Corner Sim.png" width="500">
  <figcaption><b> Fig:</b>Corner Simulation</figcaption>
</figure>


## 3. Documentation
* [Full Thesis Report (PDF)](./Thesis_Report.pdf)

## 4. References
* Säckinger, Eduard. Broadband circuits for optical fiber communication. John Wiley & Sons, 2005.
* Dziallas, Giannino, Adel Fatemi, Andrea Malignaggi, and Gerhard Kahmen. "A 97-GHz 66-dBΩ SiGe BiCMOS low-noise transimpedance amplifier for optical receivers." IEEE Microwave and Wireless Components Letters 31, no. 12 (2021): 1295-1298.
* Ahmed, Mostafa G., Tam N. Huynh, Christopher Williams, Yong Wang, Pavan Kumar Hanumolu, and Alexander Rylyakov. "34-GBd linear transimpedance amplifier for 200-Gb/s DP-16-QAM optical coherent receivers." IEEE Journal of solid-state circuits 54, no. 3 (2018): 834-844.
* Herbel, Thiemo, Mohsin Tarar, Frank Vater, and Dietmar Kissinger. "A 130-GHz bandwidth 61-dBOhm variable-gain differential linear TIA in a 130-nm SiGe: C BiCMOS technology." In 2024 IEEE BiCMOS and Compound Semiconductor Integrated Circuits and Technology Symposium (BCICTS), pp. 130-133. IEEE, 2024.





