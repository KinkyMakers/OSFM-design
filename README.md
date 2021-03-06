# OSSM - Open Source Sex Machine
OSSM (pronounced like "Awesome") is a user friendly every day sex machine for the people.

This project aims to help people curious about sex machines explore their interest. A second objective is optionally learning how mechanics, electronics, physics and computing are involved in youe sexual pleasure.

### Primary design goals:
- Compact
- Quiet
- Low cost
- 3D printable
- Easily sourced components
- Doesn't look like a giant machine

## Getting Started
There are a few hardware flavours to choose from, we've included user modified versions in case that fits your use case better!

Join our Discord to be part of the discussion and get help with your build. https://discord.gg/MmpT9xE

### Software
We recommend using the ESP32 microcontroller. This code is still arduino IDE compatible but offers many times better performance and a nice internet dashboard you can use!
Control your OSSM at https://app.researchanddesire.com/ossm !

### Eagle PCB
Simple PCB to power an ESP32 (wifi enabled microcontroller) from 24V and breakout the pins for the OSSM control

### Mechanical design
The OSSM use a compact belt design with components that have become widely available due to 3D printing popularity.
It is driven by a Nema23 motor of **your** choosing, although we reccomend small integrated closed loop steppers for their cost to performance ratio.

![Basic overview of the OSSM mechanical design](https://kinkymakers.com/wp-content/uploads/2020/09/F_Machine_Base_-_Sept_21_2020_release_Render_2020-Sep-22_03-14-38AM-000_CustomizedView27283846607-e1600747915630-edited-3.png "OSSM basic render")

### Wiring Notes

This should be a good start for the wiring of your OSSM! However, depending on your hardware mix settings or wiring may be different 

![wiring notes](https://github.com/KinkyMakers/OSSM-hardware/blob/44ab7a5deafa7dd3d66d521bb368959db542c164/Hardware/PCB/wiring%20notes%20800.png)

