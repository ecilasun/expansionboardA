# expansionboardA

This repository contains plans for an expansion board built for QMTECH A7 200T core board.
It requires KiCAD 7 and required libraries (models/symbols) are included.


# Bill of materials

```
R1: 0603_1608Metric 330 Ohm
R2: 0603_1608Metric 10 KOhm
R10,R7,R6,R9,R4,R3,R5: 0603_1608Metric 33 Ohm

C2: 0603_1608Metric 0.1uf
C3: 0603_1608Metric 18 pf
C4: 0603_1608Metric 6 pf
C5,C1: 0603_1608Metric 1 uf ceramic
C6,C7: 0805_2012Metric 10 uf

D4,D6,D5,D2,D1,D3: 1206_3216Metric LED (blue)

U1: MAX3420EECJ - USB to serial
U3: AMS1117-3.3 - Voltage regulator
U5: MCP3008T-I/SL - 10 bit ADC
U6: TLV320AIC23BIPW - Audio

Y1: Crystal 12MHz

AU1, AU2: SJ-3523-SMT-TR - Stereo jack 3.5mm
CRD1: DM3AT-SF-PEJM5 - Micro SD card connector
J2: Molex 676430910 - USB A connector (host)
P1: USB4085-GF-A - USB C connector
J3: HD02-19-M-MSMT-TR - HDMI connector
```