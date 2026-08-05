
# Experiment 4: 2-Bit Binary Ripple Carry Adder

## Objective

Design, construct, and test a two-bit binary ripple carry adder using
TTL integrated circuits.

## Components Used

- 74LS86 XOR gate
- 74LS08 AND gate
- 74LS02 NOR gate
- Solderless breadboard
- LEDs and resistors
- DIP switches
- 5 V power supply
- Digital multimeter

## Design

The circuit consists of two full-adder stages connected in cascade.
The carry output from the least-significant stage becomes the carry
input of the most-significant stage.

## Boolean Equations

### First full-adder stage

- Sum:
- Carry:

### Second full-adder stage

- Sum:
- Carry:

## Truth Table

<img width="1013" height="458" alt="image" src="https://github.com/user-attachments/assets/6af22495-e698-4cf4-b643-63b926aed854" />
<img width="1013" height="522" alt="image" src="https://github.com/user-attachments/assets/85fbdd90-d5dc-4894-b856-5fb4935a896e" />


## Logic Diagram

<img width="1013" height="671" alt="image" src="https://github.com/user-attachments/assets/6cc1f933-809e-4b88-97b6-42f3ad879e17" />


## Physical Implementation

<img width="362" height="471" alt="image" src="https://github.com/user-attachments/assets/e36d2145-b5af-4d4f-81fb-23e7edb87f90" />


## Testing

The circuit was tested using the input combinations provided in the
laboratory procedure.

| A | B | Carry In | Expected Sum | Observed Sum | Carry Out |
|---|---|---|---|---|---|
|   |   |   |   |   |   |

## Results
In this experiment a full adder was implemented using logic gates and tested for input combinations. The measured outputs agreed with the theoretical truth table. Low measured about 0.11V and High was about 4.5V consistently. The sum followed the equation A xor B xor Cin and the Cout = AB+Cin(A xor B ),



## What I Learned
Therefore this experiment confirmed the theoretical circuitry and the theoretical truth table of one full-bit adder. 
