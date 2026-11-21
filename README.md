# Elevator-Control-Design-
6th floor fpga based, elevator system using veriloghdl coding ,
We will build a complete 6-stop automatic elevator control system using Verilog HDL, including FSM design, RTL architecture, floor selection, door control, obstruction detection, timing delays, and simulation using a testbench.

# 1. Project specifications
We will consider six stops:

Floor ID	Floor name

0-	Basement (B)

1-	Ground / Floor 1

2-	Floor 2

3-	Floor 3

4-	Floor 4

5-	Floor 5

# Features of our elevator

Feature	Operation

Floor selection	Passenger selects any of six floors

Up movement	Elevator moves one floor at a time

Down movement	Elevator moves one floor at a time

Floor detection	Detects current floor

Request memory	Remembers pending floor requests

Door opening	Opens after reaching destination

Door delay	Remains open for a programmed time

Obstruction detection	Detects someone or an object interrupting the doorway

Door reopening	Reopens or remains open when obstruction is detected

Automatic closing	Closes after the delay if the doorway is clear

Idle state	Waits for new requests

                                                     # Block Diagram 

            <img width="1280" height="930" alt="block" src="https://github.com/user-attachments/assets/3cca3640-b19c-4da8-82a4-97cd42d0d2af" />

