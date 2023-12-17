# Mobile Unmanned Radio Network System
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10392593.svg)](https://doi.org/10.5281/zenodo.10392593)
![Static Badge](https://img.shields.io/badge/License-CC_BY--NC--SA%204.0-green?style=for-the-badge&logo=creativecommons&logoColor=green) ![GitHub contributors](https://img.shields.io/github/contributors/TA-Hermes/MURNS?style=for-the-badge) ![GitHub issues](https://img.shields.io/github/issues/TA-Hermes/MURNS?style=for-the-badge&color=red)


## MURNS is an interconnected network of radio repeaters aimed to decrease costs as much as possible. System is designed to be modular and can be used in various different applications.

---

## Example Uses
- ### Increased Range

	#### When extended is necessary, system can be configured in a line configuration where the repeaters are chained to create a long line of coverage.

>

- ### Wide Area Coverage

	#### When communication in a wide area is needed system can be configured to act as a network where each repeater is connected to two other repeaters creating redundancy in the system. If one repeater fails, users can switch to other repeaters in the area.

---

### You can find specific setup instructions for building the system in docs but for quick reference:

1. You need to get yourself two radios with VFO and VOX.
2. You need to make a cable to connect the audio outputs to one another.
3. You need to configure the frequencies 
	- We recommend using highly different frequencies to avoid unwanted noise if your antennae is too close.
	- We used transmitting offset of *`+007.600MHz`* for UHF and *`+000.600MHz`* for VHF
	- You can set up CTCSS if you use multiple repeaters at similar frequencies.
4. You need to fine tune the volumes for the VOX to work properly. 
	- You can alternatively use a switch to trigger PTT but we have not tried it yet. 
5. After testing the system you are good to go.

---

## Known Issues & Future Improvements

#### If you find any problems with the repeaters please feel free to submit an issue.

- [ ] Two way audio connection causing endless PTT.
<br>
- [ ] Adding transmitters for digital modes and publicly available frequencies.
- [ ] Adding fully autonomous vehicles to adjust positions on the go.
---


<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/TA-Hermes/MURNS">Mobile Unmanned Radio Network System</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/TA-Hermes">Hermes RF Solutions (Deniz Özmalkoç, Nehir Tanış & Egehan Ongun Özkula)</a> is licensed under <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p>










