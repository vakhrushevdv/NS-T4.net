# Scheme components 

U1:  GD32F107VCT6 ([datasheet](https://www.gigadevice.com/product/mcu/arm-cortex-m3/gd32f107vct6.html)) 
U2:  EL357N ([datasheet](https://en.everlight.com/wp-content/plugins/ItemRelationship/product_files/pdf/EL357N-G.pdf))
U3:  RTL8201CP ([datasheet](http://realtek.info/pdf/rtl8201cp.pdf))
U4:  HS9016 ([datasheet](http://file2.dzsc.com/product/17/10/23/1126204_161055900.pdf))
U5:  MP1484EN ([website](https://www.monolithicpower.com/en/mp1484.html))
U6:  AMS1117-3.3 ([datasheet](http://www.advanced-monolithic.com/pdf/ds1117.pdf))
U7:  25Q32JVS1Q ([website](https://www.winbond.com/hq/product/code-storage-flash-memory/serial-nor-flash/?__locale=en&partNo=W25Q32JV))
U8:  PCF8563 ([datasheet](https://www.nxp.com/docs/en/data-sheet/PCF8563.pdf))
U9:  FM24CL168G ([website](https://www.infineon.com/cms/en/product/memories/f-ram-ferroelectric-ram/fm24cl16b-g/))
U10,U15-U32: EL357N
U11,U33: ULN2803ADW ([datasheet](https://media.digikey.com/pdf/Data%20Sheets/Texas%20Instruments%20PDFs/ULN2803A_Rev2015.pdf))
U12: SP3485E ([datasheet](https://assets.maxlinear.com/web/documents/sp3485.pdf))
U13: ? not found
U14: ? not found

J16: 4xpin 2.54 SWD for U1
J4: extension for additional leds

L1: 0805 ferrite seems for analog and digital power separation
L2,L3,L5: 0805 ferrite for RTL8201CP (U3) 
L4: 101 induction for DCDC power

D1: LED RDOK
D2: LED 4DOOR
D3: LED RUN
D12: LED POW (power)
D20(K2),D22(K3),D23(K4),D24(K5),D19(K1): LEDs for RELE 

D16,D17,D18,D21,D15: M4 diode
D11: M4 diode
D13,D14: ?

RJ1: Ethernet socket RJ45

BT1: CR1220 Battery socket

F1,F2,F3,F4,F5,F6,F7,F8,F9,F10: 07D470K fuse

F11: UN30 135 fuse

RT11,RT12: P 010 fuse

Q1: (Y1) MMBT8050/SS8050 SOT-23 ?PNP?NPN? transistor  transistor ([datasheet](https://datasheet.lcsc.com/lcsc/1912111437_PJSEMI-MMBT8050D_C411762.pdf))

PR1,PR3,PR7: (472) 4.7 kOm 4xR array resistor
PR2,PR4: (330) 330 Om 4xR array resistor
PR5,PR6: (512) 5.2 kOm 4xR array resistor

S1, S2: Buttons

K1,K2,K3,K4: HF3FF 012-1ZTF Subminiature High Power Relay ([website](https://www.hongfa.com/Product/Item/HF3FF))

RN1,RN2,RN3,RN4: A102J Resistor Network 1K 5%

