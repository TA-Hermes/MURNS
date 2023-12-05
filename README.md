# Mobile Unmanned Radio Network System

![Static Badge](https://img.shields.io/badge/License-CC_BY--NC--SA%204.0-green?style=for-the-badge&logo=creativecommons&logoColor=green)
![GitHub contributors](https://img.shields.io/github/contributors/TA-Hermes/MURNS?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/TA-Hermes/MURNS?style=for-the-badge&color=red)


### MURNS is an interconnected network of radio repeaters capable of linking multiple repeaters together in order to create a wide area of coverage.

MURNS is currently for amateur radio only. Though you can use it with other frequencies however make sure to use the frequencies in respect with local regulations **DO NOT USE ANY FREQUENCY YOU ARE NOT ALLOWED ON**.

# Example Use

### The most basic example would be using the system standalone as a repater. Just set up the radio with an offset. Usually an offset of **-007.600 MHz** for UHF and **-000.700 MHz** for VHF. Optionally set up CTCSS encode on transmit for the radios. When setting the repeater up don' t forget that TX on repeater is RX on user, RX on repeater is TX on user.

[PHOTO FOR REPEATER]

### For this you only need 1 cable for sending the data to TXing radio but you cannot link them. 


### Optionally you can use 2 or more tepeaters we recommend using directional antennae for linking them up. You need to set up one radio as "link", and the other as the "gate".

### 1. Set up as usual using 2 cables.
### 2. Set up the user' s radio normally
### 3. For the "gate" radio put the ofsetted frequency (and tone if used) for recieving frequency. 
### 4. Put an offset for transmit making sure the ofsetted frequency is the recieving frequency on user

### This way you can link multiple repeaters in oreder to maintain connection in a wide area. 

## Known Issues

 Cables causing radio to transmit endlessly: Currently there are no fixes but connectin only one 3.5 and 2.5 pair does counterract. 

Volume: You need trial and error to find this. Custom radio card will help this. 

## Build

### You need to build a repeater to start, we recommend using a Duplex Repeater it is easier to make and more flexible to implement. 













