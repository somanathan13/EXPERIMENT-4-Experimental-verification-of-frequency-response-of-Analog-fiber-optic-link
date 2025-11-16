# EXP-4-.Experimental-verification-of-frequency-response-of-Analog-fiber-optic-link

## AIM

 To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

## EQUIPMENTS REQUIRED

~~~
Fiber optic trainer kit ST 2502
Power supply
Patch cords
CRO (Cathode Ray Oscilloscope)
660 nm fiber cable
~~~

## THEORY

~~~
Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:

Transmitter: Converts the electrical input signal into optical (light) energy.
Optical Fiber: Serves as the transmission medium for the light signal.
Receiver: Converts the received light back into an electrical signal, preserving the original signal pattern.
~~~

## PROCEDURE

~~~
Connect the power supply to the board.
Ensure that all switched faults are set to ‘Off’.
Make the following connections (as shown in Figure 19):
a. Connect the 1KHz sine wave output to emitter 1's input.
b. Connect the fiber optic cable between emitter output and detector input.
c. Connect detector 1's output to AC amplifier 1 input.
On the board, switch emitter 1's driver to analog mode.
Switch on the power.
Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.
Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.
Calculate the bandwidth by determining the gain in decibels (dB).
~~~

## BLOCK DIAGRAM & CONNECTION DIAGRAM

![WhatsApp Image 2025-11-16 at 15 13 10_9b68cb37](https://github.com/user-attachments/assets/777c78a1-bd9e-4736-ad38-aafa7d34ea10)

## TABULATION

![WhatsApp Image 2025-11-16 at 15 13 27_42f6f208](https://github.com/user-attachments/assets/7b54e467-5f16-464e-b039-7ea5668b6dd6)
Transmission through Analog Link

|Frequency (Hz)	|Output Signal| Amplitude (Vo)|	Gain = Vo/Vi	Gain in dB|
|---------------|-------------|---------------|-------------------------|
|        100Hz  |      8.3v   |      1.6      |         3.4             |
|        500Hz  |      9.6v   |      1.9      |         5.57            |
|        1KHz   |      10.3v  |      2.06     |         6.27            |
|        3KHz   |      12.2v  |      2.44     |         7.74            |
|        5KHz   |      12.8v  |      2.56     |         8.16            |
|        10KHz  |      12.8v  |      2.56     |         8.16            |
|        20KHz  |      12.8v  |      2.56     |         8.16            |
|        50KHz  |      12.8v  |      2.56     |         8.16            |
|        100KHz |      12.8v  |      2.56     |         8.16            |
|        500KHz |      12.8v  |      2.56     |         8.16            |
|        1MHz   |      12.2v  |      2.44     |         7.74            |
|        3MHz   |      9.4v   |      1.88     |         5.48            |
|        5MHz   |      8.5v   |      1.38     |         3.97            |

## MODEL GRAPH

![WhatsApp Image 2025-11-16 at 15 13 17_f9ec1fc5](https://github.com/user-attachments/assets/8bf84e84-5f9a-41c0-872f-50cb3de1e434)

## RESULT

 Thus the frequency response of Analog fiber optic link has been verified sucessfully
