
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

<img width="867" height="506" alt="Screenshot 2025-11-17 180737" src="https://github.com/user-attachments/assets/d64b4d50-6a01-476e-8ef1-4d158b830be7" />


## TABULATION  
**Transmission through Analog Link**
![WhatsApp Image 2025-11-17 at 18 06 33_8509def2](https://github.com/user-attachments/assets/1aebdf3a-34f9-4562-a2ee-e246748ccf8c)


## MODEL GRAPH

![WhatsApp Image 2025-11-17 at 18 06 59_e2f4c157](https://github.com/user-attachments/assets/a5432307-376a-414d-a212-0b8d0acff3e4)

![WhatsApp Image 2025-11-17 at 18 06 02_a212e468](https://github.com/user-attachments/assets/234dcb11-41f9-4a2d-be95-4f4e8d7218d9)


## RESULT

Thus,the frequency response of the analog fiber optic link was successfully studied, and the bandwidth was determined to be 95 kHz.
