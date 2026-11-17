# PanoLogic G2
# Marvell 88E1119 10/100/1000BASE-T PHY with GMII - "Alaska Gigabit Products"
From a Marvell Product comparison document
Some comparison to similar models, primarily Marvell 88E1111 but others where appropriate
* 1 Port 10/100/1000BASE-T (88E1111)
* MII (88E1111)
* GMII (88E1111)
* Internal Regulator with PNP (88E1116 & 88E1118)
* Integrated Passives (88E1116 & 88E1118)
* Virtual Cable Tester (88E1111)
* Programmable LED (88E1111)
* JTAG (88E1111)
* 125 MHz CLK OUT (88E1111)
* I-Temp (88E1111)
* RoHS 6/6, Green* (88E1310, 88E1310S, 88E1318)
* 72-QFN (Other similar chips are 48 and 64 QFN, this is the only one with 72 pins, The 88E1111 has 96, 117 and 128 pins)
88E1119 - DOESN"T have the following 
* SGMII (Line) - Serial Gigabit
* SFP - Optical 
* RGMII - Reduced Gigabit Interface
* TBI - 10 bit Interface
* RTBI - 4/5 bit Interface
* SGMII (MAC) - Serial Gigabit
* SerDes
* QSGMII - Quad Serial Gigabit
* EEE (Energy Efficient Ethernet)

## Linux commands

Info comes from [here](https://www.cyberciti.biz/faq/linux-change-the-speed-and-duplex-settings-of-an-ethernet-card/)

Current port settings:

```
ethtool eth0
```

Change port settings:

```
sudo ethtool -s eth0 speed 1000 duplex full
```

