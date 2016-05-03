# Xdrip-Lipo-Board
Xdrip on a printed circuit board!

You can order the PCB directly here: https://oshpark.com/shared_projects/IuYnoGB9

# Features:

- The board uses a MAX1811 battery charging ic
- Both Xbridge & Xdrip circuit support, selectable via a switch
- Battery can be soldered directly on the PCB or via a JST-2 connector
- Charging Status LED

# Components:

- 3x 1206 SMD Resitors (150Ω, 10kΩ, 27kΩ)
- 2x 1206 SMD Capacitor 10μf
- 2x micro switch MSK-12C02
- 1x 1206 Red LED (any led should work)
- 1x micro usb socket (ebay id: 121829362799)
- 1x MAX1811 lithium charger IC
- 1x JST-2 connector (optional)
- 1x HM-11 Bluetooth V4.0 Transceiver BLE Module (i got the one from fasttech)
- 1x Polulu Wixel
- 1x LiPo/Li-ion Battery

Attention! The MAX1811 Charger IC is set to 500mah. Only use a battery with more than 500mah.

# PCB Assembly:

Everything is labeled on the PCB. The components are large enough to be soldered by hand, the trickiest for me was the micro usb socket. But if you use a hot air rework station (40$ on ebay) it should be very easy.
![alt text](https://github.com/mzst123/Xdrip-Lipo-Board/blob/master/images/PCB%20Layout.png)


# Schematics:

![Schematics](https://github.com/mzst123/Xdrip-Lipo-Board/blob/master/images/Schematics.png)


# 3D Enclosure:
I made an enclosure, however it has not been tested yet. To further reduce space, the JST-2 connector is not used in this design. In the future I might add one with JST-2 support. The battery compartment should fit an 850mah Lipo Battery.
![Enclosure](https://github.com/mzst123/Xdrip-Lipo-Board/blob/master/Enclosure/3D_render.png)

# Pictures:

![Top View](https://github.com/mzst123/Xdrip-Lipo-Board/blob/master/images/Top.JPG)
![Bottom View](https://github.com/mzst123/Xdrip-Lipo-Board/blob/master/images/Bottom.JPG)
![Side View](https://github.com/mzst123/Xdrip-Lipo-Board/blob/master/images/Side.JPG)
![Screenshot](https://github.com/mzst123/Xdrip-Lipo-Board/blob/master/images/Screenshot.png)