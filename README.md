# Lincircuit
Linear integrated circuit design and simulation.

INTRODUCTION:

CS Amplifier: A Common Source (CS) amplifier is a fundamental MOSFET-based amplifier configuration commonly used in analog electronics. It offers voltage amplification with moderate gain and functions similarly to the common-emitter amplifier in BJTs.

Working of a CS Amplifier

 1. Circuit Components:
      
    • MOSFET ( n-channel)
    
    • Input signal (AC source is applied at the gate)
    
    • Drain resistor ( Rd )
    
    • Source resistor (Rs, sometimes bypassed with a capacitor Cs)

    • Load resistor ( Rl )
    
    • Biasing resistors (R1, R2) are essential for proper MOSFET operation.
    
    • Coupling capacitors (Cin, Cout) for AC signal transfer.
    
 2. Operation Steps:
       The AC input signal is applied to the gate of the MOSFET via a coupling capacitor. The gate-source voltage (Vgs) controls the drain current (Id) according to the MOSFET's transfer characteristics. Due to negative transconductance, an increase in Vgs leads to an increase in Id, causing a larger voltage drop across Rd. This results in an inverted output signal at the drain. The output voltage (Vout) is derived from the drain terminal.The gain of the amplifier is influenced by the MOSFET's transconductance (gm) and the load resistance.

3. Key Features:

   •	Voltage Gain: Av = - gmRd  ( CS amplifier without channel lenth modulation).

   •	Phase Inversion: The signal at the output is inverted to that at the input.

   •	High Input Impedance: Owing to the gate of the MOSFET with a near infinite resistance.

   •	Moderate Output Impedance: Varies with  Rd  and the MOSFET's output resistance.


4. Applications:

   •	Audio and RF amplifiers.

   •	Amplication of sensor signals.

   •	Buffer circuits in analog applications.

   •	Series active loads in integrated circuits.

   • used in oscillator circuits to produce AC signals.

   • used in medical equipment such as ECG and EEG equipment.

EXPERIMENT:

Aim: To find Id of given n-channel MOSFET and also vary width od MOSFET and check how that effects the current in the amplifier circuit. 


![image](https://github.com/user-attachments/assets/5ae705ef-4bae-4801-8349-f8078a862cba)



SPECIFICATIONS

LENGTH:180nm

WIDTH:1u

TYPE:n-CHANNEL MOSFET

![50u1](https://github.com/user-attachments/assets/8aaf05f1-9814-401d-9fe3-611308dd9f63)

DC ANALYSIS:

case 1:
![WhatsApp Image 2025-02-16 at 23 12 30_c4b478df](https://github.com/user-attachments/assets/da1bd67f-a17b-4d04-9ee0-621c509cf105)


case 2:
![WhatsApp Image 2025-02-16 at 23 12 30_7aa114b9](https://github.com/user-attachments/assets/9ee0c5d7-8461-4c1a-9eb6-51c102bb12a4)



INFERENCE: 

In case 1 and case 2, we see that the doubling of the channel width causes an increase in current in case 2. This is due to the fact that the greater the channel width, the greater the amount of charges passing through it, which means more current. The larger the channel width, the larger the number of charge carriers, which means an increase in current.

AC Analysis:

![ac1](https://github.com/user-attachments/assets/b59658b2-dda8-4d2f-8de6-91d3705179df)

![ac2](https://github.com/user-attachments/assets/049720a0-fbbf-4a18-a417-e5b90b3d4c2d)

1. Gate Voltage (First Image):

• The gate waveform has a larger amplitude, signifying that the input signal is correctly being input into the MOSFET.

• This also indicates that there is little or no attenuation in the gate terminal, as anticipated because it's being driven by the input source directly.

2. Drain Voltage (Second Image):
   
• The drain voltage waveform has a considerably smaller amplitude compared to the gate voltage.

•	That the MOSFET is not offering a lot of gain, possibly as a result of the short channel length (180 nm), which can cause short-channel effects that lower the transistor's amplifying ability.

•	The reduction in amplitude also points towards high output impedance or lesser transconductance, which impinges on signal strength at the drain.

Conclusion: 

• The MOSFET is being used as an amplifier, but due to the narrow channel length of 180 nm, its gain can be affecting, and that's why its drain voltage amplitude is reduced.

• The signal at the drain is smaller than the signal at the gate, which indicates the circuit could do with by increasing width of the transistor or biasing conditions) so the gain improves.

Transient Analysis:

![image](https://github.com/user-attachments/assets/358f6b24-270d-46f0-91a1-13174667683d)

![image](https://github.com/user-attachments/assets/7d766d2d-753c-4222-b618-9ff3167e8f4a)

INFERENCE:

Output voltage is inverted and amplified, because Id increases as gate coltage increases causing voltage drop across Rd.

waveform is smooth indecating low distortion and linear amplification, because there is no channel length modulation.

180 degree phase shift between input and output, because increase in gate voltahe decreases drain voltahe invertin the output.












