# SINCLAIR QL - GST ROM Board

Reverse Engineered in 2024 by Alvaro Alea Fernandez

License under: CERN Open Hardware Licence Version 2 - Strongly Reciprocal

https://ohwr.org/cern_ohl_s_v2.txt

My work is only copy the design to Kicad, all (C) are retaing to the original owners.

## THIS BOARD NOT WORK, IS WORK IN PROGRESS, INCOMPLETE, HAS NOT BEEN TESTED, NO WARRANTY OF WORKING

## IF YOU HAVE ADITIONAL INFORMATION OF THIS BOARD OR CAN PROVIDE DETAILLED PICTURES OF ONE, PLEASE CONTACT ME.

I think this board provide up to 4 x 16kB Rom (27128) expansion for the QL.

Is not clear the operation of the switch.

With the information o got from reverse engieering the chips are mapped to 0x40000, 0x44000, 0x48000, 0x4C000, This mean that this expansion board is located in the normal 512Kb expansion RAM area, and area incompatible with trump card, any expansion board, and also area useless on QDOS or Minvera, probably the intention of this board is to be used with GST's own operation system 68K/OS.

I will update this repository as soon as I got more information.

![PCB Componentes Side](pcb_comp.png)

![PCB Solder Side](pcb_sold.png)

