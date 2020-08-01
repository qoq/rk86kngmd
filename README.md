# rk86kngmd

A replica of 1993 floppy disc controller for "Radio-86RK" computers. Built around i8255 PPI chip (Soviet clone: КР580ВВ55А) and a handful of discrete logic chips.

This version is a compact rework of the replica. 

- Compact layout
- 74LS series SOIC chips are used instead of DIP 555 logic
- Kept КР580ВВ55А and К155ИР13 as they are much easier to source than i8255 and 74LS198
- 28-pin ROM socket accepts 27C32 or 27C64 EPROM chips
- Added 34-pin standard floppy cable connector and 4-pin Berg power supply connector (+5v/+12v)
- Added AND circutry (2 diodes) to form ROM CS signal from CS1/CS2
- Added two bypass capacitors for stability

![pops](./pics/board-3d-a.png)
![pops](./pics/board-3d-b.png)
