# Version 1.2

<img width="1231" alt="pc34-to-s50_v1-2" src="https://user-images.githubusercontent.com/52176362/119267577-95383a00-bbef-11eb-85c4-89049008e32a.png">

![pc34-to-s50_v1-2_a](https://user-images.githubusercontent.com/52176362/119269741-86ef1b80-bbf9-11eb-8e46-12e0e1c9fdc9.jpg)

# Usage

1. Use a standard twisted PC floppy cable (ie. drive A: connected AFTER the twist and drive B: BEFORE the twist).
2. Jumper the 8" drive as the 1st drive (DRIVE SELECT 1, SH 50 pin 26). All other DS signals are not routed by this interface, so DS1 must always be jumpered on the 8" drive; DS2-4 are a dead end.
3. Connect the interface (Shugart-50) to the 8" drive using a suitable 50-pin cable and the appropriate adapters.
4. Connect the interface (PC-34) with the PC floppy cable header ...
    1. AFTER the twist. Then the 8" drive will be assigned as DOS drive -> A:
    2. BEFORE the twist. Then the 8" drive will be assigned as DOS drive -> B:

# Information

https://retrocmp.de/kicad/pc34-to-sh50/pc34-to-s50.htm
