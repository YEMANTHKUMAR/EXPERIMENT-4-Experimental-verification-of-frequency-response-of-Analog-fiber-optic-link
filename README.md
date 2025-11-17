
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

<img width="632" height="366" alt="image" src="https://github.com/user-attachments/assets/5bf7785e-0edc-4e4d-895b-dbdfdeaf90fe" />


## CONNECTION DIAGRAM  
**Setting up an Analog Link**
<img width="354" height="131" alt="image" src="https://github.com/user-attachments/assets/f896dc2d-5cf8-43fc-aca4-c948b7c6dafd" />
<img width="271" height="119" alt="image" src="https://github.com/user-attachments/assets/59ee546a-7b0b-42c2-8dc8-9154b8e95b4f" />
<img width="280" height="122" alt="image" src="https://github.com/user-attachments/assets/3f36173d-d71f-418a-a341-bfd25030f05f" />



## TABULATION  
<img width="1152" height="1494" alt="image" src="https://github.com/user-attachments/assets/0689167d-fbeb-4174-bd9e-a01fbef0f868" />


## MODEL GRAPH

<img width="1123" height="1413" alt="image" src="https://github.com/user-attachments/assets/f2e722c7-f589-456d-91dd-e4f2da561f1b" />


---

## RESULT
Thus the  verification of frequency response of Analog fiber optic link are verified sucessfully
