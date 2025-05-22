# Ground RX Station For NOAA APT
---
### ⌛Total Hours Spent: 3 Hours

---
### What am I making??
I'm making a ground station for receiving images from NOAA satellites. This station consists of a QFH antenna mounted onto an extendable motorized platform which would be capable of extending out the antenna to about 1-2 meters. Additionally the platform would be mounted onto my balcony railing securely, and the overall system would be weatherproof (can tolerate wind and rain hopefully). The antenna would then be connected to a DIY FM notch filter and then to a DIY Bandpass filter and then to an LNA (still deciding if I want to buy or DIY this). All of this would be powered off a LiPo battery instead of a wall outlet to reduce EMI and noise, the LiPo battery would be solar charged and fully self sufficient. All of this would then be routed through my window using a coax window pass through (will most likely buy this instead of DIY) and then finally into my RTL-SDR.

Example of a NOAA APT image (from reddit)- ![image](https://hc-cdn.hel1.your-objectstorage.com/s/v3/aa65fc94f0b5efb58632960a4cb57a26acd8e181_2wsb57rprzv51.webp)



## May 17th: Preliminary research and rough BOM

Today I researched about what are the best ways to receive images from NOAA satellites and the tl;dr is that a Quadrifilar Helix Antenna is the best overall antenna and it needs to have a clear view of the sky.

Now since I live in an apartment, having an antenna that has a clear view of the sky is a difficult thing. So the only option I have is to mount an antenna on my balcony and find a way to extend it outwards to get a less obstructed view of the sky. Now luckily for me if I find a way to extend it outwards I would have a pretty clear view of the N->S and S->N passes.

My current idea for extending the antenna outwards is to mount it onto some aluminum extrusions and find a way to move them back and forth like a telescopic arm.

Here is a visual plan of what I have in mind so far
![image](https://hc-cdn.hel1.your-objectstorage.com/s/v3/069b2ef70a59f52af5598aca2623fec107da01ee_1000013856.jpg)

Also made a rough lil BOM

Copper wire (18-16awg)(30meter) - $30
PVC Pipe - $30
Aluminum Extrusions 4pcs 1200mm - $80
Nema 17 - $20
V-Wheels Gantry Plate - $20
Custom PCBs - $20 (bare pcbs)
PCB componenets - $40
Coax cable - $ 30
SMA connectors - $15
Coax pass through - $20
LiPo Battery 1500 Mah - $15
Solar Charge Module - $10
Solar Panel - $30
Power componenets & regulators - $20
Misc (screws and stuff) - $20Total =  $400 CAD = $286 USD


### Time Spent: 3 Hours