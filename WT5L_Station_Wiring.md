# WT5L Station Wiring


### Transceiver (Kenwood TS-570D):
1. DC 13.8 V (Power) -> To Astron RS-35M Power Supply output
2. ANT 1 (Coax Patch Cable) -> To Ameritron ALS-600 'RF IN' connector
3. ANT 2 (Coax Patch Cable) -> To Dummy Load
4. PADDLE -> To Bencher Iambic Paddle
5. KEY (1/8 inch stereo mini plug patch cord) -> To RIGblaster Pro 'CW OUT' connector
6. COM -> To Dual USB-Serial Adapter
7. ACC 2 (Custom cable) -> To RIGblaster Pro 'FSK OUT' connector
8. REMOTE (Custom cable) -> To Ameritron ALS-600 'RELAY' and 'ALC' RCA connectors

***

### Antenna Tuner (Palstar AT1KM):
1. RF IN (Coax Patch Cable) -> To Ameritron ALS-600 'RF OUT' connector
2. COAX 1 (TX/RX Coax - Large Diameter) -> To Antenna

***

### Linear Amplifier (Ameritron ALS-600):
1. RF OUT (Coax Patch Cable) -> To Palstar AT1KM 'RF IN' connector
2. RF IN (Coax Patch Cable) -> To Kenwood TS-570D 'ANT 1' connector 
3. RELAY (RCA connector) -> To Kenwood TS-570D 'REMOTE' connector
4. ALC (RCA connector) -> To Kenwood TS-570D 'REMOTE' connector
5. 50VDC INPUT FROM ALS-600PS -> To Ameritron ALS-600 Power Supply

### Linear Amplifier Power Supply (Ameritron ALS-600PS):
1. LINE AC -> To 230 VAC outlet
2. 50 VDC OUTPUT -> to Ameritron ALS-600 '50VDC INPUT FROM ALS-600PS'

***

### Linear Power Supply (Astron RS-35M):
1. Power -> To 115 VAC outlet
2. + Terminal (Top) / - Terminal (Bottom) -> To Kenwood TS-570D 'DC 13.8V DC' connector

***

### Computer Interface (West Mountain Radio RIGblaster Pro):
1. POWER 12VDC -> To 115 VAC outlet
2. SERIAL/COM RS-232 INPUT B -> No Connection
3. SERIAL/COM RS-232 INPUT A -> To Dual USB-Serial Adapter
4. CTL IN/OUT -> No Connection
5. CW OUT (1/8 inch stereo mini plug patch cord) -> To Kenwood TS-570D 'KEY' connector
6. FSK OUT (1/8 inch stereo mini plug patch cord) -> To Kenwood TS-570D 'ACC 2' connector 
7. MIC OUT -> No Connection
8. SPKR OUT (1/8 inch stereo mini plug patch cord) -> To External Computer Speakers
9. LINE IN (1/8 inch stereo mini plug patch cord) -> To Computer AUDIO OUT (GREEN) connector
10. LINE OUT (1/8 inch stereo mini plug patch cord) -> To Computer MIC IN (PINK) connector
11. AUDIO IN (1/8 inch stero mini plug to 1/4 mono plug patch cable) -> To Kenwood TS-570D front panel 'PHONES' jack
12. SPKER OUT -> Not Connected
13. PTT OUT -> Not Connected
14. PTT IN -> Not Connected
15. MIC OUT -> To Kenwood TS-570D front panel 'MIC' jack
16. MICROPHONE CONNECTOR (Front Panel) -> To hand-held microphone
17. HEADPHONE (Front Panel) -> To headphones

***

### Dual Serial-to-USB Adapter:
1. USB 1 -> To Kenwood TS-570D 'COM' connector
2. USB 2 -> To RIGblaster Pro 'SERIAL/COM RS232 INPUT A'
3. USB OUT -> To computer USB input