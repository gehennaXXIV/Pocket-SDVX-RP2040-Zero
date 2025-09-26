# Pocket-SDVX-RP2040-Zero

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).  
中国人，我在看你们。

## Changes from the original
- Removed LEDs and SMD parts for a simpler, lower-cost hand-solder build  
- Replaced the Pi Pico with an RP2040 Zero  
- Changed plate screws from M3 to M2 (using round spacers + rubber adhesive feet)  
- Switched from plate-mount to PCB-mount stabilizers  
- Added a 3D-printed case  

![Pocket SDVX RP2040 Zero v2](/pics/1.png)  
![Pocket SDVX RP2040 Zero v2](/pics/2.png)  

---

## Parts Required
- **JLCPCB boards** (180 × 100 mm, white, remove order number or specify location):  
  - 1× Pocket-SDVX-RP2040-Zero-Plate (MOQ 5)  
  - 1× Pocket-SDVX-RP2040-Zero (MOQ 5)  
- 1× RP2040 Zero  
- 1× 6×6×7 mm tactile switch (4-pin)  
- 2× Encoder – [PEC16-4015F-N0024](https://www.speedylabs.us/product/bourns-pec16-2015f-n0024-encoder/) (or any EC16 encoder with no detents)  
- 4× 1206 10nF SMD capacitors  
- 7× Any MX switches  
- 7× Gateron hotswap sockets  

## 
- 1× 3D-printed case  
- 4× M2×10 round standoffs (aligns plate with 3DP case + USB port)  
- 8× M2×6 screws  
- 4× M3×5 mm round acrylic spacers (7×3×5 mm tall, prevents PCB sag)  
- 2× 2U PCB-mount stabilizers (screw-in preferred)  
- 4× adhesive rubber feet  
- 1x optional 1.5mm clear acrylic top cutout

- XDA Keycap Set: https://www.speedylabs.us/product/pocket-sdvx-keycaps/  
  - 1× 1u  
  - 4× 1.5u  
  - 2× 2u  
- 2× 22 mm knobs: https://www.speedylabs.us/product/pocket-sdvx-aluminum-knob/  

---

## Assembly Notes
The RP2040 Zero is soldered from below, with the buttons facing upward.  

![Top](/pics/top.png)  
![Bottom](/pics/bottom.png)  
![Case](/pics/case.png)  

## Flashing the Firmware to RP2040 Zero

**Firmware to use:** [Download here](https://github.com/gehennaXXIV/Pico-Game-Controller/actions/runs/18004860285/artifacts/4103192028)

---

1. **Download** the firmware `.zip` file from the link above.  
2. **Extract** the `.uf2` file from the zip archive.  
3. On your RP2040 Zero, **press and hold** the **BOOT** button.  
4. While holding the button, **connect** the board to your computer via USB.  
5. The RP2040 Zero will appear as a **USB drive** on your computer.  
6. **Drag and drop** the `.uf2` firmware file onto the RP2040 Zero drive.  
7. The board will automatically reboot and run the new firmware.  

---

## Attribution
This project is a remix of [Pocket-SDVX-Pico-v4](https://github.com/speedypotato/Pocket-SDVX-Pico-v4) by **speedypotato**, licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).  

It is released under the same license.  
