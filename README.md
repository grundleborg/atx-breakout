atx-breakout
============

PCB Layout for an ATX Power Supply to Molex Connector Breakout Board.

Made in eagle 6.5.0 for Linux.

This board has a socket for one ATX 20 pin power connector, and breaks out every line on that socket
to a molex header. Each voltage goes to a two pin voltage and ground molex header, and the remaining
bits go to a 4 pin one.

Take a look at the board and schematic - it's pretty simple really.

The traces are 50mil wide - anecdotally that's enough for quite a high current, but if you are
worried about that, you should check yourself and modify it before getting the boards etched.

The board is designed to be within the 5cm x 10cm 2-Layer PCB constraints offered at
http://imall.iteadstudio.com/open-pcb/pcb-prototyping.html

Unfortunately, the 5cm x 5cm board is too small for the ATX connector.

Release branches/tags contain a folder called gerber with the files prepared by the imall CAM
processor ready to send directly to them to get it etched. However, please make sure you check
before sending them (e.g. using an online gerber viewer), as I don't accept any responsibility for
your PCBs coming back wrong even if you use files from here unmodified!
