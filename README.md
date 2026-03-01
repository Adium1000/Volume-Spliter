# 🎛️ Adrian's Volume Splitter V1.0

**A simple passive 2-channel mono audio splitter with independent volume control for each output.**


This project is a **passive audio splitter** designed to duplicate a single mono audio input into two independent audio outputs, each with its own volume potentiometer for balance control.

>  **Note:** This splitter does **not** distinguish between Left/Right stereo channels — it mixes both channels into a single mono signal. It works best when the connected output device uses any form of preamplification.

The board was designed in **KiCad** and features rounded PCB corners, custom silkscreen art, and a clean layout with through-hole TRS jacks and panel-mount potentiometers.

---

## BOM

- **Input (J3 - Mono):** Accepts a mono or mixed stereo signal via a TRS jack.
- **Output 1 (J1) & Output 2 (J2):** Two independent TRS outputs.
- **RV1 & RV2:** Potentiometers for independent volume control on each output channel.
- **4x Mounting Holes** for easy panel or enclosure mounting.

---

## Project Images

###  Schematic
> Inputs, outputs, potentiometers and mounting holes wired up in KiCad.

![Schematic](GP/SCHEMATIC.png)

---

### PCB Editor View
> Routed tracks, silkscreen art, rounded corners and component placement.

![PCB Editor](GP/PCBEDITOR.png)

---

### 3D Render
> 3D preview of the finished board from KiCad's 3D viewer.

![PCB 3D Render](GP/PCB3D.png)

