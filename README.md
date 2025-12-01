
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

- Fiber optic links can be used for transmission of digital as well as analog signals. Basically a
fiber optic link contains three main elements, a transmitter, an optical fiber and a receiver. The
transmitter module takes the input signal in electrical form and then transforms it into optical
(light) energy containing the same information. The optical fiber is the medium which takes
the energy to the receiver. At the receiver light is converted back into electrical form with the
same pattern as originally fed to the transmitter.
TRANSMITTER:
Fiber Optic transmitters are typically composed of a buffer, driver and Optical Source. The
buffer electronics provides both an electrical connection and isolation between the transmitter
and the electrical system supplying the data. The driver electronics provides electrical power to
the Optical source in a fashion that duplicates the pattern of data being fed to the transmitter.
Finally the optical source (LED) converts the electrical current to light energy with the same
pattern. The LED SFH450V (950nm) supplied with this kit operates outside the visible light
spectrum. Its Optical output is centered at near infrared wavelength of 950nm. The LED
SFH756V (660nm) supplied with this kit operates at the visible light spectrum. Its Optical output
is centered at wavelength of 660nm.
RECEIVER:
The function of the receiver is to convert the optical energy into electrical form, which is then
conditioned to reproduce the transmitted electrical signal in it's original form. The detector
SFH350V (Photo Transistor Detector) used in the kit has a transistor type output. The parameters
usually considered in the case of detector are it's responsivity at peak wavelength and response
time. SFH350V (Photo Transistor Detector) has responsivity of about 0.8mA/10uW at 660nm.
But its response time is quite large and thus has lower bandwidth of about 300 KHz. When
optical signal falls on the base of the transistor detector, proportional current flows through
its emitter generating the voltage across the resistance connected between emitter
and ground. This voltage is the duplication of the transmitted electrical signal, which can be amplified.

---

## PROCEDURE
- Refer to the block diagram and make the following connections.
- Keep all switch faults in OFF position.
- Slightly unscrew the cap of LED SFH756V (660nm). Do not remove the cap from the connector.
Once the cap is loosened, insert the 1-meter fiber into the cap. Now tighten the cap by screwing it
back.
- Slightly unscrew the cap of Photo Diode SFH250V. Do not remove the cap from the connector.
Once the cap is loosened, insert the other end of fiber into the cap. Now tighten the cap by
screwing it back.
- Keep the jumpers JP1 short for +12v, JP2 towards sine wave, JP3 short for
+12 v & JP4 towards TX1on FCL-01.
- Keep switch SW2 in VI position on FCL-01.
- Connect voltmeter and current meter as per the polarities shown in the block diagram.
- Switch on the power supply.
- Keep the potentiometer P3 in its maximum position (anti-clockwise rotation). P3 is used to control
current flowing through the LED.
- Keep the potentiometer P4 in its fully clockwise rotation.P4 is used to control bias voltage of the
LED.
- To get the IV characteristics of LED, rotate P3 slowly and measure forward current and
corresponding forward voltage. Take number of such readings for various current values and plot
IV characteristics graph for the LED.
- For each reading taken above, find out the power, which is product of I and
V. This is the electrical power supplied to the LED. Data sheets for the LED specify optical power coupled into
plastic fiber when forward current was 10 mA as 200 mW. This means that the electrical power at 10 mA
current is converted into 200 mW of optical energy. Hence the efficiency of the LED comes out to be approx.
1.15%.
- With this efficiency assumed, find out optical power coupled into plastic optical fiber for each of
the reading. Plot the graph of forward current v/s output optical power of the LED.
- Similarly measure the current at the detector.
- Plot the graph of receiver current v/s output optical power of the LED.
- Perform the above procedure again for all the combinations of Transmitter & Receiver.  
---


---

## BLOCK DIAGRAM

*<img width="1050" height="394" alt="image" src="https://github.com/user-attachments/assets/bea1f674-2db3-4c42-81c9-1beaeaf640e1" />*


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
