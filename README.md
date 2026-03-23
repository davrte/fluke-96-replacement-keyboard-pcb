# Fluke 96 Replacement Keyboard PCB
A project to develop a reliable PCB-based replacement for the original Fluke 96 membrane keypad. Part of a restoration effort for vintage Fluke Scopemeters.

**⚠️ WORK IN PROGRESS (WIP) ⚠️**
This project is currently under development and testing. Designs may change. If you have suggestions, find an error, or have successfully tested a specific manufacturer, please write me. All feedback is welcome!

---

## What is this?
A project to replace the failing conductive rubber membranes in **Fluke 96** and **96B** Scopemeters. Instead of trying to "clean" old carbon pads that eventually fail again, this uses a dedicated PCB with integrated conductive pads to restore the keypad's life.

## The Design
I'm going to create two ways to build this depending on what you need (still under develpment):

* **Rigid Version (0.4mm):** Uses ultra-thin FR4. It's cheap to make at any standard PCB house.
* **Flex Version (0.11mm):** A true FPC (Flexible Printed Circuit) using Polyimide/Kapton. This is the closest to the original thickness but usually costs more to manufacture.

## Current Status & Folders
* `/Hardware/schematic`: Files for the schematic.
* `/Hardware/pcb/`: Files for the FR4/FPC version.
* `/Docs`: Pinout and basic notes.

🔍 Compatibility Notes

This design is specifically based on the Fluke 96/96B.

Based on community research and service manuals, many other 90 and 105 series Scopemeters appear to use the same keyboard layout and foil connector. However, there are some variations to keep in mind:

    Likely Compatible: Fluke 91, 92, 93, 95, 97, 99, and 105 (including "B" and "Series II" variants).

    Likely NOT Compatible: The Fluke 98 (Automotive) often uses a different internal board and is generally not a drop-in match for this specific design.

    The "Series" Difference: While the external buttons are the same, some very early units might have non-removable foils. Please check if your original foil is removable before ordering a PCB.

Help me verify: If you try this on a model other than the 96, please let me know or open an issue so we can update the list of confirmed working devices!

## Contributing / Feedback
If you've opened your Fluke 96 and noticed a different revision, or if you have a better idea for the trace routing, please let me know. I'm especially looking for feedback on the button "feel" between the 0.4mm and 0.11mm versions.

## License
CERN-OHL-S. Feel free to use it, just keep it open and give credit.
