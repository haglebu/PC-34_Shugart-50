# Version 2.0

<img width="668" alt="pc34-to-s50_v2-1" src="https://user-images.githubusercontent.com/52176362/119269609-e4cf3380-bbf8-11eb-9f89-f99ac58fc353.png">

# Usage

1. Use a standard twisted PC floppy cable (ie. drive A: connected AFTER the twist and drive B: BEFORE the twist).
2. Jumper the 8" drive as the 1st drive (DRIVE SELECT 1, SH 50 pin 26), see figure 4 & 7. All other DS signals are not routed by this interface, so DS1 must ALWAYS be jumpered on the 8" drive; DS2-4 are a dead end.
3. Connect the interface (Shugart-50) to the 8" drive using a suitable 50-pin cable and the appropriate adapters.
4. Option 1: according to V1.2 / B: JP1 (2-3), JP2 (2-3)
    1. Connect the interface (PC-34) with the PC floppy cable header ...
      - ... AFTER the twist. Then the 8" drive will be assigned as DOS drive -> A:
      - ... BEFORE the twist. Then the 8" drive will be assigned as DOS drive -> B:
5. Option 2: / A: JP1 (1-2), JP2 (1-2)
    1. Connect the interface (PC-34) with the PC floppy cable header ...
      - ... AFTER the twist. Then the 8" drive will be assigned as DOS drive -> B:
      - ... BEFORE the twist. Then the 8" drive will be assigned as DOS drive -> A:

With these two jumper options, you are very flexible with your floppy cable and your drive assignment.

# Note

Unfortunately, I made a small design error here. The card edge connector should actually be on the other side. This is not possible, of course, because otherwise the connection to the 8" drive is wrong. The attentive observer will see this immediately. The footprint is wrong! Remedy: Simply solder on the edge connector from the front and everything is fine again. Now then!

# Information

https://retrocmp.de/kicad/pc34-to-sh50/pc34-to-s50.htm
