# EXP-4
EXP. NO. 4. 		HALFWAVE  AND FULL WAVE  RECTIFIERS

AIM: To study the characteristics of half wave, full wave and bridge rectifier with and without filter and calculate the ripple factor, rectification efficiency and % regulation.

COMPONENTS  AND  EQUIPMENT  REQUIRED:  Diodes,  Resistor,  Transformer,  Voltmeter, Ammeter, Breadboard and CRO.

THEORY: Rectifier changes ac to dc and it is an essential part of power supply. The unique property of a diode, permitting the current to flow in one direction, is utilised in rectifiers.

Half Wave Rectifier


Mains power supply is applied at the primary of the step-down transformer. All the positive half cycles of the stepped down ac supply pass through the diode and all the negative half cycles get eliminated. Peak value of the output voltage is less than the peak value of the input voltage by 0.6V because of the voltage drop across the diode.
For a half wave rectifier, Vrms = Vm/2 and Vdc = Vm/π: where Vrms = rms value of input, Vdc = Average value of input and Vm = peak value of output.


Full Wave Rectifier
During the positive half cycle of the transformer secondary voltage, diode     is forward biased and      is reverse biased. So a current flows through the diode     , load resistor      and upper half of the transformer  winding.  During  the  negative  half  cycle,  diode       becomes  forward  biased  and becomes reverse biased. The current then flows through the diode     , load resistor      and lower half of the transformer winding. Current flows through the load resistor in the same direction during both the half cycles. Peak value of the output voltage is less than the peak value of the input voltage by 0.6V
because of the voltage drop across the diode.
During the positive half cycle of the secondary voltage, diodes      and      are forward biased and diodes and      are reverse biased. Therefore, current flows through the secondary winding, diode     , load resistor
and diode     . During the negative half cycle,      and      are forward biased and diodes      and      are reverse biased. Therefore, current flows through the secondary winding, diode     . Load resistor       During both the half cycles, the current flows through the load resistor in the same direction. Peak value of the output voltage is less than the peak value of the input voltage by 1.2V due to the voltage drop across two diodes. The ripple factor of the bridge rectifier is the same as that of full wave rectifier.
All rectifier outputs contain considerable amount of ripple in addition to the DC component. In order to avoid AC components, a filter is connected at the output of the rectifier.

Capacitor input filter, choke input filter, RC, CRC, LC, and CLC filters are the usually used filters. Capacitor input filter is the simplest and cheapest. A high value capacitor C is connected in shunt with the load resistor     . Capacitor charges to peak voltage      when the half cycle appears at the output. After the peak value is passed, the capacitor discharges through the load resistor slowly since the diode is reverse biased by the capacitor voltage. Before the capacitor voltage drops substantially, next output cycle arrives and the capacitor recharges to peak.

Rectifier Efficiency

Rectifier efficiency is defined as the ratio of DC output power to the input power from the AC supply. Even with ideal rectifiers with no losses, the efficiency is less than 100% because some of the output power is AC power rather than DC which manifests as ripple superimposed on the DC waveform.
PROCEDURE:

1.   Wire up the half wave rectifier circuit without capacitor after testing all the components.

2.   Switch on the main supply. Observe the transformer secondary voltage waveform and output voltage waveform across the load resistor, simultaneously on the CRO screen. Note down       and calculate
3.   Connect the capacitor filter and observe the waveforms. Note down and calculate ripple factor, rectifier efficiency and %regulation using the expressions. Repeat for different capacitor values.
4.   Repeat the above steps for full wave and bridge rectifiers.

CIRCUIT DIAGRAMS

Half wave rectifier with filter:

![WhatsApp Image 2025-12-14 at 8 25 40 PM](https://github.com/user-attachments/assets/07aaa749-6166-4ffa-baf3-904b08b5aafa)

WAVEFORM:

![WhatsApp Image 2025-12-14 at 8 28 53 PM](https://github.com/user-attachments/assets/96bde256-aaf2-455d-a1f9-ce4e15ee15d1)

Bridge rectifier with filter:

![WhatsApp Image 2025-12-14 at 8 25 39 PM (1)](https://github.com/user-attachments/assets/8db10fd5-0da0-4b54-a1ed-69d69e549bad)

WAVEFORM:

![WhatsApp Image 2025-12-14 at 8 25 50 PM](https://github.com/user-attachments/assets/30e2bb1f-f4f8-4a5a-b84a-617ddbd5a903)

TABULAR COLUMN
Rectifier without filter:

| **Input Voltage** |        | **Output Voltage (Without Filter)** |        | **Output Voltage (With Filter)** |        |
|-------------------|--------|-------------------------------------|--------|----------------------------------|--------|
| **Vm (V)**        | **t (ms)** | **Vm (V)**                        | **t (ms)** | **Vm (V)**                     | **t (ms)** |
| 100               | 20     | 100                                 | 10     | 100 V, 5 V                      | 5 ms, 25 ms |

TABULAR COLUMN
Rectifier with filter

## Tabular Column

| **Input Voltage** |        | **Output Voltage (Without Filter)** |        | **Output Voltage (With Filter)** |        |
|-------------------|--------|-------------------------------------|--------|----------------------------------|--------|
| **Vm (V)**        | **t (ms)** | **Vm (V)**                        | **t (ms)** | **Vm (V)**                     | **t (ms)** |
| 50               | 20     | 50                                 | 5     | 50 V, 46 V                      | 5 ms, 14 ms |

RESULT:

Input and Output waveforms of a half and full bridge-wave with /without filter are observed and plotted.
