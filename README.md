# Lincicuit
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
       The AC input signal is applied to the gate of the MOSFET via a coupling capacitor. The gate-source voltage (Vgs) controls the drain current (Id) according to the MOSFET's transfer characteristics.Due to negative transconductance, an increase in Vgs leads to an increase in Id, causing a larger voltage drop across Rd. This results in an inverted output signal at the drain. The output voltage (Vout) is derived from the drain terminal.The gain of the amplifier is influenced by the MOSFET's transconductance (gm) and the load resistance.

3. Key Features:

   •	Voltage Gain: Av = - gmRd  (assuming an ideal CS amplifier with zero source degeneration).

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

