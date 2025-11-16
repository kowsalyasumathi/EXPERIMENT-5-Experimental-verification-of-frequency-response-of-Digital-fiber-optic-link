
Exp 5 Experimental verification of frequency response of Digital fiber optic link
# Digital Fiber Optic Link Analysis (600nm)

## AIM
To analyze the relationship between input and received signal of a 600nm fiber optic cable using digital link.

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
3. Make the following connections:  
   a. Connect the 1 KHz square wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to comparator 1’s input.  
   d. Connect comparator 1's output to AC amplifier 1's input.  
4. On the board, switch emitter 1's driver to digital mode.  
5. Switch on the power.  
6. Monitor both the inputs to comparator 1 (TP13 & TP14). Slowly adjust the comparator's bias preset until the DC level on TP13 lies midway between the high and low levels of the signal on TP14.  
7. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
8. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
9. Calculate the bandwidth by determining the gain in decibels (dB).  

---


## BLOCK DIAGRAM

<img width="725" height="429" alt="image" src="https://github.com/user-attachments/assets/c6df9e28-c550-4ef6-957d-adbe01f6bd39" />

---

## TABULATION  
**Transmission through Digital Link**

| Frequency (Hz) | Output Signal Amplitude (Vo) | Gain = Vo/Vi | Gain in dB |
|----------------|------------------------------|--------------|------------|
|   800Hz        |     2.5V                     |  0.5         |   -6.02
|  1KHz          |     32V                      |  6.4         |   16.12
|  2Khz          |     34V                      |  6.8         |   16.6
|  5KHz          |     36V                      |  7.2         |   17.14
|  10KHz         |     37V                      |  7.4         |   17.38
|  20KHz         |     37V                      |  7.4         |   17.38
|  50KHz         |     37V                      |  7.4         |   17.38
|  100KHz        |     27V                      |  5.4         |   14.64
|  250KHz        |     12.7V                    |  2.54        |    8.09


---

## MODEL GRAPH

<img width="805" height="386" alt="image" src="https://github.com/user-attachments/assets/ac8be9c2-1d75-46d4-86d8-b54c860d029d" />

GRAPH 

![WhatsApp Image 2025-11-12 at 22 39 24_f03ddfa7](https://github.com/user-attachments/assets/3ac1f21a-9a61-443e-b2bd-40edaf5a4f86)

---

## RESULT

Thus, the frequency response of the digital fiber optic link was successfully verified. The measured bandwidth of the digital fiber optic link is approximately 200 kHz, confirming the expected performance characteristics of digital optical transmission.
