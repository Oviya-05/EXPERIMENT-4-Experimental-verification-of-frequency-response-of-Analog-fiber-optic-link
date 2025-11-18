
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections (as shown in Figure 19):  
   a. Connect the 1KHz sine wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to AC amplifier 1 input.  
4. On the board, switch emitter 1's driver to analog mode.  
5. Switch on the power.  
6. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
7. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
8. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

*<img width="1050" height="394" alt="image" src="https://github.com/user-attachments/assets/bea1f674-2db3-4c42-81c9-1beaeaf640e1" />*

---

## CONNECTION DIAGRAM  
**Setting up an Analog Link**

*<img width="1061" height="220" alt="image" src="https://github.com/user-attachments/assets/93717bb2-cc84-4df4-9b53-bdbcbdeeacb5" />*

---

## TABULATION  
**Transmission through Analog Link**
<img width="1280" height="1154" alt="image" src="https://github.com/user-attachments/assets/20209a80-668b-4a97-8011-778337789fc3" />

---

## MODEL GRAPH

*<img width="891" height="446" alt="image" src="https://github.com/user-attachments/assets/58469c87-4be1-470e-ae0b-030d72a35e5b" />*

---

## GRAPH:
<img width="1280" height="972" alt="image" src="https://github.com/user-attachments/assets/8de1e611-f832-4ea1-8e90-e11bf7b4f624" />


## RESULT

*The transmitted and received waveforms for the 660 nm fiber link matched closely, confirming faithful analog and digital signal transfer. Output amplitude decreased with increasing frequency, showing the fiber link’s frequency-dependent response. The calculated –3 dB point confirms the bandwidth of the 660 nm analog/digital fiber optic link.*
