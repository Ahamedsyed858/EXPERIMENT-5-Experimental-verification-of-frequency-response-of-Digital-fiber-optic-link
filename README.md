# Exp 5 Experimental verification of frequency response of Digital fiber optic link
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

<img width="890" height="529" alt="Screenshot 2025-11-11 192121" src="https://github.com/user-attachments/assets/435b8e26-0b42-493e-9d58-2459aba62701" />

---

## TABULATION  
**Transmission through Digital Link**

![WhatsApp Image 2025-11-16 at 13 03 08_b3d31cc9](https://github.com/user-attachments/assets/eea8acc7-b3a9-4558-b716-27f3afad7daa)


---

## MODEL GRAPH

<img width="880" height="538" alt="Screenshot 2025-11-11 190804" src="https://github.com/user-attachments/assets/25ece563-cf37-448d-8b86-19078ca43f90" />

---

## GRAPH

![WhatsApp Image 2025-11-16 at 13 02 42_15291254](https://github.com/user-attachments/assets/10320a23-f6ef-4f58-bac3-c09d590ef782)

---

## RESULT

Thus, the frequency response of the **digital fiber optic link** was successfully verified.
The system exhibited a **stable response up to its cutoff frequency**, beyond which the signal amplitude decreased due to attenuation.
The **measured bandwidth of the digital fiber optic link is approximately 200 kHz**, confirming the expected performance characteristics of digital optical transmission.
