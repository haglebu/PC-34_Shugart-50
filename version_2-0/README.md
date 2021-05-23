# Version 2.0

<img width="667" alt="pc34-to-s50_v2-0" src="https://user-images.githubusercontent.com/52176362/119268407-19d88780-bbf3-11eb-8cca-122837ce8735.png">

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
