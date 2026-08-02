# 555-Blinky-Chaser
I made this through project a hack club stasis guide, this is an led chaser which blinks 10 LEDs in a variable speed sequence

Softwares used: KiCad, Google Chrome.

I have made a simple Blinky Chaser PCB which will repeat 10 LEDs light in a specific sequence using simple resistors, capacitors and the main NE555 Module,
You Can See the Live Demo Video Below or checout the "Live Demo.mp4" linked in this repo. 


# PCB 3D View:
<img width="605" height="672" alt="PCB 3D View" src="https://github.com/user-attachments/assets/053e85d9-bd4e-445a-9739-67993ae3d57a" />

# Soldered Board:
<img width="454" height="613" alt="image" src="https://github.com/user-attachments/assets/1b6d006f-c9cb-4485-b944-6cc63b7a0d07" />


# Bill Of Material:

| Reference | Qty | Value | DNP | Exclude from BOM | Exclude from Board | Footprint | Datasheet |
|----------|----------|----------|----------|----------|----------|----------|----------|
| C1 | 1 | 1μF |  |  |  | Capacitor_THT:CP_Radial_D5.0mm_P2.00mm |  |
| C2 | 1 | 0.01μF |  |  |  | Capacitor_THT:C_Disc_D7.5mm_W2.5mm_P5.00mm |  |
| D1,D2,D3,D4,D5,D6,D7,D8,D9,D10 | 10 | LED |  |  |  | LED_THT:LED_D3.0mm |  |
| J1 | 1 | Conn_01x02_Socket |  |  |  | Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical |  |
| J2 | 1 | Conn_01x01_Socket |  |  |  | Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical |  |
| R1 | 1 | 470 |  |  |  | Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal |  |
| R3 | 1 | 1k |  |  |  | Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal |  |
| RV2 | 1 | 50K |  |  |  | Potentiometer_THT:Potentiometer_Vishay_T93YA_Vertical |  |
| U1 | 1 | NE555P |  |  |  | Package_DIP:DIP-8_W7.62mm | http://www.ti.com/lit/ds/symlink/ne555.pdf |
| U2 | 1 | 4017 |  |  |  | Package_DIP:DIP-16_W7.62mm | http://www.intersil.com/content/dam/Intersil/documents/cd40/cd4017bms-22bms.pdf |


# PCB Live Demo Video:
https://github.com/user-attachments/assets/2a811b2b-bb50-4437-af52-b02a34f7b085
