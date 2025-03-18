# LC3b Simulator

Implements a complete ISA, FSM, datapath, and microsequencer to process Assembly instructions compatible with the LC3b. Has a modified FSM, datapath, and microsequencer to process interrupts and exceptions. Accounts for 1-time interrupt, protection exceptions, unknown opcode exceptions, and unaligned memory access exceptions. 

**Note: Currently being updated to handle instructions using pipelined processing.

## Control Store:
[controlstore.pdf](https://github.com/user-attachments/files/19302016/controlstore.pdf)

## Modified FSM:

![IMG_6037](https://github.com/user-attachments/assets/4bc3f806-f2b7-4633-a0fb-20edf7dca5d2)

## Modified Datapath:

![IMG_6039](https://github.com/user-attachments/assets/ee9e74f6-b771-466b-9209-14cdaf0bb18f)

## Modified Microsequencer:

![IMG_6038](https://github.com/user-attachments/assets/4c3d5d6f-9f24-43e9-8212-89de97a7c36c)
