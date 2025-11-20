
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


## CONNECTION DIAGRAM  
-
<img width="624" height="394" alt="image" src="https://github.com/user-attachments/assets/8c1b675a-29df-4757-b5e7-efd5282a107b" />


---

## TABULATION  

-
<img width="432" height="424" alt="Screenshot 2025-11-17 202558" src="https://github.com/user-attachments/assets/637acb32-9ada-4041-850a-1672665fbad4" />


---

## MODEL GRAPH

-
<img width="837" height="367" alt="image" src="https://github.com/user-attachments/assets/3fa6751f-e76f-488b-b700-e1b3ead52c95" />



---
## OUTPUT GRAPH
-
![WhatsApp Image 2025-11-17 at 20 58 11_debcf850](https://github.com/user-attachments/assets/59d5d0ac-2dcf-46d2-8726-fb32f71fdf5b)
---


## RESULT
-
Thus, the frequency response of the analog fiber optic link was successfully studied, and the bandwidth was determined to be 75 kHz.
