# USB Hub / DAC

> [!NOTE]
> The design has a 22 ohm resistor across the DAC's crystal (I have no clue why I did that) but it should be 1M. It also worked fine just taking the 22 ohm resistor off and leaving it empty.

A simple USB hub with 3 USB C outputs and a built in DAC for a 3.5mm audio output. It uses a SL2.1a USB hub controller and a PCM2902 DAC. 

<img width="300" alt="PXL_20260926_223934899" src="https://github.com/user-attachments/assets/06d68dbd-d6bd-4887-b084-075f397af5bd" />
<img width="300" alt="PXL_20260926_223541052" src="https://github.com/user-attachments/assets/8a351c07-f4fd-48cb-8291-ae714f0ccb1e" />
<img width="300" alt="PXL_20260926_223615273" src="https://github.com/user-attachments/assets/3d1c81dd-34e2-49f4-9817-aa10be6396b1" />
<img width="300" alt="PXL_20260926_223722004" src="https://github.com/user-attachments/assets/abaaf9f8-964e-4fb0-8302-f52c7a3a819f" />


<img width="300" alt="USB Hub DAC PCB" src="https://github.com/user-attachments/assets/8f43eb14-09bb-46c3-a596-bbaf94097c08" />

## PCB
The PCB is designed to be mounted into the case using four M2x6mm screws into the four printed standoffs that use heat set inserts. The mute button is mounted on the top of the PCB and the case has a built in flexing tab that is used as a push button.

<img width="300" alt="usb-hub-dac pcb" src="https://github.com/user-attachments/assets/f5ecf870-a5ea-4690-a518-87bc4827ba6c" />


Layout

<img width="300" alt="image" src="https://github.com/user-attachments/assets/e107ba1a-4294-4f3e-9b9e-7bb35874dde2" />

Schematic

<img width="300" alt="image" src="https://github.com/user-attachments/assets/8b67b6f4-2d3e-4252-a612-6c1bf82170ce" />

## Parts

| Part                                    | Quantity | LCSC #    | Price (each) | Total price      | Link                                                       |
| --------------------------------------- | -------- | --------- | ------------ | ---------------- | ---------------------------------------------------------- |
| PCM 2902                                | 1        | C2651869  | $15.0753     | $15.0753         | [Link](https://www.lcsc.com/product-detail/C2651869.html)  |
| SL2.1a                                  | 1        | C192893   | $0.2259      | $1.13 (5 MOQ)    | [Link](https://www.lcsc.com/product-detail/C192893.html)   |
| USBLC6-2SC6                             | 4        | C2827654  | $0.0387      | $0.39 (10 MOQ)   | [Link](https://www.lcsc.com/product-detail/C2827654.html)  |
| PJ-320D 3.5mm TRRS Jack                 | 1        | C431535   | $0.0483      | $0.48 (10 MOQ)   | [Link](https://www.lcsc.com/product-detail/C431535.html)   |
| GCT_USB4110 USB C Port                  | 4        | C5143397  | $1.8037      | $7.21            | [Link](https://www.lcsc.com/product-detail/C5143397.html)  |
| 56k ohm 0805 Resistors                  | 6        | C2907336  | $0.0014      | $0.14 (100 MOQ)  | [Link](https://www.lcsc.com/product-detail/C2907336.html)  |
| 5.1k ohm 0805 Resistors                 | 2        | C2930296  | $0.0013      | $0.13 (100 MOQ)  | [Link](https://www.lcsc.com/product-detail/C2930296.html)  |
| 1.5k ohm 0805 Resistors                 | 1        | C2907216  | $0.0017      | $0.17 (100 MOQ)  | [Link](https://www.lcsc.com/product-detail/C2907216.html)  |
| 2.2 ohm 0805 Resistors                  | 1        | C2933402  | $0.0023      | $0.23 (100 MOQ)  | [Link](https://www.lcsc.com/product-detail/C2933402.html)  |
| 22 ohm 0805 Resistors                   | 3        | C2907310  | $0.0014      | $0.014 (100 MOQ) | [Link](https://www.lcsc.com/product-detail/C2907310.html)  |
| 10k ohm 0805 Resistors                  | 3        | C2930231  | $0.0012      | $0.012 (100 MOQ) | [Link](https://www.lcsc.com/product-detail/C2930231.html)  |
| 10uF Radial D4mm L8mm P1.5mm Capacitors | 4        | C36914040 | $0.0402      | $0.2 (5 MOQ)     | [Link](https://www.lcsc.com/product-detail/C36914040.html) |
| 10uF 0805 Capacitors                    | 6        | C1713     | $0.0088      | $0.18 (20 MOQ)   | [Link](https://www.lcsc.com/product-detail/C1713.html)     |
| 1uF 0805 Capacitors                     | 3        | C28323    | $0.0092      | $0.18 (20 MOQ)   | [Link](https://www.lcsc.com/product-detail/C28323.html)    |
| 10pF 0805 Capacitors                    | 2        | C41361255 | $0.0045      | $0.45 (100 MOQ)  | [Link](https://www.lcsc.com/product-detail/C41361255.html) |
| 6mm Push Button                         | 1        | C42416249 | $0.0196      | $0.39 (20 MOQ)   | [Link](https://www.lcsc.com/product-detail/C42416249.html) |
| 12 MHz Crystal                          | 2        | C16369    | $0.0834      | $0.42 (5 MOQ)    | [Link](https://www.lcsc.com/product-detail/C16369.html)    |

Total cost: \~$26.80 + PCB (\~$2)
