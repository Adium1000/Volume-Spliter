# [Adrian's Volume Splitter V1.0](https://github.com/Adium1000/Volume-Spliter) Adrian's Volume Splitter V1.0

#### A simple passive 2-channel mono audio splitter with independent volume control for each output!

[![KiCad](https://img.shields.io/badge/kicad-%2300578F.svg?style=for-the-badge&logo=kicad&logoColor=white)](https://www.kicad.org/)
[![JLCPCB](https://img.shields.io/badge/JLCPCB-blue?style=for-the-badge)](https://jlcpcb.com)

[Key Features](#key-features) •
[PCB](#pcb) •
[BOM](#bom) •
[License](#license)

![PCB 3D Render](GP/PCB3D.png)

> **⚠️ Mono only!** This splitter does not separate left/right stereo channels. Both channels are combined into a single mono signal.

---

## Key Features

- **Passive design** — no power supply needed, works purely on signal level
- **2 independent outputs** — split one audio source into two separate channels
- **Per-output volume control** — RV1 and RV2 potentiometers let you adjust each output independently
- **3.5mm THT jacks** — standard audio connectors, easy to source and solder
- **Compact PCB** — clean layout with M3 mounting holes for easy enclosure mounting
- **Works best with a preamp** on the receiving end for optimal signal level

---

## How to Use

Plug your audio source into the **Input jack (J3)**. Then connect your two devices into **Output 1 (J1)** and **Output 2 (J2)**. Use pots **RV1** and **RV2** to adjust the volume of each output independently.

This module came out of my own need for a cheap way to share one audio source between two devices simultaneously. It works perfectly for my setup, so I went ahead and made a proper PCB for it.

---

## PCB

Designed in KiCad. Simple 2-layer board with through-hole components for easy hand soldering.

### 3D Model

![PCB 3D Render](GP/PCB3D.png)

### PCB Layout

![PCB Editor](GP/PCBEDITOR.png)

### Schematic

![Schematic](GP/SCHEMATIC.png)

### JLCPCB Order

Manufactured via [JLCPCB](https://jlcpcb.com) — $11.50 for 5 boards.

---

## BOM

| Ref | Component | Description | Qty | Unit Price | Total | Link |
|-----|-----------|-------------|-----|------------|-------|------|
| J1, J2, J3 | TRS Jack | 3.5mm Through-Hole Stereo Jack | 3 | ~$0.40 | ~$1.20 | [ArduShop](https://ardushop.ro/ro/conectori-tht/344-mufa-jack-audio-35mm-6427854003775.html) |
| RV1, RV2 | Potentiometer | Linear 50kΩ, panel mount | 2 | ~$0.29 | ~$0.57 | [ArduShop](https://ardushop.ro/ro/componente-discrete/280-376-potentiometru-liniar-10k-50k-100k.html#/158-valoare_rezistenta-50k) |
| — | Knobs | Potentiometer knob cap, White | 2 | ~$0.48 | ~$0.96 | [ArduShop](https://ardushop.ro/ro/componente-discrete/2247-1291-capac-pentru-potentiometru-encoder-buton.html#/3-culoare-alb) |
| H1–H4 | Mounting Hole | M3 screw hole, no copper | 4 | — | — | — |
| — | PCB | Adrian's Volume Splitter V1.0, Rev 1 | 1 | $11.50 | $11.50 | [JLCPCB](https://jlcpcb.com) |

**Total: ~$14.23**


---

## Credits

This project uses:

- [KiCad](https://www.kicad.org/) for PCB design
- [Hack Club Blueprint](https://blueprint.hackclub.com)
